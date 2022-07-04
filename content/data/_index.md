---
title: Data
linktitle: Data 
toc: true
type: book
date: "2021-01-24T00:00:00+01:00"
draft: false


# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 0
---

<!-- Place this tag in your head or just before your close body tag. -->
<script async defer src="https://buttons.github.io/buttons.js"></script>

## Overview
The data are constructed from the UK business register, available from [Companies House]( https://www.gov.uk/government/organisations/companies-house) ([data]( http://download.companieshouse.gov.uk/en_output.html) here in .csv format). The register records every company in the UK with its birth date, post code and industry. This makes it possible to measure daily company registrations.

## Pros and Cons

The main advantage of the data is that it is timely (almost real-time nature) and covers the entire UK. A disadvantage is that it is not possible to identify companies that will employ and produce compared to those that are set up for accountancy purposes.

## Cleaning
We **exclude** firms with missing values on the incorporation date, post code and/or industry of main activity.

## Descriptive Statistics
The chart below shows the density of daily company registrations in the UK for 2020.

{{< chart data="density" >}}

## Country of Origin Registrations

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/ygalanak/CH-CountryOfOrigin/fork" aria-label="Fork ygalanak/CH-CountryOfOrigin on GitHub">ReplicateMe</a>

The chart below shows the UK and non-UK Country of Origin Registrations in Basic Companies Data since January 2019. De-select "United Kingdom" from the legend for a clearer plot of registrations among remaining countries. The legend is in size order.

{{< chart data="nonUK" >}}


## Outliers
### Week 53 2020
Week 53 2020 experiences a 6-fold increase in business registrations relative to week 53 2019. There are two reasons for this.

#### Leap year
In a normal year there are 365 days which is 52 7-day weeks and a 53rd 1-day week. In a leap year, such as 2020, there are 366 days which is 52 7-day weeks (364 days) and a 53rd 2-day week. Therefore, comparing week 53 in 2020 to other (non-leap) years includes twice the number of days. This contributes to a high number of relative registrations in week 53 2020. 

If we were to adjust for the leap year by halving the number of registrations in week 53 2020 so it represents one day, the comparison with 2019 still yield a 3-fold increase in firm registrations. 


#### EU-UK Trade and Cooperation Agreement (TCA)
Once adjusting for the leap year, the remaining 3-fold spike in firm registrations in week 53 2020 compared to week 53 2019 is likely due to a spike in registrations caused by the [EU-UK Trade and Cooperation Agreement (TCA)]( https://www.gov.uk/government/publications/agreements-reached-between-the-united-kingdom-of-great-britain-and-northern-ireland-and-the-european-union), signed on December 30th 2020.

Treating the excess firm registration of the last week as an outlier, we repeat the sectoral analysis, found [here]({{< relref "/reports/monthly/jan2021/#i-classfas-fa-industryi-span-classml-1sectoral-analysisspan" >}}), *without* considering the activity of the last two days of December. The only noticeable difference regards the administrative and support services whose firm creation on average come behind the arts, entertainment, and recreation sector. 

Looking only at the outliers, manufacturing, administrative and supportive services related businesses seem to register more than the same days in 2019. This static improve might be related to Brexit and the EU-UK TCA.

In terms of the regional analysis, an excess registration activity is observed in London, England, and Wales.

### Public Holidays and Weekends
Public holidays do not occur in the same week every year. This can affect comparisons across years when we total daily registrations because the same week may have a different number of working days.

Weekends typically observe near zero firm registrations. An exception to this rule-of-thumb is the first weekend after lockdown-I (July 4 and 5, 2020) which saw more than 3000 firms registered on the weekend.

### Postcode Areas
Some postcodes have extraordinarily high levels of firm registrations. These postcodes are typically accountancy firm addresses that offer "set up a company" services. The median number of registrations at a postcode in the dataset is 1, which is also the lower bound as every postcode on the register has at least one registration.

{{< chart data="postcode" >}}

*Table:* Summary statistics of Companies Registrations at a postcode 
|               | Mean  | SD    | Min | Q1 | Median | Q3 | Max |
|---------------|-------|-------|-----|----|--------|----|-----|
| registrations | 13.47 | 36.64 | 1   | 1  | 1      | 7  | 295 |
<small> **Note**: For registrations recorded between January 2020 and January 2021. </small>


## Archive data construction

To construct the archive monthly incorporation data, we use the historic snapshot registers from Companies House.

### Historic snapshot source and description

The historic snapshots are taken from [National Archives websites snapshots of the Companies House databases](https://webarchive.nationalarchives.gov.uk/*/http://download.companieshouse.gov.uk/en_output.html).

The National Archive web snapshots are taken unevenly since July 2012. Even when a snapshot is taken, the link may be broken. The following monthly snapshots do not work:

03-2015 <br>
10-2015 <br>
10-2016 <br>
09-2017 <br> 
03-2018 <br>
09-2019 <br>
03-2020 <br>
04-2020 <br>
05-2020 <br>

After 2017 the snapshots are available as a single data dump for the whole month rather than dividing the data into parts.

The biggest break is between 12-2014 and 05-2016. A break of 17 months. This break is due to both 2015 snapshots containing broken links and not available registers.

### How to construct?

To construct the archive data, we keep only the registrations occurred the last month and append them backwards. 

#### Example #1: Consecutive registers

Let two consecutive registers released on 1 May 2022 and 1 June 2022.

*Step 1:* Use register released on 1 June 2022

*Step 2:* Keep only registrations occurred on 1-31 May 2022

*Step 3:* Use register released on 1 May 2022

*Step 4:* Keep only registrations occurred on 1-30 April 2022

*Step 5*: Append data frames from steps 2 and 4.

#### Example #2: Non-consecutive registers

Let two registers available. One register released on 1 June 2020 and the immediate previous available register releases on 1 February 2020.

*Step 1:* Use register released on 1 June 2020

*Step 2:* Keep only registrations occurred on 1 February 2020 - 31 May 2020

*Step 3:* Use register released on 1 February 2020

*Step 4:* Keep only registrations occurred on 1-31 January 2020

*Step 5:* Append data frames from steps 2 and 4.

#### Example #3: Register of July 2012

The first available register was released on 1 July 2012. From this register we can count all the active firms at the time. However, Companies House removes dissolved companies from its register within 3 months. This means that we can measure, as accurately as possible, the number of registrations from 1 March 2012 in the register released on 1 July 2012.

### Robustness of measuring incorporations

To make sure we monitor incorporation registration in a similar fashion to Companies House, we compare our number of registrations to those in the CH quarterly report.

{{< chart data="comp_inc" >}}

### Archive descriptives
Looking at the archive of incorporation registrations, the following table summarises the descriptive stats by quarter

*Table:* Summary statistics of Company Registrations 
|               | Mean  | Min | Q1 | Median | Q3 | Max |
|---------------|-------|-----|----|--------|----|-----|
| registrations | 161,500  | 119,327   | 147,800  | 157,714     | 174,359  | 223,248 |

## Dissolutions

To monitor the dissolutions, we collect data from the [Companies House advanced search tool]( https://find-and-update.company-information.service.gov.uk/advanced-search) between 1 January 2010 and 31 May 2022. The tool displays only 10,000 observations in each search and allows a download of 5,000 observations. 

The number of dissolutions that we count matches the figures reported on the Companies House quarterly reports.


{{< chart data="comp_dis" >}}  	  	  	  	  	

