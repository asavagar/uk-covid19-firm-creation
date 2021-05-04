---
title: Report May 2021
linktitle: May 2021
toc: true
type: docs
date: "2021-05-01T00:00:00+01:00"
draft: false
menu:
  reports:
#    parent: Reports 2021
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---


We analyse Companies House ["basic company data"](http://download.companieshouse.gov.uk/en_output.html) up to the April 30th, 2021. We note a similar strength of new company registration. Lockdown-III period has not altered the business setup observed the last 2 months. 

## <i class="far fa-lightbulb"></i>  <span class="ml-1">Highlights</span>
1. Business creation decreased 14.64% between March 2021 and April 2021.
2. Business creation increased 66.45% between April 2020 and April 2021.
3. The largest number of company registrations occurs in Wholesale and retail trade; repair of motor vehicles and motorcycles’ sector. 


## <i class="fas fa-bullseye"></i> <span class="ml-1">Aggregate Analysis</span>
### Daily 
The chart below shows the daily company incorporations in the UK since January 2020. The lockdown periods correspond to our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline). [Lockdown-III eases further]( https://www.bbc.co.uk/news/uk-56641596) on April 12, 2021 (pubs, restaurants, hairdressers, gyms and non-essential shops can reopen). For our analysis, we treat April 12th as the end of lockdown-III.

{{< chart data="dailyagg" >}}
<small>Download histogram data as: <a href="data/01histogram.csv" download="01histogram.csv"><i class="fas fa-file-csv"></i></a>
  <br>
Download statistics as: <a href="data/02statsLockdown.xlsx" download="02statistics.xlsx"><i class="fas fa-file-excel"></i></a></small>

- Business creation decreased 14.64% between March and April 2021. 
- 22,919 additional companies were registered in April 2021 relative to April 2019. 
- The median daily registrations were 52.57% higher in April 2021 than April 2019.
- The median daily registrations during lockdown-III is 32.6% higher than in lockdown-I, and 1.53% higher than in lockdown-II.  

The chart below shows the rolling average of firm creation since January 2019. Shaded areas correspond to lockdown periods as shown our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline).

{{< chart data="rollAv" >}}


### Relative  

Company registrations persistently exceed their 2019 and 2020 levels. Week 12 in 2020 marks the beginning of the first national lockdown. The ratio between 2021/2020 dominates the one between 2021/2019 among the weeks 13-15. We note that a national lockdown holds in weeks 13-15 in both 2020 and 2021. This may suggest an adjustment of business activity during lockdown-III than lockdown-I.   

{{< chart data="total" >}}
<small>Download data as: <a href="data/04ratio.csv" download="03ratio.csv"><i class="fas fa-file-csv"></i></a></small>

### April 
Daily average company registrations in April 2021 are 66.45% higher than April 2020 and 51.1% higher than April 2019.

{{< chart data="april" >}}
<small>Download data as: <a href="data/03statsApr.csv" download="04march.csv"><i class="fas fa-file-csv"></i></a></small>

## <i class="fas fa-map-marker-alt"></i>  <span class="ml-1">Regional Analysis</span>

### Postcode Area
The map shows the percentage change in new registrations in April 2021 compared to April 2019.  

<iframe src="mapApr2021Av.html" style="height:600px;width:100%;border:none;overflow:hidden;"></iframe>

### Country 
The following graph aggregates business creation by country. In April 2021, firm creation remains higher in most of the regions than it was in 2019. On average, England (excl. London), for the first time in 2021, experiences the fewest new daily registrations. London, followed by Wales, dominate business registrations.  

{{< chart data="country" >}}
<small>Download data as: <a href="data/05country.csv" download="05country.csv"><i class="fas fa-file-csv"></i></a></small>

### London
Within London, most of the business creation in April 2021 comes from Central and East London.

{{< chart data="london" >}}
<small>Download data as: <a href="data/06London.csv" download="06london.csv"><i class="fas fa-file-csv"></i></a></small>


## <i class="fas fa-industry"></i> <span class="ml-1">Sectoral Analysis</span>
### SIC Sections
The graph illustrates company registrations in April 2021 relative to 2019 by industrial sector. It compares the percentage change in 2021 relative to 2019 for each week of the year. We use 4-digit SIC levels (ONS "Classes") and group them into broader sectors (ONS "Sections"). We use the [ONS classification](https://onsdigital.github.io/dp-classification-tools/standard-industrial-classification/ONS_SIC_hierarchy_view.html). We show a selection of sectors that present notable changes. 

{{< chart data="sectors" >}}
<small>Download data as: <a href="data/07sections.csv" download="07sections.csv"><i class="fas fa-file-csv"></i></a></small>

- April 2021 retains higher firm creation in most sectors than April 2019.
- 'Wholesale, and Retail Trade', 'Manufacturing', ‘Activities of households as employers; undifferentiated goods-and services-producing activities’, and ‘Financial and insurance activities’ sectors show the greatest increase in firm creation in April 2021. 
- Compared to April 2019, in April 2021 there is more than a 200% increase in business creation for ‘Retail trade not in stores, stalls or markets’, ‘Retail sale of food, beverages and tobacco in specialised stores’, ‘Agents involved in the sale of furniture, household goods, hardware and ironmongery’, and ‘Retail sale of sporting equipment in specialised stores’. 
- There are lower registrations relative to March 2019 in Service activities incidental to land transportation’, ‘Manufacture of metal structures and parts of structures’, ‘Combined facilities support activities’ and ‘Washing and (dry-)cleaning of textile and fur products’. 


