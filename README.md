# 🗺 Hai Anh Dang's Python Portfolio

I use Python to examine business questions through forecasting, model evaluation and diagnostic analysis. These projects compare models with simple baselines, check whether inputs are available when a decision is made, and explain where the evidence supports further testing.

## 📚 Table of Contents

- [Python](#python)
- [About & References](#about--references)

## Python

| Project Link | Area of Analysis | Project Description |
| --- | --- | --- |
| 📈 [Victoria Retail Forecasting](https://github.com/Hai-Anh-Dang/victoria-retail-forecasting) | Time-series forecasting, chronological validation, baseline comparison | Can a forecasting model improve monthly Victoria liquor-retailing revenue scenarios beyond repeating last year's same month? The development-selected SARIMA recorded 36.05% higher final MAE than seasonal naive across December 2022 to March 2025. The recommendation keeps the seasonal baseline as the reference for a new forward assessment. |
| ☎️ [Bank Marketing Leakage Review](https://github.com/Hai-Anh-Dang/bank-marketing-leakage) | Classification, feature availability, probability calibration | Can a model identify likely term-deposit subscribers before a call? This controlled logistic-regression comparison removes completed call duration, which is unavailable at that decision point. The corrected model remains unsuitable for call prioritisation under the tested protocol, with weak validation ranking and severe probability underprediction. |
| 🚲 [Seoul Bike Demand Review](https://github.com/Hai-Anh-Dang/seoul-bike-demand-review) | Regression, chronological evaluation, error diagnostics | Does a regression model improve hourly bike-demand estimates beyond a calendar rule? Random Forest reduces held-out RMSE by 21.66%, while still underpredicting by 205.66 bikes/hour on average across 1,937 operating test hours. Observed target-hour weather makes this conditional historical prediction; forecast-input availability and busy-hour errors require further testing. |

Each repository contains an executed notebook, retained results, data provenance and instructions for independent execution and saved-artifact checks. The findings above summarise those published results; they do not represent a new model execution.

---

## About & References

Visit [my GitHub profile](https://github.com/Hai-Anh-Dang) for my introduction and skills, or explore my [SQL and Power BI portfolio](https://github.com/Hai-Anh-Dang/data-powerbi-portfolio).

The layout follows my [Data and Power BI portfolio](https://github.com/Hai-Anh-Dang/data-powerbi-portfolio), which credits Katie Huang's [Portfolio Guide](https://github.com/katiehuangx/Portfolio-Guide) and [GitHub portfolio tutorial](https://github.com/katiehuangx/How-to-Create-a-GitHub-Portfolio/blob/main/README.md). The project descriptions and findings refer to my own portfolio work. The Seoul project adapts a group analysis and credits the original contributors in its repository.

The business contexts are illustrative. Historical model comparisons do not establish deployment readiness, current forecasts or measured commercial impact.

