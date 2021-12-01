---
title: Report December 2021
linktitle: December 2021
toc: true
type: book
date: "2021-12-01T00:00:00+01:00"
draft: false
menu:
  monthly:
  #    parent: Reports 2021
    weight: 12

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 12
---

## In a nutshell



We analyse Companies House ["basic company data"](http://download.companieshouse.gov.uk/en_output.html) up to the November 30th, 2021. We note more company registration relative to October 2021. The firm creation among active firms remains stronger than the same period in 2019.

## <i class="far fa-lightbulb"></i>  <span class="ml-1">Highlights</span>
1. Business creation increased 4.3% between October 2021 and November 2021.
2. Business creation was 2.1% lower in November 2021 than in November 2020.
3. The largest number of company registrations occurs in 'Wholesale and retail trade; repair of motor vehicles and motorcycles' and ‘Transportation and storage’.


## <i class="fas fa-bullseye"></i> <span class="ml-1">Aggregate Analysis</span>
### Daily 
The chart below shows the daily company incorporations in the UK since January 2020. The lockdown periods correspond to our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline). 

{{< chart data="dailyagg" >}}
<small>Download histogram data as: <a href="data/01histogram.csv" download="01histogram.csv"><i class="fas fa-file-csv"></i></a>
  <br>
Download statistics as: <a href="data/02statsLockdown.xlsx" download="02statistics.xlsx"><i class="fas fa-file-excel"></i></a></small>

- Business creation increased by 4.3% between October and November 2021. 
- 26,248 additional companies were registered in November 2021 relative to November 2019. 
- 1,411 less company registrations are noticed in November 2021 relative to November 2020.
- The median daily registrations were 65% higher in November 2021 than November 2019. 

The chart below shows the rolling average of firm creation since January 2019. Shaded areas correspond to lockdown periods as shown our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline).

{{< chart data="rollAv" >}}
Download rolling average data as: <a href="data/08rollingAverage.csv" download="08rollingAverage.csv"><i class="fas fa-file-excel"></i></a></small>



### Relative  

Company registrations persistently exceed their 2019 levels. However, we notice a slowdown, which persists the last few months. 

{{< chart data="total" >}}
<small>Download data as: <a href="data/04ratio.csv" download="03ratio.csv"><i class="fas fa-file-csv"></i></a></small>

### November
Daily average company registrations in November 2021 are 2.1% lower than November 2020, but 67% higher than November 2019 among the active firms.

{{< chart data="october" >}}
<small>Download data as: <a href="data/03statsSept.csv" download="04november.csv"><i class="fas fa-file-csv"></i></a></small>

## <i class="fas fa-map-marker-alt"></i>  <span class="ml-1">Regional Analysis</span>

### Postcode Area
The map shows the average percentage change in new registrations in November 2021 compared to October 2019.  

<iframe src="mapDec2021Av.html" style="height:600px;width:100%;border:none;overflow:hidden;"></iframe>

### Country 
The following graph aggregates business creation by country. London, followed by Wales, dominates business registrations. 

{{< chart data="country" >}}
<small>Download data as: <a href="data/05country.csv" download="05country.csv"><i class="fas fa-file-csv"></i></a></small>

### London
Within London, most of the business creation in November 2021 comes from Central, South East and East London. 

{{< chart data="london" >}}
<small>Download data as: <a href="data/06London.csv" download="06london.csv"><i class="fas fa-file-csv"></i></a></small>


## <i class="fas fa-industry"></i> <span class="ml-1">Sectoral Analysis</span>
### SIC Sections
The graph illustrates company registrations in November 2021 relative to 2019 by industrial sector. It compares the percentage change in 2021 relative to 2019 for each week of the year. We use 4-digit SIC levels (ONS "Classes") and group them into broader sectors (ONS "Sections"). We use the [ONS classification](https://onsdigital.github.io/dp-classification-tools/standard-industrial-classification/ONS_SIC_hierarchy_view.html). We show a selection of sectors that present notable changes. 

{{< chart data="sectors" >}}
<small>Download data as: <a href="data/07sections.csv" download="07sections.csv"><i class="fas fa-file-csv"></i></a></small>

- November 2021 retains higher firm creation in most sectors than November 2019.
- 'Wholesale, and Retail Trade' and ‘Transportation and storage’ sectors show the greatest increase in firm creation in November 2021. 
- Compared to November 2019, in November 2021 there is more than a 300% increase in business creation for ‘Combined office administrative service activities’, ‘Publishing of computer games’, `Other retail sale not in stores, stalls or markets' and ‘Non-specialised wholesale trade' sectors. 
- There are lower registrations relative to November 2019 in ‘Activities of holding companies', ‘Engineering activities and related technical consultancy’ and ‘Renting and operating of own or leased real estate'. 

{{< cta cta_text="Snapshot" cta_link="/reports/monthly/nov2021/November2021.pdf" cta_new_tab="true" >}}

