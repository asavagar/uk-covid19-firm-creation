---
title: Report September 2021
linktitle: September 2021
toc: true
type: book
date: "2021-08-02T00:00:00+01:00"
draft: false
menu:
  monthly:

#    parent: Reports 2021
    weight: 10

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 10
---

## In a nutshell


We analyse Companies House ["basic company data"](http://download.companieshouse.gov.uk/en_output.html) up to the August 31st, 2021. We note a slowdown in company registration relative to August 2020. However, firm creation remains stronger than the same month in 2019.

## <i class="far fa-lightbulb"></i>  <span class="ml-1">Highlights</span>
1. Business creation decreased 1.18% between July 2021 and August 2021.
2. Business creation was 12.1% lower in August 2021 than in August 2020.
3. The largest number of company registrations occurs in 'Wholesale and retail trade; repair of motor vehicles and motorcycles' and ‘Transportation and storage’. Closer to the end of August 2021, 'Financial and insurance activities’ present an increase. 


## <i class="fas fa-bullseye"></i> <span class="ml-1">Aggregate Analysis</span>
### Daily 
The chart below shows the daily company incorporations in the UK since January 2020. The lockdown periods correspond to our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline). 

{{< chart data="dailyagg" >}}
<small>Download histogram data as: <a href="data/01histogram.csv" download="01histogram.csv"><i class="fas fa-file-csv"></i></a>
  <br>
Download statistics as: <a href="data/02statsLockdown.xlsx" download="02statistics.xlsx"><i class="fas fa-file-excel"></i></a></small>

- Business creation decreased by 1.18% between July and August 2021. 
- 19,104 additional companies were registered in August 2021 relative to August 2019. 
- 7,998 less company registrations are noticed in August 2021 relative to August 2020.
- The median daily registrations were 47.3% higher in July 2021 than July 2019. 

The chart below shows the rolling average of firm creation since January 2019. Shaded areas correspond to lockdown periods as shown our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline).

{{< chart data="rollAv" >}}
Download rolling average data as: <a href="data/08rollingAverage.csv" download="08rollingAverage.csv"><i class="fas fa-file-excel"></i></a></small>



### Relative  

Company registrations persistently exceed their 2019 levels. This effect is strong regardless the third national lockdown. However, we notice a slowdown, which continues from the previous month, in August 2021 relative to August 2020. However, the August 2021 slowdown is smaller than the July 2021 one.

{{< chart data="total" >}}
<small>Download data as: <a href="data/04ratio.csv" download="03ratio.csv"><i class="fas fa-file-csv"></i></a></small>

### August
Daily average company registrations in August 2021 are 13.16% lower than August 2020, but 45% higher than August 2019.

{{< chart data="august" >}}
<small>Download data as: <a href="data/03statsAugust.csv" download="04may.csv"><i class="fas fa-file-csv"></i></a></small>

## <i class="fas fa-map-marker-alt"></i>  <span class="ml-1">Regional Analysis</span>

### Postcode Area
The map shows the average percentage change in new registrations in August 2021 compared to August 2019.  

<iframe src="mapSept2021Av.html" style="height:600px;width:100%;border:none;overflow:hidden;"></iframe>

### Country 
The following graph aggregates business creation by country. London, followed by Northern Ireland, dominates business registrations. 

{{< chart data="country" >}}
<small>Download data as: <a href="data/05country.csv" download="05country.csv"><i class="fas fa-file-csv"></i></a></small>

### London
Within London, most of the business creation in August 2021 comes from Central, West and South East London. 

{{< chart data="london" >}}
<small>Download data as: <a href="data/06London.csv" download="06london.csv"><i class="fas fa-file-csv"></i></a></small>


## <i class="fas fa-industry"></i> <span class="ml-1">Sectoral Analysis</span>
### SIC Sections
The graph illustrates company registrations in August 2021 relative to 2019 by industrial sector. It compares the percentage change in 2021 relative to 2019 for each week of the year. We use 4-digit SIC levels (ONS "Classes") and group them into broader sectors (ONS "Sections"). We use the [ONS classification](https://onsdigital.github.io/dp-classification-tools/standard-industrial-classification/ONS_SIC_hierarchy_view.html). We show a selection of sectors that present notable changes. 

{{< chart data="sectors" >}}
<small>Download data as: <a href="data/07sections.csv" download="07sections.csv"><i class="fas fa-file-csv"></i></a></small>

- August 2021 retains higher firm creation in most sectors than August 2019.
- `Transportation and storage’ and 'Wholesale, and Retail Trade' sectors show the greatest increase in firm creation in August 2021. 
- Towards the end of August 2021, ‘Financial and insurance activities' sector presents an increase.
- Compared to August 2019, in August 2021 there is more than a 300% increase in business creation for ‘Repair of communication equipment’, ‘Water collection, treatment and supply’, 'Camping grounds, recreational vehicle parks and trailer parks' and ‘Event catering activities' sectors. 
- There are lower registrations relative to August 2019 in 'Construction of railways and underground railways', ‘Wholesale of other intermediate products’ and 'Activities of head offices'. 

{{< cta cta_text="Snapshot" cta_link="/reports/sept2021/Sept2021.pdf" cta_new_tab="true" >}}
