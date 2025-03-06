# Ontario Traffic Accident Analysis

## 📌 Project Overview
This project analyzes traffic accidents in Ontario, focusing on patterns, anomaly detection, and crash severity prediction. Using statistical analysis and machine learning, this study examines:
- 🚦 The effect of traffic control devices, weather, and road conditions on accident severity.
- 📈 **Trends over time**, identifying high-risk periods for accidents.
- 🔍 **Correlation analysis** between crash severity and contributing factors.
- 🤖 **Predictive modeling** for assessing accident severity risks.

The dataset is sourced from Toronto Police Service Open Data:  
🔗 **[Traffic Collisions Dataset](https://data.torontopolice.on.ca/datasets/TorontoPS::traffic-collisions-open-data-asr-t-tbl-001/about)**

---

## ⚙️ Technologies Used
- **Python** → Data analysis and machine learning.
- **pandas, numpy** → Data cleaning and preprocessing.
- **matplotlib, seaborn** → Data visualization.
- **sklearn.preprocessing** → Feature scaling.
- **Jupyter Notebook** → Interactive analysis.

---

## 🚀 Features
- ✅ **Data Cleaning & Preprocessing** → Removes duplicates, converts date columns, and processes categorical variables.
- 📊 **Exploratory Data Analysis (EDA)** → Histograms, scatter plots, and box plots for identifying trends.
- 📈 **Trend & Correlation Analysis** → Examines relationships between crash severity, time of day, and environmental factors.
- 🏎️ **Crash Severity Prediction** → Uses machine learning to predict accident severity.
- - 🔮 **Machine Learning Models**:
  - **Logistic Regression** → Predicts likelihood of severe accidents.
  - **Random Forest Classifier** → Identifies key factors influencing crash severity.
  - **Decision Trees** → Explains accident severity classification in an interpretable way.
  - **K-Means Clustering** → Groups accidents based on shared characteristics.


---

## 🛠 How to Run

```bash
# 1️⃣ Clone the Repository
git clone https://github.com/YOUR-USERNAME/Ontario-Traffic-Accident-Analysis.git
cd Ontario-Traffic-Accident-Analysis
# 2️⃣ Install Required Python Packages
pip install pandas numpy matplotlib seaborn scikit-learn
# 3️⃣ Load Dataset
# Ensure 'Traffic_accidents dataset.csv' is in the project directory.
# 4️⃣ Run Jupyter Notebook
jupyter notebook Ontario_Traffic_Accident_Analysis.ipynb

