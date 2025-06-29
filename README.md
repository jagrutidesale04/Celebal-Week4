# 📊 Week 4: Heart Disease EDA + XGBoost Modeling

This project is part of **Week 4** of the **Celebal Summer Internship** program.

The assignment was to perform **in-depth Exploratory Data Analysis (EDA)** on a complex dataset. I chose the **Heart Disease UCI dataset** from Kaggle, conducted a full EDA, and then built a predictive model using **XGBoost** with hyperparameter tuning and unsupervised clustering using **PCA + KMeans**.

## 📌 Features

- ✅ Thorough EDA with:
  - Dataset summary, null check, statistical analysis
  - Visualizations: histograms, boxplots, heatmaps, countplots
  - Outlier detection and correlation insights
- 🧠 Predictive Modeling:
  - Train/Test split with `train_test_split()`
  - `XGBoostClassifier` with cross-validation
  - `RandomizedSearchCV` for hyperparameter tuning
- 🔬 Dimensionality Reduction:
  - StandardScaler + PCA (2D + 3D visualization)
- 🎯 Clustering with KMeans:
  - Elbow method, Silhouette Score, PCA-based cluster visualization
- 📉 Feature importance ranking using XGBoost

## 📂 File Structure

```
Celebal-Week4/
├── week4.ipynb                  # Main Jupyter Notebook
├── heart.csv                   # Dataset (from Kaggle)
├── requirements.txt            # Python dependencies
└── README.md                   # This file
```

## 🚀 How to Run

### 1. Clone this Repository

```bash
git clone https://github.com/jagrutidesale04/Celebal-Week4.git
cd Celebal-Week4
```

### 2. (Optional) Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate      # Windows
# or
source venv/bin/activate   # macOS/Linux
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Notebook

```bash
jupyter notebook week4.ipynb
```

## 📊 Visualizations Included

- Histograms
- Boxplots
- Correlation heatmap
- Countplot of target
- 2D PCA scatter plot
- 3D PCA cluster visualization with Plotly

## 📎 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
plotly
scipy
```

## 👩‍💻 Author

**Jagruti Desale**  
B.Tech – Data Science and Engineering (3rd Year)  
Summer Intern @ Celebal Technologies

🔗 [GitHub](https://github.com/jagrutidesale04)  
💼 [LinkedIn](https://www.linkedin.com/in/jagruti-desale-jd04)

## 📜 License

This project is intended for academic and learning purposes only as part of the Celebal Summer Internship program.