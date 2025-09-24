# Predictive Modelling of Eating-Out Problem

## Overview
This project explores restaurant data from Sydney (2018) to predict restaurant ratings and classify restaurant quality.  
The notebook implements the **full data science workflow**:

- **Part A – Exploratory Data Analysis (EDA):** data cleaning, summary statistics, visualisation, geospatial analysis with `geopandas`, and interactive plots using Plotly.  
- **Part B – Predictive Modelling:** regression (linear regression + gradient descent implementation), classification (logistic regression + tree-based models), and model evaluation.  
- **Part C – Reproducibility & Workflow:** setup using **Git, Git LFS, and DVC** to ensure all results are reproducible.  
- **PySpark Integration:** one regression and one classification task are re-implemented with **PySpark MLlib** pipelines for scalability comparison.

---

## Dataset
- **CSV:** `zomato_df_final_data.csv` – 10,000+ restaurant records (address, cost, cuisine, ratings, type, suburb, etc.).  
- **GeoJSON:** `sydney.geojson` – boundaries for geospatial analysis.  

Both files are tracked with **Git LFS**.

---

## Installation
Clone the repo and install dependencies:

## Main requirements
pandas, numpy, scikit-learn, matplotlib, seaborn,
plotly, geopandas, shapely, folium, pyspark, dvc

```bash
git clone https://github.com/<your-username>/predictive-modelling-reproducibility.git
cd predictive-modelling-reproducibility

# recommended: conda environment
conda create -n pm python=3.11 -y
conda activate pm

pip install -r requirements.txt



