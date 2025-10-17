# Crime in Los Angeles Analysis

This project analyzes **crime patterns in Los Angeles** using the publicly available **Los Angeles Police Department (LAPD) crime dataset**. The goal is to identify trends, hotspots, and insights that can help understand crime distribution in the city.

---

## 🗂️ Project Structure
crime-in-los-angeles/
├── data/ # Raw or sample datasets (not included due to licensing)
├── notebooks/ # Jupyter notebooks for analysis
├── src/ # Python scripts for reproducible analysis
├── dashboard/ # Interactive dashboards (optional)
├── report.pdf # Summary report of findings
└── README.md # Project description (this file)


---

## 📌 Dataset

- **Source:** [Los Angeles Open Data Portal](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/)
- **Description:** Includes crime reports with location, type, date, and other relevant attributes.
- **Note:** The raw dataset is **not included** in this repository due to size and privacy. Sample or anonymized data can be used for reproducing the analysis.

---

## 🛠️ Tools & Libraries

- Python 3.10+  
- Pandas, NumPy for data manipulation  
- Matplotlib, Seaborn for visualizations  
- Plotly / Dash / Streamlit for interactive dashboards (optional)  
- Jupyter Notebook for exploratory analysis

---

## 📊 Analysis Overview

The project performs the following:

1. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Convert date/time columns
   - Encode categorical variables if needed

2. **Exploratory Data Analysis (EDA)**
   - Crime counts over time
   - Crime type distribution
   - Heatmaps for geographic distribution
   - Temporal patterns (hour, day, month trends)

3. **Visualizations**
   - Static charts in notebooks (Matplotlib, Seaborn)
   - Optional interactive dashboard (Plotly Dash or Streamlit) for dynamic exploration

4. **Insights & Findings**
   - Top neighborhoods by crime frequency
   - Most common crime types
   - Temporal trends in crime activity

---

## 📌 How to Run

1. **Clone this project**
```bash
git clone https://github.com/your-username/data-analytic.git
cd data-analytic/project-1
```

2. **Install dependencies**

`pip install -r requirements.txt`


3. **Run analysis notebooks**

- Open notebooks/Crime_Analysis.ipynb in Jupyter Notebook or VS Code

cd dashboard
streamlit run app.py   # or python app.py for Dash

---

## 📑 Report

A detailed project report is included as `report.pdf`.
It contains methodology, visualizations, findings, and key insights.

---

## ⚡ Notes

Raw datasets are not included — please download the data from the LAPD Open Data Portal.

Code and notebooks are reproducible with sample data.

This analysis can be expanded for predictive modeling or advanced spatial analysis.