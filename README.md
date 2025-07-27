📊 Customer Churn Prediction Using Machine Learning
🎯 Objective

To develop a machine learning classification model that accurately predicts whether a customer is likely to churn, using the Telco Customer Churn dataset or a similar data
📁 Project Structure

```
customer-churn-prediction/
│
├── data/
│   └── churn_data.csv                # Cleaned dataset (150 rows, no duplicates)
│
├── churn_prediction.ipynb           # Jupyter Notebook with full analysis & model
│
├── README.md                        # Project overview and instructions
│
└── assets/
    └── plots/                       # EDA and model evaluation visualizations


## 📝 Dataset Details

* **Rows**: 150 unique customer records
* **Features**: Customer demographics, service usage, tenure, charges, etc.
* **Target**: `Churn` (Yes/No)
## 🔍 Key Steps

### 1. Data Cleaning & Preprocessing

* Removed duplicates
* Handled missing values
* Converted data types appropriately

### 2. Exploratory Data Analysis (EDA)

* Visualized churn distribution
* Correlation heatmaps and bar plots for categorical and numerical features

### 3. Feature Engineering

* Label Encoding for binary features
* One-Hot Encoding for multi-class features
* Feature Scaling using StandardScaler

### 4. Model Building

* Models used:

  * Logistic Regression
  * Random Forest
  * Decision Tree
* Compared models using:

  * Accuracy
  * Confusion Matrix
  * ROC-AUC Score

### 5. Model Evaluation

* Selected the best performing model based on test accuracy and ROC-AUC
* Plotted feature importance for interpretability
📈 Visualizations Included

* Churn rate distribution
* Service usage vs. Churn rate
* Heatmap of feature correlations
* ROC Curve
* Confusion Matrix
* Feature Importance bar chart

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook churn_prediction.ipynb
   ```

---

## 💡 Future Improvements

* Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
* Add XGBoost/LightGBM for improved performance
* Deploy as a web application using Streamlit or Flask

