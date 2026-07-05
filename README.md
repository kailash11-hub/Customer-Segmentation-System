# 🌍 Country Development Segmentation using Machine Learning

A Machine Learning project that performs **country segmentation** using clustering algorithms and predicts cluster labels using supervised learning models. This project helps identify groups of countries with similar socio-economic characteristics, which can assist governments, NGOs, and policymakers in making informed decisions.

---

## 📌 Project Overview

This project uses the **Country Data** dataset containing socio-economic and health-related indicators of different countries. The workflow consists of:

1. Data preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature scaling
4. Country segmentation using clustering algorithms
5. Classification of clusters using machine learning models
6. Model evaluation and feature importance analysis

---

## 🚀 Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Heatmap
- Distribution plots
- Feature Scaling using StandardScaler
- Country Segmentation using:
  - K-Means Clustering
  - DBSCAN Clustering
- Optimal cluster selection using Elbow Method
- Cluster quality evaluation using Silhouette Score
- Classification Models:
  - Random Forest
  - XGBoost
- Baseline model comparison using Dummy Classifier
- 5-Fold Cross Validation
- Confusion Matrix visualization
- Feature Importance analysis

---

## 📂 Dataset

**Dataset:** Country-data.csv

The dataset contains socio-economic indicators such as:

- Child Mortality
- Exports
- Health Expenditure
- Imports
- Income
- Inflation
- Life Expectancy
- Total Fertility
- GDP per Capita

Target labels are generated using **K-Means Clustering**.

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab

---

## 📊 Machine Learning Workflow

### 1. Data Preprocessing

- Load dataset
- Check missing values
- Statistical summary
- Feature scaling using StandardScaler

### 2. Exploratory Data Analysis

- Pair Plot
- Correlation Heatmap
- Feature Distribution Histograms

### 3. Clustering

#### K-Means

- Elbow Method for selecting optimal clusters
- Cluster visualization
- Silhouette Score evaluation

#### DBSCAN

- Density-based clustering
- Noise detection
- Silhouette Score evaluation

---

### 4. Classification Models

After creating cluster labels using K-Means, supervised learning models are trained to predict the cluster of unseen countries.

Models used:

- Dummy Classifier (Baseline)
- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Model Evaluation

Performance metrics include:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Cross Validation Accuracy
- Feature Importance

The notebook compares model performance to identify the most effective classifier.

---

## 📷 Visualizations

The project generates several visualizations including:

- Pair Plot
- Correlation Heatmap
- Feature Histograms
- Elbow Curve
- K-Means Cluster Plot
- DBSCAN Cluster Plot
- Random Forest Confusion Matrix
- XGBoost Confusion Matrix
- Feature Importance Chart

---

## 📁 Project Structure

```
Country-Segmentation/
│
├── Country-data.csv
├── Country_Segmentation.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Country-Segmentation.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook.

---

## 📦 Required Libraries

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
```

Install manually:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Interactive dashboard using Streamlit
- PCA for dimensionality reduction
- Automated cluster selection
- Model deployment with Flask or FastAPI
- Explainability using SHAP

---

## 🎯 Applications

- Country development analysis
- Economic policy planning
- International aid allocation
- Market segmentation
- Socio-economic research
- Government decision support

---

## 👨‍💻 Author

**Kailash Kumar**

Machine Learning | Data Science | Java Full Stack Developer

---

## ⭐ If you found this project useful, consider giving it a star!
