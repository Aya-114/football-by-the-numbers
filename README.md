FIFA 21 Players Data Analysis
-
An exploratory data analysis (EDA) project using the FIFA 21 Complete Player Dataset to uncover insights about player performance, talent distribution, market value, and club squad strength.

📌 Project Overview
-
This project analyzes 18,944 players and 106 attributes from the FIFA 21 dataset.
Our team explored player performance trends, relationships between key features, and squad values across top clubs.

🧹 Data Cleaning & Wrangling

Before analysis, the dataset required extensive preprocessing:

✔ Missing Values

Some columns contained 16,000+ missing values, others around 1,000.
We evaluated whether to remove or impute them depending on column importance.

✔ Converting Financial Data

Converted value_eur and wage_eur from string formats like "€120K" or "€90M" into numerical float values for proper analysis.

✔ Removing Outliers

Outliers in Age and Overall Rating were detected and removed to improve the reliability of visualizations.

✔ Standardizing Categories

Unified position labels

Standardized nation names

✔ Removing Duplicate Players

Identified and removed duplicate player records based on unique identifiers.

📊 Key Questions Explored
-
1️⃣ Which countries produce the best players (based on Overall rating)?

We grouped players by nationality and found the Top 10 countries by average overall rating.

2️⃣ What is the relationship between Age, Potential, and Market Value?

Using scatter plots & correlation matrices, we uncovered trends between development and player valuation.

3️⃣ Which clubs have the most valuable squads?

Aggregated player market values to rank clubs by total squad worth.

📈 Visualizations Included

Top 10 countries by average overall (Bar Chart)

Age vs Potential with Market Value (Gradient Scatter Plot)

Correlation Matrix of key variables (Heatmap)

Top 10 most valuable squads (Bar Chart)

All plots are available in the notebook.

🛠 Technologies Used
-
Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook


⭐ If you find this project useful, feel free to star the repo!
