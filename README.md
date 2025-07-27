# Lloyds Banking Group - Customer Churn Prediction

This project is part of the Lloyds Banking Group's Forage Job Simulation, where I built a predictive model to identify customers at risk of churn using structured banking datasets. The project was divided into two main tasks:

## 🚀 Tasks

### 📊 Task 1: Data Gathering, EDA, and Preprocessing
- Combined customer demographics, transaction history, service interactions, and online activity.
- Created aggregations such as total spend, transaction count, and unresolved support queries.
- Visualized trends using histograms, box plots, count plots, and a correlation heatmap.
- Exported a cleaned dataset (`cleaned_customer_data.csv`) for modeling.

📂 Artifacts:
- `Eda_and_cleaning.ipynb`
- `cleaned_customer_data.csv`

### 🤖 Task 2: Machine Learning Model for Churn Prediction
- Chose **Random Forest Classifier** for its balance between accuracy and interpretability.
- Used a pipeline with one-hot encoding and a classifier.
- Evaluated using ROC-AUC, F1-score, and confusion matrix.

📂 Artifacts:
- `Machine learning model.ipynb`
- `task2_model_report.md`

## 📈 Results
- **ROC-AUC**: *0.517*

## 🛠️ Tech Stack
- Python, Pandas, Seaborn, Scikit-learn, Matplotlib
- Jupyter Notebook

## 📁 Getting Started
```bash
# Clone the repo
git clone https://github.com/Dpkvas/Customer-Churn-Prediction.git

# Install dependencies
pip install -r requirements.txt
