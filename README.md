# 📊 Housing Affordability Analysis in Canadian Cities (2016–2021)
## 🚀 Project Overview

This project analyzes housing affordability among young adults (ages 25–34) across major Canadian Census Metropolitan Areas (CMAs) using 2016 and 2021 Census microdata.

Rather than focusing on individual cities alone, the analysis examines metropolitan-level housing systems, which better reflect labor markets, commuting patterns, and regional housing dynamics.

## 🎯 Key Business Question

Is housing pressure concentrated in Toronto, or is it a broader issue across Canadian metropolitan areas?

Housing pressure is defined as spending more than 30% of income on housing, a standard affordability threshold.

## 📈 Key Insights

- Housing pressure is not unique to Toronto — many CMAs show similarly high levels

- Most CMAs experienced increasing housing burden from 2016 to 2021

- In many metropolitan areas, housing costs outpaced income growth, worsening affordability

 - Even where income growth kept up, existing high cost levels sustained pressure

- Individuals without a bachelor’s degree are more likely to experience housing stress across CMAs

## 🧠 Analytical Approach
### Data
Canadian Census Microdata (2016 & 2021)

**Population**: Young adults aged 25–34

**Geographic** **unit**: Census Metropolitan Areas (CMAs)

### Feature Engineering
**Housing burden ratio** = annual shelter cost / annual income

**Binary indicator**: burden > 30%

**Education grouping**: bachelor’s vs non-bachelor’s

**Weighted aggregation** using survey weights

### Methods

Cross-sectional comparison across cities

Time-series comparison (2016 → 2021)

Distribution analysis (within-city inequality)

Growth comparison (income vs housing costs)

## 📊 Visualization & Communication

This project emphasizes data storytelling, using multiple complementary visualizations:

**Choropleth maps → geographic patterns of housing pressure

Scatter plots → relationship between income growth and housing cost growth

Density plots → distribution of housing burden within cities

Interactive dashboard(html file) → allows users to explore city-level differences

The focus is not just on analysis, but on making insights interpretable and actionable.**

## 🛠️ Tech Stack

R (tidyverse, ggplot2) — data cleaning and analysis

Data visualization tools — for storytelling and interaction

Census microdata processing — handling weighted survey data

## 📌 Key Takeaway

Housing affordability is a systemic issue across Canadian metropolitan areas, not just a Toronto-specific problem.
The imbalance between income and housing costs is driving widespread housing pressure among young adults.

## ⚠️ Limitations

ONLY Based on two time points (2016 & 2021) → limited temporal resolution

Uses city-level aggregates, which may mask neighborhood-level variation

Results depend on self-reported census data
