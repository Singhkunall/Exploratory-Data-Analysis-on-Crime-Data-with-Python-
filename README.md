# Exploratory-Data-Analysis-on-Crime-Data-with-Python-
# EDA-project
# 🕵️ Crime Data Analysis (2020 - Present)

This project is a comprehensive Exploratory Data Analysis (EDA) on the **Los Angeles Crime Dataset (2020–Present)** using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.  
The goal is to uncover trends, patterns, and insights about crime incidents using real-world data.

---

## 📁 Dataset Used
- **Source**: [data.lacity.org](https://data.lacity.org/)  
- **Name**: `Crime_Data_from_2020_to_Present.csv`
- **Records**: 1,000,000+ rows  
- **Features**: Date, Time, Location, Crime Type, Victim Descent, Weapon Used, etc.

---

## 🛠 Technologies & Tools

| Category              | Tools / Libraries                      |
|-----------------------|----------------------------------------|
| Language              | Python 3.x                             |
| Data Manipulation     | Pandas, NumPy                          |
| Data Visualization    | Matplotlib, Seaborn                    |
| Statistical Analysis  | Scipy (Shapiro-Wilk, Chi-squared)      |
| Machine Learning      | Scikit-learn (Random Forest Classifier) |
| IDE                   | Jupyter Notebook / VS Code             |

---

## 📌 Project Structure

- `1_Data_Loading_Cleaning.ipynb` → Load CSV, clean missing/nulls, handle datatypes  
- `2_Visualization_EDA.ipynb` → Univariate, Bivariate plots (Time, Location, Crime Type)  
- `3_Statistical_Analysis.ipynb` → Correlation, Outliers, Hypothesis Testing  
- `4_Machine_Learning_Model.ipynb` → Simple Random Forest Classifier to predict crime type  
- `README.md` → Project Overview  

---

## 📈 Key Insights

- 🔥 **Peak Crime Hours**: Most crimes happen between 6 PM to 11 PM.
- 🗺️ **Hotspots**: Downtown LA and South LA see maximum criminal activity.
- 🕒 **Monthly Trends**: Crime frequency dips during pandemic lockdown periods.
- ⚔️ **Weapons**: Highest number of crimes committed without weapons or with handguns.
- 📊 **Classification Accuracy** (RandomForest): ~72%

---

## 💡 What I Learned

- Real-world data cleaning & type conversions  
- Data visualization principles and customization  
- Statistical testing using Python (Shapiro, Chi-Square)  
- Simple ML model training and evaluation  
- Importance of feature engineering in time/location-based datasets

---

## 🚀 Future Scope

- Add clustering for unsupervised crime pattern detection  
- Deploy model using Flask or Streamlit  
- Create an interactive dashboard with Plotly or PowerBI  

---

## 📌 How to Run

```bash
git clone https://github.com/kunalusername/Crime-EDA.git
cd Crime-EDA
jupyter notebook
