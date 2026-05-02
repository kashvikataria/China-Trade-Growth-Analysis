# China-Trade-Growth-Analysis
OLS regression analysis of trade openness, FDI, and GDP growth in China (2000–2024) using World Bank data
# Trade Openness & Economic Growth - China (2000–2024)

**Method:** OLS Multiple Linear Regression  
**Data Source:** World Bank Open Data  
**Period:** 2000–2024 (25 annual observations)

## Overview
This project investigates the relationship between trade openness, foreign direct 
investment (FDI), and GDP growth in China over a 25-year period. Using OLS regression, 
the study quantifies how external economic integration has driven and is now 
constraining China's growth trajectory.

## Model
GDP Growth = −0.7338 + 0.1501(Trade % GDP) + 1.0302(FDI % GDP) − 0.2448(Inflation)

## Key Results
| Metric | Value |
|---|---|
| R² | 0.806 |
| Adjusted R² | 0.779 |
| F-Statistic | 29.16 (p < 0.0001) |
| Trade Openness (β) | 0.1501 (p < 0.01) |
| FDI (β) | 1.0302 (p < 0.01) |

## Key Findings
- Trade openness and FDI are statistically significant determinants of China's GDP growth
- Model explains 80.6% of variance in annual GDP growth
- Post-2007 growth deceleration aligns with declining trade intensity following the GFC
- COVID-19 (2020) produced the largest residual (−3.18), reflecting exogenous shock limitations of linear models
- China's FDI inflows have collapsed from 4.49% of GDP (2005) to 0.10% (2024); a structural headwind to future growth

## Files
- `China_Trade_Growth_Analysis.pdf` — Full report including methodology, regression output, and policy implications

## Tools Used
- Microsoft Excel (OLS Regression, Data Analysis ToolPak)
- World Bank Open Data
