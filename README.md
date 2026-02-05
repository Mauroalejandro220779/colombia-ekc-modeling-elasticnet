# Modeling the Environmental Kuznets Curve (EKC) & Emission Projections for Colombia
### A Data Science Framework for NDC 3.0 & PNCTE Assessment

This repository contains the end-to-end research, code, and econometric methodology for my Master’s Thesis (2026) and National Deparment of Planning of Colombia DNP. The project focuses on the empirical validation of the **Environmental Kuznets Curve (EKC)** for Colombia and the projection of Greenhouse Gas (GHG) emission pathways to support national climate policy.

## 🚀 Key Technical Features

### 1. Model Benchmarking & Selection
- **Parametric vs. Non-Parametric Comparison:** Evaluated traditional parametric OLS (Quadratic and Cubic EKC specifications) against non-parametric trends to ensure the model captured the true decoupling of emissions without structural bias.
- **Elastic Net Regularization:** Implemented an Elastic Net framework (L1 and L2 penalties) to handle the high multicollinearity inherent in macroeconomic time-series data (GDP, Energy Intensity, Trade Openness).

### 2. Robust Validation
- **Time-Series Cross-Validation:** Utilized a rolling-window validation strategy to ensure the model's predictive stability across different Colombian economic cycles.
- **Diagnostic Testing:** Rigorous assessment of residuals, heteroskedasticity, and autocorrelation to ensure statistical integrity for policy-making.

## 📊 Research Impact & Policy Alignment

### Macroeconometric Projections to 2035
The framework functions as a decision-support tool to monitor Colombia's progress against its **Nationally Determined Contributions (NDC)** for 2030 and 2035.

- **Official Data Integration:** Projections are driven by official economic growth rates calculated by the **DADS-DNP** (Dirección de Ambiente y Desarollo Sostenible - Environmental Unit for Sustainable Development).
- **Absolute Emission Quantification:** The model translates sectoral **per-capita $CO_2e$** projections into absolute **$MtCO_2e$** values by integrating national population dynamics.
- **PNCTE/ETS Assessment:** Provides a quantitative baseline to evaluate how the implementation of the **Colombian Emission Trading System (PNCTE)** can close the mitigation gap through three strategic scenarios:
  1. **Conservative:** Low economic growth / high carbon intensity.
  2. **Trend (Moderate):** Alignment with historical decarbonization patterns.
  3. **Optimistic:** High growth coupled with aggressive climate transition targets.



## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Scikit-learn (ElasticNet), Pandas, Statsmodels, Scipy, Matplotlib/Seaborn.
- **Framework:** Reproducible Data Science (Jupyter/Colab).

## 📂 Project Structure
- `Notebooks/`: Full preprocessing and modeling pipeline (Elastic Net implementation).
- `Data/`: Metadata and source descriptions (World Bank, DNP).
- `Thesis/`: Final TFM Research Report (PDF).

---
*Developed by Mauro A. Reyes Bonilla - Master in Data Science & Business Analytics.*
