---
title: Data
linktitle: Data 
toc: true
type: docs
date: "2021-01-24T00:00:00+01:00"
draft: false
menu:
  reports:
#    parent: Reports
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 0
---

## Overview
The data are constructed from the UK business register, available from [Companies House]( https://www.gov.uk/government/organisations/companies-house) ([data]( http://download.companieshouse.gov.uk/en_output.html) here in .csv format). The register records every company in the UK with its birth date, post code and industry. This makes it possible to measure daily company registrations.

## Pros and Cons

The main advantage of the data is that it is timely (almost real-time nature) and covers the entire UK. A disadvantage is that it is not possible to identify companies that will employ and produce compared to those that are set up for accountancy purposes.

## Cleaning
We **exclude** firms with missing values on the incorporation date, post code and/or industry of main activity.

## Descriptive Statistics
The chart below shows the density of daily company registrations in the UK for 2020.

{{< chart data="density" >}}

## Non-UK Country of Origin Registrations
The chart below shows the non-UK Country of Origin Registrations in Basic Companies Data since January 2019.

{{< chart data="non-UK" >}}


## Outliers
### Week 53 2020
Week 53 2020 experiences a 6-fold increase in business registrations relative to week 53 2019. There are two reasons for this.

#### Leap year
In a normal year there are 365 days which is 52 7-day weeks and a 53rd 1-day week. In a leap year, such as 2020, there are 366 days which is 52 7-day weeks (364 days) and a 53rd 2-day week. Therefore, comparing week 53 in 2020 to other (non-leap) years includes twice the number of days. This contributes to a high number of relative registrations in week 53 2020. 

If we were to adjust for the leap year by halving the number of registrations in week 53 2020 so it represents one day, the comparison with 2019 still yield a 3-fold increase in firm registrations. 


#### EU-UK Trade and Cooperation Agreement (TCA)
Once adjusting for the leap year, the remaining 3-fold spike in firm registrations in week 53 2020 compared to week 53 2019 is likely due to a spike in registrations caused by the [EU-UK Trade and Cooperation Agreement (TCA)]( https://www.gov.uk/government/publications/agreements-reached-between-the-united-kingdom-of-great-britain-and-northern-ireland-and-the-european-union), signed on December 30th 2020.

Treating the excess firm registration of the last week as an outlier, we repeat the sectoral analysis, found [here]({{< relref "../jan2021/#i-classfas-fa-industryi-span-classml-1sectoral-analysisspan" >}}), *without* considering the activity of the last two days of December. The only noticeable difference regards the administrative and support services whose firm creation on average come behind the arts, entertainment, and recreation sector. 

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
