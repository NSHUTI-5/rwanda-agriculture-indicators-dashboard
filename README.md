# 🌾 Rwanda Agriculture Development Analytics | INSY 8413 Capstone Project

## 📘 Project Overview
This project was developed as part of the inal Capstone Examfor the course Introduction to Big Data Analytics. It analyzes Rwanda's agricultural trends using Python and Power BI to reveal insights that can improve rural development outcome and if it enhance there day to day life.

---

## 👤 Student Information

- **Name: Nshuti Dorothy and ID:27129 
- **Sector: Agriculture  
- **Course: Introduction to Big Data Analytics  
- **Instructor: Eric Maniraguha  
   


# Problem Statement
"Can access to irrigation influence yields across Rwanda’s main staple crops?"                                                                                                          
   Dataset Information

- Title: Agriculture and Rural Development – Rwanda  
- Source: [Humanitarian Data Exchange (HDX)](https://data.humdata.org/)  
- **Link:** [Download CSV](https://data.humdata.org/dataset/e2e4318c-a5b2-4f89-bcf9-9aa5305274b7/resource/76b8e361-0e9e-4154-aeb4-ff07d8f738c8/download/agriculture-and-rural-development_rwa.csv)  
- Format: CSV  
- Size: 60 rows × 6 columns 


## 🧪 Python Analytics Tasks

All the code for the following steps should be written inside the notebook:  
📄 `Agliculture cl.ipynb`

### ✅ 1. Data Cleaning
- Handle missing values
- Fill missing values (forward fill, backward fill)
- Standardize data types
- Detect and remove outliers using IQR
- Apply scaling (`StandardScaler`)
<img width="980" height="685" alt="image" src="https://github.com/user-attachments/assets/e1389a26-16ff-4b95-996e-30ceb78f7c8c" />

### ✅ 2. Exploratory Data Analysis (EDA)
- Descriptive statistics (`df.describe()`)
- Correlation matrix (`sns.heatmap`)
- Time series trends
- Histograms, boxplots, and pairplots

 screenshots of visualizations in: <img width="970" height="686" alt="image" src="https://github.com/user-attachments/assets/2c3e26e8-d399-4739-a9d1-99704a79cf78" />
enshots/eda/`

### ✅ 3. Machine Learning – Clustering
- Chosen Model: K-Means Clustering
- Use Elbow Method and Silhouette Score to find best `k`
- Use `PCA` to reduce dimensions for cluster visualizati 
<img width="966" height="687" alt="image" src="https://github.com/user-attachments/assets/03e45c4a-91db-4a48-895c-f5c6607e9aca" />
hots/clustering/`

### ✅ 4. Evaluation
- Metric: Silhouette Score (e.g., `0.65`)
- Justify chosen cluster count and model
- Evaluate separability using plots

👉 **📸 Add evaluation metrics as screenshot** in:  
📁 <img width="947" height="156" alt="image" src="https://github.com/user-attachments/assets/9ca8000e-8cb0-4899-8127-8235609f7a3a" />


## 📊 Power BI Dashboard

You should create a Power BI dashboard that includes:

- **Line Chart:** Trends over time
- **Bar Chart:** Top development indicators
- **Map (optional):** If geolocation is available
- **Slicers:** Year and Indicator filter
- **KPIs:** Highest growth year, average development

👉 Save this in:  
📄 `powerbi/agriculture_dashboard.pbix`

👉 **📸 Add screenshots of dashboard visuals** in:  
📁 `screenshots/powerbi/`

---

## 📽 PowerPoint Presentation

Include:
- Problem Statement and Objective
- Dataset summary
- Step-by-step Python process
- Clustering results with interpretation
- Power BI visuals
- Final insights and recommendations

👉 Save your presentation in:  
📄 `presentation/capstone_presentation.pptx`

👉 Add title slide screenshot in:  
📁 `screenshots/ppt/`

---

## 📁 Final Project Folder Structure




