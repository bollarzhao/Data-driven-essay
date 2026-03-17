# 📊 Housing Affordability Analysis in Canadian Cities (2016–2021)
## 🚀 Project Overview

This project analyzes housing affordability among young adults (ages 25–34) across major Canadian cities using 2016 and 2021 Census microdata.

The goal is to evaluate whether Toronto is uniquely unaffordable or part of a broader national trend, and to identify the underlying drivers of housing pressure using data-driven evidence.

## 🎯 Key Business Question

Is housing affordability pressure concentrated in Toronto, or is it a systemic issue across Canadian metropolitan areas?

Housing pressure is defined as individuals spending more than 30% of their income on housing, a widely used affordability benchmark.

## 📈 Key Insights

Housing pressure is widespread across Canadian cities, not limited to Toronto

Most cities experienced an increase in housing burden from 2016 to 2021

In many regions, housing costs grew faster than income, driving affordability issues

Even where income growth kept pace, high baseline costs still led to sustained pressure

Individuals without a bachelor’s degree are consistently more vulnerable to housing stress

## 🧠 Analytical Approach
### Data

Canadian Census Microdata (2016 & 2021)

Population: Young adults aged 25–34

Geographic scope: Major Census Metropolitan Areas (CMAs)

### Feature Engineering

Housing burden ratio = annual housing cost / annual income

Binary affordability indicator (>30% threshold)

Education grouping (Bachelor’s vs Non-Bachelor’s)

City-level aggregation with survey weights

### Methods

Cross-sectional comparison across cities

Time-series comparison (2016 → 2021)

Distribution analysis (within-city inequality)

Growth comparison (income vs housing costs)

## 📊 Visualization & Communication

This project emphasizes data storytelling, using multiple complementary visualizations:

Choropleth maps → geographic patterns of housing pressure

Scatter plots → relationship between income growth and housing cost growth

Density plots → distribution of housing burden within cities

Interactive dashboard → allows users to explore city-level differences

The focus is not just on analysis, but on making insights interpretable and actionable.

## 🛠️ Tech Stack

R (tidyverse, ggplot2) — data cleaning and analysis

Data visualization tools — for storytelling and interaction

Census microdata processing — handling weighted survey data

## ⚠️ Limitations

Based on two time points (2016 & 2021) → limited temporal resolution

Uses city-level aggregates, which may mask neighborhood-level variation

Results depend on self-reported census data
