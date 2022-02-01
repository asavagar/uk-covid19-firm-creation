---
title: Report February 2022
linktitle: February 2022
toc: true
type: book
date: "2022-02-01T00:00:00+01:00"
draft: false
menu:
  monthly:
  #    parent: Reports 2022
    weight: 15

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 15
---


We analyse Companies House ["basic company data"](http://download.companieshouse.gov.uk/en_output.html) up to the January 31st, 2021. We note more company registration relative to December 2021. The firm creation among active firms remains stronger than the same period in 2019.

## <i class="far fa-lightbulb"></i>  <span class="ml-1">Highlights</span>
1. Business creation increased 21% between December 2021 and January 2022.
2. Business creation was 49% higher in January 2022 than in January 2020 and 3% higher in January 2022 than in January 2021.
3. The largest number of company registrations occurs in 'Wholesale and retail trade; repair of motor vehicles and motorcycles' and ‘Transportation and storage’.


## <i class="fas fa-bullseye"></i> <span class="ml-1">Aggregate Analysis</span>
### Daily 
The chart below shows the daily company incorporations in the UK since January 2020. The lockdown periods correspond to our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline). 

{{< chart data="dailyagg" >}}
<small>Download histogram data as: <a href="data/01histogram_Jan 2022.csv" download="01histogram_Jan 2022.csv"><i class="fas fa-file-csv"></i></a>
<br>
Download statistics as: <a href="data/02statsLockdown_Jan 2022.csv" download="02statisticsLockdown.csv"><i class="fas fa-file-csv"></i></a></small>

<small>

- Business creation increased by 3% between December 2021 and January 2022. 
- 28,523 additional companies were registered in January 2022 relative to January 2019. 
- 21,051 more company registrations are noticed in January 2022 relative to January 2020.
- 1,836 more company registrations are noticed in January 2022 relative to January 2021.
- The median daily registrations were 82% higher in January 2022 than January 2019.  

The chart below shows the rolling average of firm creation since January 2019. Shaded areas correspond to lockdown periods as shown our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline).

{{< chart data="rollAv" >}}
Download rolling average data as: <a href="data/08rollingAverage_Jan 2022.csv" download="08rollingAverage_Jan 2022.csv"><i class="fas fa-file-excel"></i></a></small>



### Relative  

Company registrations persistently exceed their 2019 levels. Extensive business activity is observed during the first 2 weeks of January 2022. Week 3 onwards, companies registration ratio narrows the gap and reaches the 2021/2019 ratio.

{{< chart data="total" >}}
<small>Download data as: <a href="data/04ratio_Jan 2022.csv" download="03ratio_Jan 2022.csv"><i class="fas fa-file-csv"></i></a></small>

### January
Daily average company registrations in January 2021 are 49% higher than January 2020, but 80% higher than January 2019 among the active firms. 

{{< chart data="january" >}}
<small>Download data as: <a href="data/03stats_Jan 2022.csv" download="04january.csv"><i class="fas fa-file-csv"></i></a></small>

## <i class="fas fa-map-marker-alt"></i>  <span class="ml-1">Regional Analysis</span>

### Postcode Area
The map shows the average percentage change in new registrations in January 2022 compared to January 2019.  

<iframe src="mapFeb2022Av.html" style="height:600px;width:100%;border:none;overflow:hidden;"></iframe>

<small>Download data as: <a href="data/09map_Jan 2022.csv" download="09map.csv"><i class="fas fa-file-csv"></i></a></small>

### Country 
The following graph aggregates business creation by country. London, followed by Northern Ireland, dominates business registrations. In week 1, Scotland follows London. This trend vanishes the coming weeks of 2022.

{{< chart data="country" >}}
<small>Download data as: <a href="data/05country_Jan2022.csv" download="05country_Jan2022.csv"><i class="fas fa-file-csv"></i></a></small>

### London
Within London, most of the business creation in January 2022 comes from Central, East and North of London. 

{{< chart data="london" >}}
<small>Download data as: <a href="data/06London_Jan 2022.csv" download="06london_Jan2022.csv"><i class="fas fa-file-csv"></i></a></small>


## <i class="fas fa-industry"></i> <span class="ml-1">Sectoral Analysis</span>
### SIC Sections
The graph illustrates company registrations in January 2022 relative to 2019 by industrial sector. It compares the percentage change in 2021 relative to 2019 for each week of the year. We use 4-digit SIC levels (ONS "Classes") and group them into broader sectors (ONS "Sections"). We use the [ONS classification](https://onsdigital.github.io/dp-classification-tools/standard-industrial-classification/ONS_SIC_hierarchy_view.html). We show a selection of sectors that present notable changes. 

{{< chart data="sectors" >}}

- January 2022 retains higher firm creation in most sectors than January 2019.
- ‘Public administration and defence; compulsory social security’ and 'Wholesale, and Retail Trade' sectors show the greatest increase in firm creation in January 2022, as last month. 
- Compared to January 2019, in January 2022 there is more than a 300% increase in business creation for ‘Other retail sale not in stores, stalls or markets’, ‘Removal services’, ‘General cleaning of buildings’ and ‘Manufacture of sports goods’ sectors.
- There are lower registrations relative to January 2019 in ‘Packaging activities’, ‘Warehousing and storage’ and ‘Manufacture of perfumes and toilet preparations’ sectors. 

{{< cta cta_text="Snapshot" cta_link="/reports/monthly/jan2022/January2022.pdf" cta_new_tab="true" >}}

