---
title: Variety in firm creation
linktitle: Variety in firm creation
author:
 - Mason Veilleux
toc: true
type: book
date: "2021-10-12T00:00:00+01:00"
draft: false
menu:
  specialised:

#    parent: Reports 2021
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---
The relationship between firm creation and the variety of firms is an essential element of economic growth. New firms hire skilled workers and adopt new technologies to boost productivity, and hence, output. Variety, highlighted by recent literature, signals important information such as the cost of shipping, materials, and labour that firms take into account prior to their entering into a market. As such, variety acts as a channel for firm creation that promotes economic growth. In this report, we define variety as unique SIC codes in a district. We use a new data set compiled from Companies House basic data. It includes all incorporations in the UK across industries and postcodes from 2012. I find that (1) firm creation concentrates in places with higher variety and (2) districts with higher levels of GDP tend to have higher levels of variety and new firms.

## Defining Variety 
Variety counts the number of unique industry codes in a given district and year. Here we follow the ONS Standard Industrial Classification ([SIC](https://onsdigital.github.io/dp-classification-tools/standard-industrial-classification/ONS_SIC_hierarchy_view.html)) classification of industry codes. Alternatively, we can express variety as: 
$$ \\sum\_{i=1}^n \\text{SIC}\_{i,r,t}\\ \\forall\\ \\ i,j \\ \\in {1110,..., 99000}\\ \\nexists\\ {j\\neq i\\ and\\ \\text{SIC}\_i=\\ \\text{SIC}\_j} $$ 

For example, consider a district which experiences 1000 incorporations in year $t$. This cohort can be evenly divided into four groups. Each counts 250 incorporations. Quarter 1 is entirely composed of licensed restaurants (SIC code 56.10/1 in Section I); Quarter 2 is composed of companies that plaster buildings (SIC code 43.31 in Section F); Quarter 3 is composed of companies that offer life insurance (SIC code 65.11 in Section K). Quarter 4 is comprised of 4- or 5- digit coded industries that are distinct from each other and the previously mentioned industries. As such, we have 1000 companies in an area with 253 distinct industries ( 1+1+1+250= 253). Figure 1 illustrates this example. There are currently 730 unique SIC codes at the 4/5 digit level in our data. 

{{< chart data="fig1" >}}

## Context 
Figure 2 illustrates the relationship between new firms, variety, and output. Variety is on the y-axis and number of new firms (incorporations) on the x-axis. The size of the bubbles depends upon the real GDP given by [ONS](https://www.ons.gov.uk/economy/grossdomesticproductgdp/datasets/regionalgrossdomesticproductlocalauthorities) data. Figure @ref(fig:timelapse) shows this relationship dynamically between 2012 and 2019. 

{{< chart data="fig2" >}}

### Firm creation concentrates in places with higher variety 
An increase in incorporations (or an additional incorporation) results in an increase of variety at a decreasing rate. This finding suggests that when potential companies are looking to open a shop, they will likely open in a place that has higher variety. Firms may concentrate in high-variety areas for several reasons. For example, transportation costs for inputs are reduced when firms are closer in proximity to one another; new firm linkages with established firms in the same section create incentive for specialization (i.e. A plastering specialists in the Construction section); or the skilled labour in the area produce spillover effects that boost firm-specific productivity. In other words, variety acts as the environment that breeds new firms into existence. Some of these new firms may even enter in industries that create higher levels of variety. 

### Districts with higher levels of output tend to have higher levels of variety and new firms 
The ability of larger districts to sustain high levels of variety and new firms suggests a heightened degree of dynamism. When new firms enter the market, they tend to bring in the latest technological advancements, pay higher wages and hire unemployed workers. As a result, they increase the level of employment, physical capital, and technological progress, all essential elements for economic growth. This dynamism implies that the area’s average productivity increases along with output. 

## Conclusion and Implications 
A higher geographic concentration in new firms occurs in places that have both higher variety and output. Since variety is a central element of growth, the interest does not lie only on the number of firms, but also on their variety. 

## Data 
Regional Gross Domestic Product: Local Authorities.1998-2019. [ONS](https://www.ons.gov.uk/economy/grossdomesticproductgdp/datasets/regionalgrossdomesticproductlocalauthorities). 
