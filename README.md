# housing-rent-prediction Project

## Overview
This repository contains a Jupyter Notebook developed in an Anaconda environment to analyze and predict housing rents in German cities such as Berlin, Munich, and Frankfurt.  
The project compares **Linear Regression**, **Random Forest**, and **XGBoost** models, and integrates socio‑economic indicators to provide insights into housing market dynamics.  

The aim is to forecast rental price trends at a **district/neighborhood level**, considering factors such as:
- Urban development plans
- Population growth
- Transportation infrastructure changes
- Broader economic indicators

---

##  Contents
- `rent_prediction.ipynb` → Main notebook with preprocessing, model training, evaluation, and results   
- `README.md` → Project documentation  

---

##  Setup
To run the notebook locally:

Clone the repository:
   bash
   git clone https://github.com/Anucs1304/housing-rent-prediction.git
   cd housing-rent-prediction 

## Results
- inear Regression - RMSE ≈ 1090.13, R² ≈ -3.36
- Random Forest - RMSE ≈ 188.57, R² ≈ 0.87
- XGBoost - RMSE ≈ 171.0, R² ≈ 0.89

## Future Work
- Advanced hyperparameter tuning (Bayesian optimization, automated frameworks)
- SHAP analysis for deeper interpretability
- Enrich dataset with external features (transport, schools, crime rates)
- Deployment as a web app/dashboard
- Benchmarking against LightGBM and CatBoost
- Temporal analysis of rent trends

## License
- This project is released under the MIT License.

## Acknowledgements
- pandas, matplotlib, scikit-learn, seaborn
- XGBoost library
- Dataset sourced from housing rental listings
