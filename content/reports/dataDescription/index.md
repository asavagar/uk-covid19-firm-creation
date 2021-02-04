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

## <i class="fas fa-database  "></i>   <span class="ml-1">Data</span>
The data are constructed from the UK business register, available from [Companies House]( https://www.gov.uk/government/organisations/companies-house) ([data]( http://download.companieshouse.gov.uk/en_output.html) here in .csv format). The register records every company in the UK with its birth date, post code and industry. This makes it possible to measure daily company registrations.

### Advantages and Disadvantages

The main advantage of the data is that it is timely (almost real-time nature) and covers the entire UK. A disadvantage is that it is not possible to identify companies that will employ and produce compared to those that are set up for accountancy purposes.

We **exclude** firms with missing values on the incorporation date, post code and/or industry of main activity.

## Distribution of Aggregate Company Registrations
The chart below shows the density of daily company registrations in the UK for 2020.

{{< chart data="density" >}}


