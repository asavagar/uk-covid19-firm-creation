---
title: Report October 2021
linktitle: October 2021
toc: true
type: book
date: "2021-10-01T00:00:00+01:00"
draft: false
menu:
  monthly:

#    parent: Reports 2021
    weight: 11

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 11
---

## In a nutshell

We analyse Companies House ["basic company data"](http://download.companieshouse.gov.uk/en_output.html) up to the September 30th, 2021. We note a slowdown in company registration relative to September 2021. However, firm creation among active firms remains stronger than the same month in 2019.

## <i class="far fa-lightbulb"></i>  <span class="ml-1">Highlights</span>
1. Business creation increased 9.8% between August 2021 and September 2021.
2. Business creation was 9.5% lower in September 2021 than in September 2020.
3. The largest number of company registrations occurs in 'Wholesale and retail trade; repair of motor vehicles and motorcycles' and ‘Transportation and storage’. Closer to the end of August 2021, 'Administrative and support service activities’ present an increase. 


## <i class="fas fa-bullseye"></i> <span class="ml-1">Aggregate Analysis</span>
### Daily 
The chart below shows the daily company incorporations in the UK since January 2020. The lockdown periods correspond to our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline). 

{{< chart data="dailyagg" >}}
<small>Download histogram data as: <a href="data/01histogram.csv" download="01histogram.csv"><i class="fas fa-file-csv"></i></a>
  <br>
Download statistics as: <a href="data/02statsLockdown.xlsx" download="02statistics.xlsx"><i class="fas fa-file-excel"></i></a></small>

- Business creation increased by 9.81% between August and September 2021. 
- 22,101 additional companies were registered in September 2021 relative to September 2019. 
- 6,763 less company registrations are noticed in September 2021 relative to September 2020.
- The median daily registrations were 48.3% higher in September 2021 than September 2019. 

The chart below shows the rolling average of firm creation since January 2019. Shaded areas correspond to lockdown periods as shown our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline).

{{< chart data="rollAv" >}}
Download rolling average data as: <a href="data/08rollingAverage.csv" download="08rollingAverage.csv"><i class="fas fa-file-excel"></i></a></small>



### Relative  

Company registrations persistently exceed their 2019 levels. This effect is strong regardless the third national lockdown. However, we notice a slowdown, which continues from the last few months, in September 2021 relative to September 2020. However, the September 2021 slowdown is smaller than the August 2021 one.

{{< chart data="total" >}}
<small>Download data as: <a href="data/04ratio.csv" download="03ratio.csv"><i class="fas fa-file-csv"></i></a></small>

### September
Daily average company registrations in September 2021 are 9.56% lower than September 2020, but 52% higher than August 2019 among the active firms.

{{< chart data="september" >}}
<small>Download data as: <a href="data/03statsSept.csv" download="04september.csv"><i class="fas fa-file-csv"></i></a></small>

## <i class="fas fa-map-marker-alt"></i>  <span class="ml-1">Regional Analysis</span>

### Postcode Area
The map shows the average percentage change in new registrations in September 2021 compared to September 2019.  

<iframe src="mapOct2021Av.html" style="height:600px;width:100%;border:none;overflow:hidden;"></iframe>

### Country 
The following graph aggregates business creation by country. London, followed by Northern Ireland and Wales, dominates business registrations. 

{{< chart data="country" >}}
<small>Download data as: <a href="data/05country.csv" download="05country.csv"><i class="fas fa-file-csv"></i></a></small>

### London
Within London, most of the business creation in September 2021 comes from Central, South East and West London. 

{{< chart data="london" >}}
<small>Download data as: <a href="data/06London.csv" download="06london.csv"><i class="fas fa-file-csv"></i></a></small>


## <i class="fas fa-industry"></i> <span class="ml-1">Sectoral Analysis</span>
### SIC Sections
The graph illustrates company registrations in September 2021 relative to 2019 by industrial sector. It compares the percentage change in 2021 relative to 2019 for each week of the year. We use 4-digit SIC levels (ONS "Classes") and group them into broader sectors (ONS "Sections"). We use the [ONS classification](https://onsdigital.github.io/dp-classification-tools/standard-industrial-classification/ONS_SIC_hierarchy_view.html). We show a selection of sectors that present notable changes. 

{{< chart data="sectors" >}}
<small>Download data as: <a href="data/07sections.csv" download="07sections.csv"><i class="fas fa-file-csv"></i></a></small>

- September 2021 retains higher firm creation in most sectors than September 2019.
- `Transportation and storage’, 'Wholesale, and Retail Trade' and 'Construction' sectors show the greatest increase in firm creation in September 2021. 
- Towards the end of September 2021, ‘Administrative and support service activities' sector presents an increase.
- Compared to September 2019, in September 2021 there is more than a 300% increase in business creation for ‘Event catering activities’, ‘General public administration activities’, 'Retail sale of music and video recordings in specialised stores' and ‘Wholesale of other intermediate products' sectors. 
- There are lower registrations relative to August 2019 in 'Activities of business and employers membership organisations', ‘Tour operator activities’ and 'Construction of railways and underground railways'. 

{{< cta cta_text="Snapshot" cta_link="/reports/sept2021/Sept2021.pdf" cta_new_tab="true" >}}
