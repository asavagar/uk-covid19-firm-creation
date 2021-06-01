---
title: Report June 2021
linktitle: June 2021
toc: true
type: docs
date: "2021-06-01T00:00:00+01:00"
draft: false
menu:
  reports:
#    parent: Reports 2021
    weight: 7

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 7
---

## In a nutshell



We analyse Companies House ["basic company data"](http://download.companieshouse.gov.uk/en_output.html) up to the May 31st, 2021. We note a similar strength of new company registration. Lockdown-III period has not altered the business setup observed the last few months. 

## <i class="far fa-lightbulb"></i>  <span class="ml-1">Highlights</span>
1. Business creation decreased 5.8% between April 2021 and May 2021.
2. Business creation was 13.5% higher in May 2021 than in May 2020.
3. The largest number of company registrations occurs in 'Wholesale and retail trade; repair of motor vehicles and motorcycles' sector, followed by 'Agriculture, forestry and fishing'. 


## <i class="fas fa-bullseye"></i> <span class="ml-1">Aggregate Analysis</span>
### Daily 
The chart below shows the daily company incorporations in the UK since January 2020. The lockdown periods correspond to our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline). [Lockdown-III eases further]( https://www.bbc.co.uk/news/uk-56641596) on April 12, 2021 (pubs, restaurants, hairdressers, gyms and non-essential shops can reopen). On May 17, 2021 indoors hospitality is allowed. For our analysis, we treat April 12th as the end of lockdown-III. 

{{< chart data="dailyagg" >}}
<small>Download histogram data as: <a href="data/01histogram.csv" download="01histogram.csv"><i class="fas fa-file-csv"></i></a>
  <br>
Download statistics as: <a href="data/02statsLockdown.xlsx" download="02statistics.xlsx"><i class="fas fa-file-excel"></i></a></small>

- Business creation decreased 5.8% between April and May 2021. 
- 7,996 additional companies were registered in May 2021 relative to May 2019. 
- The median daily registrations were 30% higher in May 2021 than May 2019. 

The chart below shows the rolling average of firm creation since January 2019. Shaded areas correspond to lockdown periods as shown our key dates [timeline](https://uk-firm-dynamics.netlify.app/reports/#timeline).

{{< chart data="rollAv" >}}


### Relative  

Company registrations persistently exceed their 2019 and 2020 levels. This effect is strong regardless the third national lockdown.   

{{< chart data="total" >}}
<small>Download data as: <a href="data/04ratio.csv" download="03ratio.csv"><i class="fas fa-file-csv"></i></a></small>

### May
Daily average company registrations in May 2021 are 13.5% higher than May2020 and 41% higher than May 2019.

{{< chart data="april" >}}
<small>Download data as: <a href="data/03statsApr.csv" download="04march.csv"><i class="fas fa-file-csv"></i></a></small>

## <i class="fas fa-map-marker-alt"></i>  <span class="ml-1">Regional Analysis</span>

### Postcode Area
The map shows the percentage change in new registrations in May 2021 compared to May 2019.  

<iframe src="mapMay2021Av.html" style="height:600px;width:100%;border:none;overflow:hidden;"></iframe>

### Country 
The following graph aggregates business creation by country. London, followed by England, dominate business registrations. For the first time in 2021, Scotland presents increasing business incorporations.  

{{< chart data="country" >}}
<small>Download data as: <a href="data/05country.csv" download="05country.csv"><i class="fas fa-file-csv"></i></a></small>

### London
Within London, most of the business creation in May 2021 comes from Central, East and North London. 

{{< chart data="london" >}}
<small>Download data as: <a href="data/06London.csv" download="06london.csv"><i class="fas fa-file-csv"></i></a></small>


## <i class="fas fa-industry"></i> <span class="ml-1">Sectoral Analysis</span>
### SIC Sections
The graph illustrates company registrations in May 2021 relative to 2019 by industrial sector. It compares the percentage change in 2021 relative to 2019 for each week of the year. We use 4-digit SIC levels (ONS "Classes") and group them into broader sectors (ONS "Sections"). We use the [ONS classification](https://onsdigital.github.io/dp-classification-tools/standard-industrial-classification/ONS_SIC_hierarchy_view.html). We show a selection of sectors that present notable changes. 

{{< chart data="sectors" >}}
<small>Download data as: <a href="data/07sections.csv" download="07sections.csv"><i class="fas fa-file-csv"></i></a></small>

- May 2021 retains higher firm creation in most sectors than May 2019.
- 'Wholesale, and Retail Trade', 'Manufacturing', ‘Financial and insurance activities’ and 'Real estate activities' sectors show the greatest increase in firm creation in May 2021. 
- Compared to May 2019, in May 2021 there is more than a 300% increase in business creation for ‘Combined office administrative service activities’, ‘Retail sale via mail order houses or via Internet’ and ‘Raising of other animals’. 
- There are lower registrations relative to May 2019 in 'Warehousing and storage’, ‘Activities of head offices’, ‘Service activities incidental to land transportation’ and ‘Legal activities’. 


{{< cta cta_text="Snapshot" cta_link="/reports/may2021/June2021.pdf" cta_new_tab="true" >}}
