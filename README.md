# COVID-19 Machine Learning Analysis

## Overview
This project explores machine learning techniques applied to UK COVID-19 data, analysing the relationship between hospital admissions, deaths, vaccinations, and mechanical ventilation bed usage.

### Objectives
- Analyse COVID-19 admission and death trends across the UK
- Understand the impact of the vaccination rollout on hospitalisation rates
- Apply data mining techniques to uncover patterns in the data
- Build forecasting models to predict future admissions and MV bed usage

## Technologies
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Prophet
- mlxtend
- Jupyter Notebook

## Dataset
UK COVID-19 data provided by Dr. Harry Yu, covering:
- Daily new hospital admissions
- Daily deaths within 28 days
- Daily vaccinations (first and second dose)
- COVID-occupied mechanical ventilation beds

## Project Structure
```
data/                   raw CSV datasets
outputs/                generated forecasts and model outputs
DataAlgorithm.ipynb     main analysis notebook
```

## Installation
```bash
git clone https://github.com/AstralSkies/FoundationsofAI.git
cd FoundationsofAI
pip install pandas numpy scikit-learn matplotlib seaborn prophet mlxtend jupyter
```
