# 🧠 Obesity Level Prediction using Machine Learning

A machine learning project to **predict obesity levels** in individuals based on their physical condition and lifestyle habits. The dataset includes real and synthetic samples collected from individuals in **Mexico, Peru, and Colombia**.

🔗 **Live Report**:  
👉 [Click here to view the HTML report](https://himanshu-shekhar2327.github.io/Obesity-Level-Prediction/)

---

## 📊 Project Overview

This project is part of a Data Science & Machine Learning coursework. It involves the full ML pipeline — from data cleaning and exploratory analysis to model training and evaluation — to classify individuals into one of the following obesity levels:

- **Insufficient Weight**
- **Normal Weight**
- **Overweight Level I**
- **Overweight Level II**
- **Obesity Type I**
- **Obesity Type II**
- **Obesity Type III**

---

## 🧾 Dataset Information

- 📄 **Source**: Provided as part of coursework (original source by Fabio Mendoza Palechor and Alexis De la Hoz Manotas, 2019)
- 🧬 **Records**: 2111 individuals
- 📊 **Attributes**: 17 features including:
  - Age, Gender, Height, Weight
  - Daily eating habits
  - Water consumption
  - Physical activity
  - Smoking, alcohol use
  - Transportation mode
  - Family history with obesity
- 🧪 **Target variable**: `NObeyesdad` (Obesity Level)
- ⚠️ **Note**: 77% of data was synthetically generated using the SMOTE technique (Weka tool)

---

## 🔧 Steps Performed

### 🧼 Data Preprocessing
- Missing value check
- Outlier detection (Boxplot, Z-score)
- Encoding categorical variables
- Feature scaling (StandardScaler, MinMaxScaler)

### 📊 Data Visualization
- **Univariate**: Histograms, boxplots, bar charts
- **Bivariate**: Scatter plots, correlation heatmaps
- **Multivariate**: Pair plots, PCA, DBSCAN clustering

### 📉 Dimensionality Reduction
- PCA (Principal Component Analysis)
- DBSCAN clustering for anomaly detection

### 🤖 Models Used

- ✅ **Logistic Regression**
- ✅ **K-Nearest Neighbors (KNN)**
- ✅ **Random Forest**
- ✅ **Support Vector Machine (SVM)**
- ✅ **Decision Tree Classifier**
- ✅ **Neural Network (MLPClassifier)**
- ✅ **AdaBoost (Adaptive Boosting)**
- ✅ **XGBoost (Extreme Gradient Boosting)r**

### 📈 Model Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- Feature importance visualization

---

## 📦 Libraries & Tools

| Tool | Use |
|------|-----|
| `pandas`, `numpy` | Data handling |
| `matplotlib`, `seaborn` | Data visualization |
| `sklearn` | Machine Learning algorithms |
| `DBSCAN`, `PCA`, `StandardScaler` | Clustering and scaling |
| `Jupyter Notebook` | Development environment |
| `Git`, `GitHub Pages` | Version control and deployment |

---

## 📁 Project Structure

```bash
Obesity-Level-Prediction/
│
├── index.html                 # Exported Jupyter notebook report
├── README.md                  # Project description
├── *.ipynb (optional)         # Original notebook (if available)
└── ObesityDataSet_*.csv       # Dataset file

## 👨‍🎓 Author

**Himanshu Shekhar**  
B.Tech CSE Student, Silicon Institute of Technology  
GitHub: [@himanshushekhar2327](https://github.com/himanshushekhar2327)

---

## Acknowledgements

- Dataset by Fabio Mendoza Palechor & Alexis De la Hoz Manotas (2019)
- Synthetic data generated using SMOTE with the Weka tool
- Project developed as part of Data Science & Machine Learning course