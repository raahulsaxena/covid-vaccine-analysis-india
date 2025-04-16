# COVID-19 Vaccination Coverage Analysis in India 🇮🇳💉

This project explores district-level vaccination trends in India using data from the CoWIN portal and Ministry of Health. It identifies geographic and demographic disparities in vaccine coverage and visualizes insights using clustering and geospatial mapping.

## 🔍 Overview
- Public data sources: CoWIN API (archived), MoHFW updates, IndiaStat
- District-level analysis of 600K+ records
- Focus on disparities by age, gender, and location
- Clustering of low-coverage regions for targeted outreach
- Interactive maps using Plotly and GeoPandas

## 📊 Techniques Used
- Pandas & NumPy for data wrangling
- K-means clustering for region grouping
- Matplotlib & Plotly for data viz
- GeoPandas & shapefiles for choropleths
- Seaborn for statistical distribution plots

## 📌 Sample Insight
> Maharashtra’s tribal districts showed <30% first-dose coverage in July 2021, despite statewide averages above 50%. Clustering analysis grouped these with similar rural, underserved regions across Jharkhand and Chhattisgarh.

## 📂 Repo Structure
```
notebooks/        → Jupyter Notebooks for EDA, clustering, viz  
data/             → Raw + processed data files  
src/              → Utility scripts  
outputs/          → Generated maps and insights  
```

## 📦 Setup
```bash
git clone https://github.com/raahulsaxena/covid-vaccine-analysis-india.git
cd covid-vaccine-analysis-india
pip install -r requirements.txt
```


**Author**: Rahul Saxena  
[LinkedIn](https://linkedin.com/in/raahulsaxena) | [Portfolio](http://raahulsaxena.github.io)
