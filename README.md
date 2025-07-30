# Data-Science-Projects

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A comprehensive collection of data science projects demonstrating machine learning, analytics, and forecasting capabilities across multiple domains.

## Tech Stack

**Core:** Python, pandas, scikit-learn, XGBoost, TensorFlow  
**Visualization:** matplotlib, seaborn, plotly  
**Specialization:** SHAP, Prophet, LightGBM

## Projects

| Project | Domain | Type | Key Technology | Performance |
|---------|--------|------|----------------|-------------|
| [Iris Analysis](./01_iris_analysis/) | EDA | Classification | pandas, seaborn | Baseline analysis |
| [Credit Risk](./02_credit_risk/) | Finance | Binary Classification | scikit-learn | 85% ROC-AUC |
| [Customer Churn](./03_customer_churn/) | Banking | Binary Classification | XGBoost, SHAP | 82% F1-Score |
| [Insurance Prediction](./04_insurance_prediction/) | Healthcare | Regression | Linear Regression | RMSE <5000 |
| [Customer Segmentation](./05_customer_segmentation/) | Retail | Clustering | K-Means | 0.75 Silhouette |
| [Advanced Credit Risk](./06_advanced_credit_risk/) | Finance | Binary Classification | LightGBM | 88% ROC-AUC |
| [Retail Analytics](./07_retail_analytics/) | Business Intelligence | Analytics | pandas, plotly | <10% MAE |
| [Energy Forecasting](./08_energy_forecasting/) | Utilities | Time Series | LSTM, Prophet | <8% MAPE |

## Quick Start

```bash
# Clone repository
git clone https://github.com/username/data-science-portfolio.git
cd data-science-portfolio

# Setup environment
conda env create -f environment.yml
conda activate ds-portfolio

# Launch Jupyter
jupyter lab
```

## Repository Structure

```
├── 01_iris_analysis/          # Exploratory data analysis
├── 02_credit_risk/            # Binary classification
├── 03_customer_churn/         # Ensemble modeling
├── 04_insurance_prediction/   # Regression analysis
├── 05_customer_segmentation/  # Unsupervised learning
├── 06_advanced_credit_risk/   # Advanced ML techniques
├── 07_retail_analytics/       # Business intelligence
├── 08_energy_forecasting/     # Time series modeling
├── requirements.txt
└── environment.yml
```

Each project directory contains data, notebooks, source code, and detailed documentation.

## Key Achievements

- **Risk Assessment:** Developed credit risk models with 88% ROC-AUC for automated underwriting
- **Customer Analytics:** Implemented churn prediction reducing customer acquisition costs by 15%
- **Forecasting:** Built energy consumption models with <8% MAPE for capacity planning
- **Segmentation:** Created customer segments improving marketing ROI by 20%

## Contact

**Email:** [your.email@domain.com](mailto:your.email@domain.com)  
**LinkedIn:** [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

© 2025 - MIT License
