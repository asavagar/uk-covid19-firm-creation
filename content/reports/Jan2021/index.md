---
title: Report January 2021
linktitle: January 2021
toc: true
type: docs
date: "2021-01-08T00:00:00+01:00"
draft: false
menu:
  reports:
    parent: Reports
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

## In a nutshell 
{{< figure src="Jan2021_4x3_adj.png" title="Report January 2021: In a nutshell" >}}


## <i class="far fa-lightbulb"></i>  Highlights
1. Daily business creation increases by 18.5 % between the first and second lockdown.
2. 16.9% more companies incorporations in the second lockdown, relative to the first one.
3. 17,167 additional companies registered in December 2020 than in December 2019.
4. 2,465 new daily registrations since the first Pfizer/BioNTech vaccine.
5. Manufacturing, retail and wholesale sectors outperform in December 2020 relative to 2019 levels. Accommodation and Food services sector’s recovery, occurred after the initial lockdown, worsens as certain areas enter the new Tier-4 scheme.

We analyse Companies House ["basic company data"](http://download.companieshouse.gov.uk/en_output.html) up to the December 31st, 2020 to understand the effect of COVID-19 policies on business creation, and hence, economic activity. We find that daily business creation increases by 18.5% after the first, but before the second, lockdown. 17,167 additional companies registered in December 2020 relative to December 2019. There is more firm creation in every sector, notably in manufacturing, retail, and wholesale sectors. Firm creation continues to increase relative to recent months, but accommodation and food services’ strong performance weakens. 


## Daily Aggregate Company Incorporations
The charts below show the daily company incorporations in the UK for 2020 and their distribution.

{{< chart data="dailyagg" >}}
{{< chart data="density" >}}

The following table summarises the median and the mean of daily new registrations in different periods in 2020. The sharp decline of new incorporations, observed during the first lockdown, recovers. The shock of the initial lockdown anticipates over time. Registrations increase by 18.5% and 16.9% relative to before and during lockdown-I, respectively.
We notice a moderate shock during lockdown-II. The daily median goes from 3057 incorporations during lockdown-II to 2675 incorporations per day after lockdown-II, but before the New Tier-4 Scheme. This is a fall in business creation of 1.9%.
London, South East and East of England move to tier 4 on December 20th, under the [new Tier scheme](https://www.bbc.co.uk/news/uk-55379220). From the 20th December to 31st December, firm creation is significantly higher than over
the same 12 days in 2019 (regardless of the EU-UK Trade deal). Daily median business creation shrinks by 7.5 % and 20.8 % relative to the period during the first and second lockdown, respectively. Most of the business creation occurs on December 30th and 31st and concerns the manufacturing sector. This may be related to Brexit and more specifically to the EU-UK Trade and Cooperation Agreement (TCA).

**Table:** Median and Mean of new daily companies Incorporations in 2020

||<td colspan=3 style="text-align:center;"> Lockdown I</td> <td colspan=2 style="text-align:center;"> Lockdown II</td> <td colspan=1 style="text-align:center;">New Tier-4 Scheme</td> |
|---------|:----------:|:------------:|:----------:|:--------:|:-------------:|:--------:|:-------------------:|:---------------------:|
|         | Total    | Before     | During   | After  | During      | After  | During            | since first vaccine  |
| Median  | 2848.5   | 2581       | 2616     | 3058   | 3057        | 2675   | 2420              | 2563                 |
| Mean    | 2662.076 | 2397.662   | 2582.545 | 2849.6 | 2942.905    | 2572.4 | 2529              | 2465.353             |

*Source: Authors' Calculations*

### Total Effect 

In total, a persistent recovery in business creation has been seen since June. Lockdown-I ended on the 4th of July, when non-essential businesses opened again. Forward that period up until the end of 2020, company registrations exceed their 2019 levels. Over 2020, 2848 daily new companies register. The peak of this ratio is noticed at the end of August (week August 25th). 

Looking at the distribution of registrations, most new registrations occur after the end of lockdown-I. In fact, similar performance is observed between the end of the first and during the second lockdown (July - early December). This may be, mostly, attributed to the less restrictions attached to lockdown-II given the different duration of these two periods. 16.9% more companies incorporations noted during the second lockdown than the first one. 

{{< chart data="total" >}}

## <i class="fas fa-map-marker-alt"></i>  Regional Analysis

The following map[^1] shows the average percentage change of new registrations occurred in December relative to December 2019. Greater changes are showed with bigger bubbles. To see the values, hoover your mouse over each bubble.

{{< chart data="bubbles" >}}

A similar illustration follows in a form of a heatmap to associate areas and their percentage change, as before.
{{< chart data="map" >}}

The following graph aggregates the business creation by country. We separate London from England. In December 2020, firm creation remains higher in all regions than it was in 2019. Following lockdown-I, an uneven recovery is observed among all countries. Since the end of June, Scotland and Wales maintain a positive business creation relative to the same period of 2019. Northern Ireland's recovery commences the same period. It faces, though, several fluctuations until the end of lockdown-II. In London, firm creation escapes the initial lockdown shock quickly and catches up 2019 levels since April. The remaining English regions perform better than the three countries under devolved administration; their recovery occurs faster.

{{< chart data="country" >}}

## <i class="fas fa-industry"></i> Sectoral Change

The following graph illustrates the cumulative company registrations in 2020 by industrial sector relative to 2019 values. For the analysis, we use the 2-digit SIC level and convert it to sectors, following the [ONS classification](https://www.ons.gov.uk/methodology/classificationsandstandards/ukstandardindustrialclassificationofeconomicactivities/uksic2007).

In December 2020, all sectors observe higher firm creation than December 2019. Mining and quarrying, arts, entertainment and recreation sectors present the smallest change relative to their 2019 levels. Manufacturing, wholesale, and retail trade sectors present the greatest increase in firm creation. Accommodation and food services observe a significant drop after the introduction of Tier-4 scheme.

{{< chart data="sector" >}}


## Understanding the EU-UK TCA outliers

There is an outlier of extremely high firm creation on December 30 (and 31), 2020 when the [EU-UK Trade and Cooperation Agreement (TCA)]( https://www.gov.uk/government/publications/agreements-reached-between-the-united-kingdom-of-great-britain-and-northern-ireland-and-the-european-union) was signed.

Treating the excess firm registration of the last week as an outlier, we repeat the sectoral analysis *without* considering the activity of the last two days of December. The only noticeable difference regards the administrative and support services whose firm creation on average come behind the arts, entertainment, and recreation sector. Looking only at the outliers, manufacturing, administrative and supportive services related businesses seem to register more than the same days in 2019. This static improve might be related to Brexit and the EU-UK TCA.

In terms of the regional analysis, an over-activity is observed in London, England, and Wales.


[^1]: Daily maps with all the new established firms, by full postcode, are available upon request in .gif format.
