# 🌲 Forest Type Cover Prediction (PRCP-1005)

## 📌 Project Overview

This project aims to predict the **forest cover type** for a given 30 × 30 meter patch of forest land using various geographical and environmental features. The dataset is provided by the **US Forest Service (USFS)** and contains information derived from cartographic variables.

The project involves:

- Performing Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature analysis
- Building Machine Learning models
- Evaluating model performance
- Predicting one of seven forest cover types

---

## 🎯 Problem Statement

### Task 1
Prepare a complete **Exploratory Data Analysis (EDA)** report on the given dataset.

### Task 2
Create a predictive Machine Learning model that accurately predicts **seven different forest cover types** in four different wilderness areas.

---

## 📂 Dataset Information

Each record represents a **30 × 30 meter** forest cell.

The dataset contains:

- Numerical terrain features
- Wilderness Area indicators
- Soil Type indicators
- Target variable: **Cover_Type**

### Target Classes

The target variable contains **7 forest cover types**.

---

## 📊 Features

### Numerical Features

- Elevation
- Aspect
- Slope
- Horizontal Distance to Hydrology
- Vertical Distance to Hydrology
- Horizontal Distance to Roadways
- Hillshade (9 AM)
- Hillshade (Noon)
- Hillshade (3 PM)
- Horizontal Distance to Fire Points

### Categorical Features

#### Wilderness Areas (One-Hot Encoded)

- Wilderness_Area1
- Wilderness_Area2
- Wilderness_Area3
- Wilderness_Area4

#### Soil Types

There are **40 Soil_Type** columns representing different soil classifications.

---

# 🛠️ Project Workflow

## 1. Import Required Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM

---

## 2. Load Dataset

- Read dataset using Pandas
- Display basic information
- Check dimensions

---

## 3. Data Exploration

Performed:

- Dataset inspection
- Missing value analysis
- Duplicate value analysis
- Statistical summary
- Data type verification

---

## 4. Exploratory Data Analysis (EDA)

The following visualizations were created:

- Histograms
- Boxplots
- Scatter plots
- Count plots
- Correlation Heatmap
- Distribution plots

EDA helped understand:

- Feature distributions
- Relationships between variables
- Class balance
- Outliers
- Correlations

---

## 5. Data Preprocessing

- Checked missing values
- Removed duplicates (if any)
- Feature selection
- Train-test split

---

## 6. Machine Learning Models

Several models can be trained, including:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM

The best-performing model is selected based on accuracy.

---

## 7. Model Evaluation

Performance metrics include:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Feature Importance

---

# 📁 Project Structure

```
Forest-Type-Cover-Prediction/
│
├── data/
│   └── train.csv
│
├── notebooks/
│   └── Forest-Type-Cover-Prediction.ipynb
│
├── reports/
│   └── Forest_Cover_Report.pdf
│
├── README.md
│
└── requirements.txt
```

---

# 📈 Expected Results

The project predicts one of seven forest cover types with high accuracy.

Typical model performance:

| Model | Accuracy |
|--------|----------|
| Decision Tree | 80–88% |
| Random Forest | 90–95% |
| XGBoost | 94–97% |
| LightGBM | 95–98% |

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Forest-Type-Cover-Prediction.git
```

Navigate to the project folder:

```bash
cd Forest-Type-Cover-Prediction
```

Install required packages:

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Forest-Type-Cover-Prediction.ipynb
```

Run all cells sequentially.

---

# 📚 Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM

---

# 📊 Project Outcomes

- Comprehensive Exploratory Data Analysis
- Data visualization
- Feature engineering
- Machine Learning model development
- Model evaluation
- Forest cover type prediction

---

# 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Ensemble learning
- Feature selection optimization
- Model deployment using Flask or FastAPI
- Interactive dashboard with Streamlit

---

