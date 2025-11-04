# Investigating Netflix Movies

![Crime Scene illustration](src/project-2.webp)
**Netflix**! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.

This project explores Netflix’s vast collection of movies and TV shows through data-driven insights. Using exploratory data analysis (EDA) techniques, I examined content distribution by genre, country, release year, and duration to uncover viewing trends and production patterns.

**Key Objectives:**
- Analyze the composition of Netflix’s catalog across different categories.
- Identify trends in content production and release years.
-  the most represented countries, directors, and genres.
- Visualize insights with Python libraries such as Pandas, Matplotlib, and Seaborn.
---

## 🗂️ Project Structure
Investigating Netflix Movies/
<br>
├── src/ # Project files and datasets (not included due to licensing)
<br>
├── notebook.ipynb # Jupyter notebooks for analysis
<br>
├── requirements.txt # Dependencies
<br>
├── Report_Investigating_Netflix.pdf # Summary report of findings.
<br>
└── README.md # Project description (this file)

---

## 📌 Dataset
- **Source:** [DataCamp Projects – Investigating Netflix Movies](https://app.datacamp.com/)
- **Description:** The dataset contains detailed information about Netflix’s catalog of movies and TV shows. Each record includes the show’s title, type, director, cast, country of origin, release year, date added to Netflix, duration, genre, and a brief description.
- **Note:** The original dataset is available within the DataCamp Projects environment. Due to licensing and privacy restrictions, the raw dataset is not included in this repository.

---

## 🛠️ Tools & Libraries

- Python 3.10+  
- Pandas, NumPy for data manipulation  
- Matplotlib, Seaborn for visualizations   
- Jupyter Notebook for analysis

---

## 📊 Analysis Overview
### The project performs the following:

**1. Data Cleaning & Preprocessing**

- Filled missing Vict Sex and Vict Descent with mode values
- Replaced missing Weapon Desc with "UNKNOWN WEAPON/OTHER WEAPON"
- Converted date/time columns into datetime format
Extracted key temporal features: Year, Month, Day of Week, and Hour
- Ensured data consistency across all categorical and numerical fields

**2. Exploratory Data Analysis (EDA)**

- Temporal patterns (hourly, daily, monthly, yearly trends)
- Spatial distribution by area/division
- Victim demographic patterns (age, gender, descent)
- Crime type frequency and trends over time
- Heatmaps for hourly and weekday distribution

**3. Visualizations**

- Static charts and plots using Matplotlib and Seaborn
- Line, bar, and heatmap visualizations for Crimes by area, Crimes by time of day, Crimes by demographic group, and more.

**4. Insights & Findings**

- Top neighborhoods: Central, Southwest, and 77th Street divisions show the highest crime frequencies.

- Most common crime types: Identity Theft, Simple Assault, and Burglary from Vehicle.

- Temporal trends: Crimes peak between 12:00–22:00, especially in summer months (May–August).

- Demographics: Young adults (19–45) form the majority of victims; gender distribution is nearly equal.

- Crime status: 82.8% of cases remain under investigation; only 7.2% resulted in arrests.

---

## 📌 How to Run

1. **Clone this project**

`git clone https://github.com/Cyber-Trinity/Data-Analysis.git`

`cd Data-Analysis/Investigating netflix Movies`

2. **Install dependencies**

`pip install -r requirements.txt`


3. **Run analysis notebooks**

Open notebook.ipynb in Jupyter Notebook or VS Code

---

## 📑 Report

A detailed project report is included as [Report_Investigating_Netflix.pdf](https://github.com/Cyber-Trinity/Data-Analysis/blob/main/Crime%20in%20Los%20Angeles/Report_Crime_Analysis.pdf)

It contains methodology, visualizations, findings, and key insights.

---

## ⚡ Notes

- Raw datasets are not included

- Code and notebooks are reproducible with sample data.