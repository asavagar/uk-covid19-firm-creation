---
title: Report January 2022
linktitle: January 2022
toc: true
type: book
date: "2022-01-06T00:00:00+01:00"
draft: false
menu:
  monthly:
  #    parent: Reports 2022
    weight: 14

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 14
---


We analyse Companies House ["basic company data"](http://download.companieshouse.gov.uk/en_output.html) up to the December 31st, 2021. We note less company registration relative to November 2021. The firm creation among active firms remains stronger than the same period in 2019.

## <i class="far fa-lightbulb"></i>  <span class="ml-1">Highlights</span>
1. Business creation decreased 19.1% between November 2021 and December 2021.
2. Business creation was 7.3% lower in December 2021 than in December 2020.
3. The largest number of company registrations occurs in ‘Public administration and defence; compulsory social security’ and ‘Wholesale, and Retail Trade’.


## <i class="fas fa-bullseye"></i> <span class="ml-1">Aggregate Analysis</span>
### Daily 
The chart below shows the daily company incorporations in the UK since January 2020. The lockdown periods correspond to our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline). 

{{< chart data="dailyagg" >}}
<small>Download histogram data as: <a href="data/01histogram.csv" download="01histogram.csv"><i class="fas fa-file-csv"></i></a>
</small>

- Business creation decreased by 19.1% between November and December 2021. 
- 21,429 additional companies were registered in December 2021 relative to December 2019. 
- 4,167 less company registrations are noticed in December 2021 relative to December 2020.
- The median daily registrations were 52.6% higher in December 2021 than December 2019. 

The chart below shows the rolling average of firm creation since January 2019. Shaded areas correspond to lockdown periods as shown our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline).

{{< chart data="rollAv" >}}
Download rolling average data as: <a href="data/08rollingAverage.csv" download="08rollingAverage.csv"><i class="fas fa-file-excel"></i></a></small>



### Relative  

Company registrations persistently exceed their 2019 levels. However, we notice a slowdown, which persists the last few months. 

{{< chart data="total" >}}
<small>Download data as: <a href="data/04ratio.csv" download="03ratio.csv"><i class="fas fa-file-csv"></i></a></small>

### December
Daily average company registrations in December 2021 are 7.3% lower than December 2020, but 67.6% higher than December 2019 among the active firms.

{{< chart data="november" >}}
<small>Download data as: <a href="data/03statsDec.csv" download="04december.csv"><i class="fas fa-file-csv"></i></a></small>

## <i class="fas fa-map-marker-alt"></i>  <span class="ml-1">Regional Analysis</span>

### Postcode Area
The map shows the average percentage change in new registrations in December 2021 compared to December 2019.  

<iframe src="mapJan2022Av.html" style="height:600px;width:100%;border:none;overflow:hidden;"></iframe>

### Country 
The following graph aggregates business creation by country. London, followed by Northern Ireland and Scotland, dominates business registrations. 

{{< chart data="country" >}}
<small>Download data as: <a href="data/05country.csv" download="05country.csv"><i class="fas fa-file-csv"></i></a></small>

### London
Within London, most of the business creation in December 2021 comes from South East, Central and East London. 

{{< chart data="london" >}}
<small>Download data as: <a href="data/06London.csv" download="06london.csv"><i class="fas fa-file-csv"></i></a></small>


## <i class="fas fa-industry"></i> <span class="ml-1">Sectoral Analysis</span>
### SIC Sections
The graph illustrates company registrations in November 2021 relative to 2019 by industrial sector. It compares the percentage change in 2021 relative to 2019 for each week of the year. We use 4-digit SIC levels (ONS "Classes") and group them into broader sectors (ONS "Sections"). We use the [ONS classification](https://onsdigital.github.io/dp-classification-tools/standard-industrial-classification/ONS_SIC_hierarchy_view.html). We show a selection of sectors that present notable changes. 

{{< chart data="sectors" >}}

- December 2021 retains higher firm creation in most sectors than December 2019.
- ‘Public administration and defence; compulsory social security’ and 'Wholesale, and Retail Trade' sectors show the greatest increase in firm creation in December 2021. 
- Compared to December 2019, in December 2021 there is more than a 300% increase in business creation for ‘Retail sale of electrical household appliances in specialised stores’, ‘Other retail sale not in stores, stalls or markets’, ‘Regulation of the activities of providing health care, education, cultural services and other social services, excluding social security’ sectors.
- There are lower registrations relative to December 2019 in ‘Warehousing and storage’, ‘Activities of holding companies’, ‘Accounting, bookkeeping and auditing activities; tax consultancy’ sectors. 

{{< cta cta_text="Snapshot" cta_link="/reports/monthly/jan2022/January2022.pdf" cta_new_tab="true" >}}

