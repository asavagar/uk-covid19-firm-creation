---
title: Firm creation and productivity during COVID-19
linktitle: Firm creation and productivity
authors:
 - admin
 - Anthony Savagar
toc: true
#type: page
date: "2021-10-14T00:00:00+01:00"
lastmod: "2021-10-15T00:00:00+01:00"
reading_time: true  # Show estimated reading time?
share: true  # Show social sharing links?
profile: true  # Show author profile?
comments: false  # Show comments? 

# Optional header image (relative to `assets/media/` folder).
header:
  caption: "Photo by [Avel Chuklanov](https://unsplash.com/@chuklanov?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/business-creation?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)"
  image: ""
draft: false
menu:
  specialised:

#    parent: Reports 2021
    weight: 1
url_pdf: "reports/specialised/productivity/productivity_GalanakisSavagar2021.pdf"
  

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

We show that during the COVID-19 pandemic, firm start-up growth is largest in high-productivity sectors. For example, the high-productivity pharmaceuticals sector observes a three-fold increase in firm creation relative to pre-pandemic levels.

 

This positive relationship between firm creation and sector productivity adds to evidence of a positive reallocative effect on productivity from the COVID-19 pandemic. This is consistent with {{< cite "AndrewsCharltonMoore2021_OECD" >}} who find job reallocation towards high-productivity sectors during the pandemic, and {{< cite "BloomBunnMizenSmietankaThwaites2020_NBER" >}} who find a positive 'between-firm' effect in a standard productivity decomposition. However, the reallocation channel that we highlight is only one component of aggregate productivity growth. Overall, {{< cite "BloomBunnMizenSmietankaThwaites2020_NBER" >}} show that the pandemic has strong negative effects on productivity in the UK because it decreases the productivity of existing firms. 

 

Our data is helpful to analyse the between-firm or reallocation effect of firm entry on productivity. Empirical research suggests entry and exit is an important determinant of aggregate productivity growth, typically it accounts for greater than 20\% of productivity change and it can rise as high as 70% depending on the context (country, sector and time period). {{< cite "AsturiasHurKehoeRuhl2020_wp" >}} provide a recent survey. The point is that entry and exit are a major channel for productivity growth. We do not have data on firm exit but there is significant theory to explain why firm creation is an important driver of productivity growth. New firms innovate and they create competition for existing incumbents which ensures they remain efficient. Entry leads resources to be reallocated towards new firms. Unfortunately, we cannot analyse the productivity of new firms that are being created which would require real-time data on firm-level productivity. Instead, we can focus on whether firms are being created in sectors that are high or low productivity. This addresses the question of whether booming firm creation during COVID, which is restricted to certain sectors, could cause a distorted allocation of inputs that may have long-run implications. A plausible hypothesis is that the 'artificial' firm creation caused by the COVID pandemic means firms are not necessarily setting-up in productive sectors, instead they are easy-to-setup firms created in COVID-compliant sectors which may not have the usual long-run positive productivity effects. Our evidence is not supportive of this whimsical firm creation.

 

Our analysis compares firm creation by sector to a productivity measure (output per hour) of each sector, as released by [ONS](https://www.ons.gov.uk/economy/economicoutputandproductivity/productivitymeasures/datasets/flashproductivitybysection).



## 2020Q4

Here we focus on the last quarter of 2020. From this analysis, we exclude three industries as productivity or registrations outliers. In terms of productivity, we exclude industries L (Real estate activities) and B (Mining and quarrying). In terms of registrations, we exclude CH (Manufacture of basic metals and metal products). When no outliers are considered, we observe that new firms are registered in lower-productivity industries. For each 2-digit industry, figure 1 plots the total number of registrations 2020Q4 against the sector productivity (output per hour) in 2020Q4.


{{< chart data="2020q4" >}}
<center> <small>
<caption style="text-align:center">Figure 1: Registrations vs. productivity in 2020Q4 </caption> </small> </center>

We also repeated the analysis using pre-COVID measures of productivity in case the static measures of productivity were affected by COVID[^1]. Hence we plotted registrations in 2020Q4 against productivity in 2019Q4. The relationship is very similar.

[^1]: For example, if furloughed workers are not counted as workers and productivity is calculated as output per worker, then labour productivity might increase during the pandemic due to a larger decrease in the numerator than the denominator.


## Ratio of registrations vs. productivity

Taking a longer perspective in firm creation, we plot the ratio of registration (registrations relative to the same week in 2019) against the productivity in the last quarter of 2020. We keep excluding the same outliers as in the previous paragraph. In this exercise we note a positive, but not strong, relationship between the growth in registrations and productivity[^2]. Therefore, even though the majority of new registrations occurs in low-productivity sectors (figure 1), their growth takes place in high-productivity sectors (figure 2).

[^2]: For robustness, we have plotted the ratio of registrations against the ratio of productivity (productivity in the current quarter relative to the equivalent quarter in 2019). The correlation remains positive.

{{< chart data="ratio" >}}
<center> <small>
<caption style="text-align:center">Figure 2: Ratio of registrations vs. productivity in 2020q4 (no outliers) </caption> </small> </center>

## References
<!-- Markdown -->

{{< bibliography cited >}}
