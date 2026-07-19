# 🌍 Country Development Segmentation using K-Means Clustering

A Machine Learning project that groups countries based on their development indicators using the **K-Means Clustering** algorithm. This project analyzes countries using **Population**, **Fertility Rate**, and **Life Expectancy** data to identify countries with similar development characteristics.

---

## 📌 Project Overview

This project applies **Unsupervised Machine Learning** to segment countries into different clusters based on their demographic and health indicators.

The clustering helps understand the development status of countries and supports data-driven decision-making.

---

## 🎯 Objectives

- Analyze country development data.
- Perform Exploratory Data Analysis (EDA).
- Apply Feature Engineering.
- Scale numerical features.
- Find the optimal number of clusters.
- Cluster countries using K-Means.
- Visualize clusters using PCA.
- Interpret cluster characteristics.

---

## 📂 Dataset

The project uses three datasets from the **World Bank**.

- country_population.csv
- fertility_rate.csv
- life_expectancy.csv

### Features Used

- Population
- Fertility Rate
- Life Expectancy

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Machine Learning Concepts

- Data Cleaning
- Feature Engineering
- StandardScaler
- K-Means Clustering
- Elbow Method
- WCSS
- Silhouette Score
- PCA (Principal Component Analysis)
- Cluster Interpretation

---

## 🚀 Project Workflow

### 1. Import Libraries

Import all required Python libraries.

### 2. Load Dataset

Load the three World Bank datasets.

### 3. Merge Dataset

Merge all datasets using the **Country Name** column.

### 4. Data Cleaning

- Handle missing values
- Remove unwanted columns
- Rename columns

### 5. Exploratory Data Analysis

- Histogram
- Box Plot
- Pair Plot
- Correlation Matrix
- Heatmap
- Scatter Plot
- Bar Plot

### 6. Feature Engineering

Select important numerical features.

- Population
- Fertility Rate
- Life Expectancy

### 7. Data Scaling

Apply StandardScaler to normalize features.

### 8. Elbow Method

Determine the optimal number of clusters.

### 9. Silhouette Score

Evaluate clustering quality.

### 10. K-Means Clustering

Group countries into clusters.

### 11. PCA Visualization

Reduce dimensions for visualization.

### 12. Cluster Interpretation

Analyze each cluster using average feature values.

---

## 📊 Features

- Population Analysis
- Fertility Rate Analysis
- Life Expectancy Analysis
- Correlation Analysis
- Country Segmentation
- PCA Visualization
- Cluster Summary

---

## 📈 Visualizations

- Histogram
- Box Plot
- Heatmap
- Pair Plot
- Scatter Plot
- Bar Plot
- Count Plot
- PCA Scatter Plot

---

## 📁 Output Files

- Country_Development.csv
- Features.csv
- Scaled_Data.csv
- Country_Clusters.csv
- Final_Country_Clusters.csv

---

## 📌 Project Structure

```
Country-Development-Segmentation/
│
├── Dataset/
│   ├── country_population.csv
│   ├── fertility_rate.csv
│   └── life_expectancy.csv
│
├── Notebook/
│   └── Country_Development_Segmentation.ipynb
│
├── Output/
│   ├── Country_Development.csv
│   ├── Features.csv
│   ├── Scaled_Data.csv
│   ├── Country_Clusters.csv
│   └── Final_Country_Clusters.csv
│
├── Images/
│   ├── Histogram.png
│   ├── Heatmap.png
│   ├── PairPlot.png
│   ├── ScatterPlot.png
│   ├── ElbowMethod.png
│   ├── PCA.png
│   └── ClusterCount.png
│
├── README.md
└── requirements.txt
```

---

## 📷 Results

The project successfully segmented countries into **3 clusters** using the K-Means algorithm.

The clusters were visualized using **Principal Component Analysis (PCA)**.

The first two principal components preserved approximately **95% of the total variance**, making the visualization highly representative.

---

## 📌 Conclusion

This project demonstrates how **K-Means Clustering** can effectively group countries with similar demographic and health characteristics.

The clustering results can support policymakers, researchers, and organizations in understanding global development patterns.

---

## 🔮 Future Improvements

- Add GDP per Capita
- Add Literacy Rate
- Add Human Development Index (HDI)
- Add Internet Usage
- Create Interactive Dashboard using Streamlit
- Deploy as a Web Application

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Country-Development-Segmentation.git
```

### Navigate

```bash
cd Country-Development-Segmentation
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run Notebook

Open:

```
Country_Development_Segmentation.ipynb
```

Run all cells in Google Colab or Jupyter Notebook.

---

## 📦 Requirements

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 👨‍💻 Author

**Rahul**

B.Tech – Computer Science & Engineering (AI & ML)

Machine Learning Enthusiast

---

## ⭐ If you like this project

Please ⭐ Star this repository and share it with others.
