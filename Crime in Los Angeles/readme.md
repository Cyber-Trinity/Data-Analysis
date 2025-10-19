# Crime in Los Angeles Analysis

![Crime Scene illustration](src/project-1.jpg)

Los Angeles, California 😎. The City of Angels. Tinseltown. The Entertainment Capital of the World! 

Known for its warm weather, palm trees, sprawling coastline, and Hollywood, along with producing some of the most iconic films and songs. However, as with any highly populated city, it isn't always glamorous and there can be a large volume of crime. That's where I can help!

This project analyzes **crime patterns in Los Angeles** using the publicly available **Los Angeles Police Department (LAPD) crime dataset**. The goal is to identify trends, hotspots, and insights that can help understand crime distribution in the city. My insights will be useful to allocate resources effectively to tackle various crimes in different areas.

---

## 🗂️ Project Structure
crime-in-los-angeles/
<br>
├── src/ # Project files and datasets (not included due to licensing)
<br>
├── Crime_Analysis.ipynb # Jupyter notebooks for analysis
<br>
├── requirements.txt # Dependencies
<br>
├── Report_Crime_Analysis.pdf # Summary report of findings.
<br>
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
### The project performs the following:

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

`git clone https://github.com/Cyber-Trinity/Data-Analysis.git`

`cd Data-Analysis/Crime in Los Angeles`

2. **Install dependencies**

`pip install -r requirements.txt`


3. **Run analysis notebooks**

- Open Crime_Analysis.ipynb in Jupyter Notebook or VS Code

cd dashboard
streamlit run app.py   # or python app.py for Dash

---

## 📑 Report

A detailed project report is included as [Report_Crime_Analysis.pdf](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/)

It contains methodology, visualizations, findings, and key insights.

---

## ⚡ Notes

- Raw datasets are not included

- You can download the data from the LAPD Open Data Portal.

- Code and notebooks are reproducible with sample data.

- This analysis can be expanded for predictive modeling or advanced spatial analysis.