# GC Marketing Budget Optimization 
**General Championship 2025 | IIT Kharagpur**

## Overview  
This project was developed as part of the General Championship 2025 at IIT Kharagpur. The objective was to analyze historical sales, media, weather, and NPS (Net Promoter Score) data to identify key revenue drivers, evaluate the impact of marketing campaigns, and optimize media budget allocation across channels.

We combined exploratory data analysis, time-series forecasting, and marketing mix modeling to build a comprehensive decision-support tool for campaign planning and budget efficiency.

---

## Objectives  
- Understand which factors (media, weather, NPS) influence GMV (Gross Merchandise Value) the most.  
- Model lagged effects of marketing efforts using statistical and ML techniques.  
- Forecast future GMV trends across varying scenarios.  
- Recommend optimal media spend reallocations under business constraints.

---

## Dataset Description  
The dataset covered **12+ months** of:
- Sales & GMV (Gross Merchandise Value)
- Media spend across 9 digital and offline channels
- Net Promoter Score (NPS) — customer sentiment indicator
- Weather data (temperature, rainfall, etc.)
- Promotional calendar with holiday and discount markers

---

## Data Analysis Highlights  
- Conducted KPI trend analysis to identify seasonality, product category performance, and campaign effectiveness.  
- Mapped key revenue drivers using correlation, regression, and lag-based impact studies.  
- Discovered that media spend windows overlapping with holidays yielded **43.78% of total GMV**.  
- Identified NPS as a strong leading indicator of revenue uplift when paired with high media exposure.

---

## Modeling & Optimization  
### Bayesian MMM (Marketing Mix Modeling)  
- Implemented Bayesian MMM with **adstock transformation** to model delayed impact of ad channels.  
- Captured channel-specific decay rates and saturation effects.  
- Quantified marginal ROI of each channel and mapped it against actual investment.

### Forecasting  
- Applied time-series models like **Autoformer**, **Prophet**, and **SARIMA**.  
- Achieved **MAPE of ~10%** with SARIMA on GMV predictions.

### Optimization  
- Reallocated media budgets using ROI estimates under fixed spend constraints.  
- Achieved **25.8% improvement** in media efficiency via optimization logic.

---
