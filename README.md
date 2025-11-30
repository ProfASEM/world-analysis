

🌍 World Data Analysis Project

This project demonstrates a complete end-to-end data analysis workflow, starting from collecting raw data, cleaning it using Python, preparing it with SQL, and finally building an interactive Power BI dashboard for insights and storytelling.
It simulates a real-world BI project by integrating data from multiple sources and overcoming common data challenges.

> Note: Although the dataset is clean and well-structured, it is not fully up-to-date, and this project should be considered a training simulation designed to practice real analytical workflows.




---

🎯 Project Objectives

Collect, explore, and clean data from multiple sources.

Handle missing values, inconsistent formatting, and type issues.

Perform descriptive and exploratory data analysis.

Use Python, Pandas, SQL for data preparation.

Build relationships and a data model in Power BI.

Design interactive dashboards for insights and storytelling.



---

🛠 Tools & Technologies

Python (Pandas, NumPy)

Jupyter Notebook

SQL

Power BI

Web Scraping (when needed)



---

📂 Project Structure

|-- notebooks/
|     └── data_cleaning_and_analysis.ipynb
|-- data/
|     ├── raw/
|     └── cleaned/
|-- dashboard/
|     └── world_data_report.pbix
|-- README.md


---

🧹 Data Cleaning Steps

Identifying missing values and deciding how to handle them.

Fixing inconsistent formatting (text, numbers, dates).

Converting units (e.g., GDP values).

Removing duplicates.

Standardizing key fields for merging (country names/codes).

Merging datasets from different sources.

Exporting final cleaned dataset.



---

🔍 Exploratory Data Analysis

Performed using Python:

Summary statistics

Distribution analysis

Correlation analysis

Outlier detection

Feature comparisons


> Most visualizations were later implemented in Power BI for better presentation.




---

📊 Power BI Dashboard

Includes:

Global KPIs (Population, GDP, Growth Rate, etc.)

Top and bottom countries by key metrics

GDP and Life Expectancy trends

Language distributions

HDI world map

Correlation matrix

Country-level detailed report page

A mobile-friendly layout for phone viewing


> Dashboard file available in: dashboard/world_data_report.pbix
(Add your link here)




---

⚙️ Challenges & Solutions

1️⃣ Integrating Data from Multiple Sources

Challenge: Data came from different formats, structures, and naming conventions.
Solution:

Built a Power BI data model using cleaned keys.

Standardized country names/codes using Python.

Validated joins using SQL before import.



---

2️⃣ Importing SQL Data into Power BI

Challenge: Importing SQL tables caused encoding and datatype issues.
Solution:

Cleaned SQL output in Python first.

Reassigned column types in Power BI (Power Query → Transform Data).

Split large SQL tables into smaller structured ones.



---

3️⃣ GDP Column Contained Textual Values

Examples:
$3.5 trillion, $850B, 1.2 billion

Solution:

Built a custom Python function to convert all textual GDP units into numeric values.

Applied final validation in Power BI with Transform Data.


This allowed correct calculations, correlations, and rankings.


---

4️⃣ Visual Design and Layout Challenges

Challenge: Achieving a clean, modern layout with balanced visuals.
Solution:

Improved visual formatting, colors, spacing, and alignment.

Rebuilt charts from scratch when needed.

Designed a phone layout version separately.



---

5️⃣ Dataset Was Not Fully Up-to-Date

This project aims to simulate a realistic BI workflow rather than provide current global statistics.


---

💡 Key Insights

(Replace these with your actual insights if needed)

Countries with high GDP often show higher life expectancy.

Population distribution is highly uneven globally.

Some regions show consistent negative growth rates.

HDI strongly correlates with economic and educational indicators.



---

🚀 How to Run This Project

1. Clone or download this repository.


2. Open the Jupyter Notebook in the notebooks/ folder.


3. Run all cells to reproduce data cleaning and analysis.


4. Open the Power BI file to interact with the dashboard.




---

📬 Contact

If you'd like to connect:
LinkedIn: (Add your link here)


---

🎉 Thank you for exploring this project!
Feel free to reach out for discussion or collaboration.
