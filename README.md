# 📊 Zomato Bangalore Restaurants - Exploratory Data Analysis

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harshith-Reddy11/EDA-on-Zomato-Dataset/blob/eda-notebook/EDA_on_Zomato_Dataset.ipynb)
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)

This repository contains a detailed exploratory data analysis (EDA) of the Zomato Bangalore restaurant dataset.  
The goal is to uncover trends, patterns, and actionable insights about restaurant types, locations, cuisine preferences, and cost distributions in Bangalore.

---

## ✅ Project Overview
- **Dataset:** Zomato Bangalore Restaurants (from Kaggle)
- **Objective:** Clean, explore, and analyze data to understand the city's restaurant landscape
- **Tech stack:** Python, Pandas, NumPy, Seaborn, Matplotlib

---

## 📦 Contents
- `EDA_on_Zomato_Dataset.ipynb` → Main notebook with all data cleaning, preprocessing, and visualizations
- `Zomato_EDA_Analysis_Report.pdf` → Professional data analysis report summarizing key findings
- `requirements.txt` → List of Python packages to reproduce the analysis

---

## 🧹 Data Cleaning & Preprocessing
- Dropped irrelevant columns (`url`, `phone`, `address`, etc.)
- Handled missing values in the `rate` column by cleaning text and filling with the mean
- Removed duplicates to improve data quality
- Standardized cost columns by converting to float
- Grouped less frequent categories (cuisines, restaurant types, locations) under `'others'`

---

## 📊 Key Insights
- Quick Bites and Casual Dining are the dominant restaurant types
- BTM, Koramangala, and Whitefield are the top areas by restaurant count
- North Indian, Chinese, and South Indian are the most popular cuisines
- Most restaurants fall into an affordable average cost range
- Ratings cluster around the mean; extreme ratings are less common

---

## 📈 Visualizations
The notebook includes:
- Count plots by location and restaurant type
- Boxplots and histograms of cost distributions
- Bar plots for popular cuisines
- Pie charts of type and location shares

---

## 📂 Recommendations & Next Steps
- Build predictive models (e.g., rating prediction based on features)
- Perform comparative city analysis if other datasets are available
- Explore temporal trends with date-based data if added

---

## ⚙️ Installation
```bash
git clone https://github.com/Harshith-Reddy11/EDA-on-Zomato-Dataset.git
cd EDA-on-Zomato-Dataset
pip install -r requirements.txt
