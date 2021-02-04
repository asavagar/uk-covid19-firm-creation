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

## Data
The data are constructed from the UK business register, available from [Companies House]( https://www.gov.uk/government/organisations/companies-house) ([data]( http://download.companieshouse.gov.uk/en_output.html) here in .csv format). The register records every company in the UK with its birth date, post code and industry. This makes it possible to measure daily company registrations.

### Advantages and Disadvantages

The main advantage of the data is that it is timely (almost real-time nature) and covers the entire UK. A disadvantage is that it is not possible to identify companies that will employ and produce compared to those that are set up for accountancy purposes.

We **exclude** firms with missing values on the incorporation date, post code and/or industry of main activity.

## Distribution of Aggregate Company Registrations
The chart below shows the density of daily company registrations in the UK for 2020.

{{< chart data="density" >}}


## Understanding the outliers
There is an outlier of extremely high firm creation on December 30 (and 31), 2020 when the [EU-UK Trade and Cooperation Agreement (TCA)]( https://www.gov.uk/government/publications/agreements-reached-between-the-united-kingdom-of-great-britain-and-northern-ireland-and-the-european-union) was signed.

Treating the excess firm registration of the last week as an outlier, we repeat the sectoral analysis, found [here](https://uk-firm-dynamics.netlify.app/reports/jan2021/), *without* considering the activity of the last two days of December. The only noticeable difference regards the administrative and support services whose firm creation on average come behind the arts, entertainment, and recreation sector. 

Looking only at the outliers, manufacturing, administrative and supportive services related businesses seem to register more than the same days in 2019. This static improve might be related to Brexit and the EU-UK TCA.

In terms of the regional analysis, an over-activity is observed in London, England, and Wales.

