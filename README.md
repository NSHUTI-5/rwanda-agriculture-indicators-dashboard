# 🌾 Rwanda Agriculture Development Analytics | INSY 8413 Capstone Project

## 📘 Project Overview
This project explores agricultural development trends in Rwanda using data analytics. By analyzing key indicators such as land use, crop production, and rural development metrics, the goal is to uncover patterns and insights that can support more informed agricultural planning. The project uses Python for data preprocessing, visualization, and clustering, and Power BI for interactive dashboards. This combination provides both deep analytical insight and user-friendly visual storytelling.
---

## MY Information

- **Name: Nshuti Dorothy and ID:27129 
- **Sector: Agriculture  
- **Course: Introduction to Big Data Analytics  
- **Instructor: Eric Maniraguha  
   


# Problem Statement
"Can access to irrigation influence yields across Rwanda’s main staple crops?"                                                                                                          
   Dataset Information

- Title: Agriculture and Rural Development – Rwanda  
- Source: [Humanitarian Data Exchange (HDX)](https://data.humdata.org/)  
- **Dataset Link:** [Download CSV](https://data.humdata.org/dataset/e2e4318c-a5b2-4f89-bcf9-9aa5305274b7/resource/76b8e361-0e9e-4154-aeb4-ff07d8f738c8/download/agriculture-and-rural-development_rwa.csv)
- **Colab link:** [Reach on my google colab link](https://colab.research.google.com/drive/10R5wEVpIN51sNwyzvCP2zfbWGG-57H7_?authuser=0#scrollTo=zN9_qU5UJw8w)
- Format: CSV  
- Size: 60 rows × 6 columns 


## 🧪 Python Analytics Tasks
In this section, we used Python to clean and explore the dataset, apply clustering techniques, and evaluate the results. The goal was to uncover patterns in agricultural data and support better decision-making.



### ✅ 1. Data Cleaning
- Handle missing values
- Fill missing values (forward fill, backward fill)
- Standardize data types
- Detect and remove outliers using IQR
- Apply scaling 
<img width="980" height="685" alt="image" src="https://github.com/user-attachments/assets/e1389a26-16ff-4b95-996e-30ceb78f7c8c" />

# Categorical/text columns: fill with most common
cat_cols = df.select_dtypes(include=['object']).columns
for c in cat_cols:
    df[c] = df[c].fillna(df[c].mode()[0])

### ✅ 2. Exploratory Data Analysis (EDA)
- Descriptive statistics (`df.describe()`)
- Correlation matrix (`sns.heatmap`)
- Time series trends
- Histograms, boxplots, and pairplots

 screenshots of visualizations in: <img width="970" height="686" alt="image" src="https://github.com/user-attachments/assets/2c3e26e8-d399-4739-a9d1-99704a79cf78" />
enshots/eda/`
<img width="983" height="706" alt="image" src="https://github.com/user-attachments/assets/cb7ff127-3fd5-4a85-8fb0-17b39e89a731" />
<img width="982" height="658" alt="image" src="https://github.com/user-attachments/assets/e7eda53f-a667-41da-b3d9-5789a4fcfbf8" />

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
  


screenshots of dashboard visuals

<img width="995" height="623" alt="image" src="https://github.com/user-attachments/assets/d69d4864-1b17-49ec-b1ef-baf53cdb0734" />



