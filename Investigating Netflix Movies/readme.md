# Investigating Netflix Movies

![Netflix illustration](src/project-7.jpg)
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

- Data Standardization: Columns like date_added and release_year are converted to consistent datetime objects.

- Missing Value Handling: Missing entries in critical features like director and cast are imputed with an 'Unknown' placeholder to allow for comprehensive counting.

- Feature Engineering: The duration column is standardized to minutes (Movies) and seasons (TV Shows) for quantitative comparison.

**2. Exploratory Data Analysis (EDA)**

- Temporal Analysis: Examination of the content release year vs. addition year to determine acquisition lag.

- Geographical Concentration: Identification of top 10 content-producing countries and their specialization (Movies vs. TV Shows).

- Personnel Trends: Analysis of the most prolific directors and cast members to identify key partners.

- Content Characteristics: Distribution analysis of Movie Duration by Genre and the count of TV Show seasons.

**3. Visualizations**

- Time-Series Plots: Line plots comparing titles released versus titles added over time.
- Stacked Bar Charts: Visualization of the split between Movies and TV Shows across top countries.
- Bar Charts: Ranking of Top Directors, Top Cast, and median Movie Duration per genre.

**4. Insights & Findings**

- Geographical Strategy: The United States is the largest content producer. India shows a strong focus on Movies, while Japan and South Korea specialize heavily in TV Shows (Anime and K-Dramas).

- Content Acquisition: The majority of TV shows in the catalog are 1-Season titles, indicating a preference for mini-series, docuseries, or limited-run content.

- Personnel: The top cast list is dominated by Indian actors, confirming the massive volume of Bollywood content on the platform.

- Movie Formats: The median duration for most feature film genres (Action, Drama, Sci-Fi) consistently falls in the 107–112 minute range.

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

A detailed project report is included as [Report_Investigating_Netflix.pdf](https://github.com/Cyber-Trinity/Data-Analysis/blob/main/Investigating%20Netflix%20Movies/Report_Investigating_Netflix.pdf)

It contains methodology, visualizations, findings, and key insights.

---

## ⚡ Notes

- Raw datasets are not included

- Code and notebooks are reproducible with sample data.
