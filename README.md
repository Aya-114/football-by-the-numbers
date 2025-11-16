FIFA 21 Player Analysis
Overview

This project explores the FIFA 21 Complete Player Dataset, containing 18,944 players and 106 attributes, to uncover insights about player performance, talent distribution, and club value. The analysis was performed by our team, focusing on data cleaning, exploratory data analysis (EDA), and visualization.

Goals

The project aims to answer three main questions:

Which countries produce the best players?

How are age, potential, and market value related?

Which clubs have the most valuable squads?

Dataset

Source: FIFA 21 Complete Player Dataset on Kaggle

Size: 18,944 players × 106 columns

Key columns include: age, overall, potential, value_eur, wage_eur, nationality, club_name, player_positions, pace, shooting, passing, etc.

Data Cleaning & Wrangling

The raw dataset required significant preprocessing:

Converted value_eur and wage_eur from strings (e.g., "€120K") to numerical floats

Handled missing values: some columns had ~16,000 missing values, others ~1,000; decisions were made to delete or impute depending on relevance

Removed outliers in age and overall

Standardized player positions and nationality names

Detected and removed duplicate player records

Exploratory Data Analysis (EDA)

Top countries by player quality:

Brazil, Czech Republic, Portugal, and Croatia led in average overall rating.

Age, potential, and market value relationships:

Younger players with high potential tend to have higher market values.

Veteran players’ value depends on performance and market demand.

Most valuable squads by club:

Some famous clubs weren’t as valuable as expected.

Lesser-known clubs sometimes dominated the total squad value rankings.

Visualizations

Bar charts: Top countries by average overall rating, Top clubs by total squad value

Scatter plots: Age vs. potential, with overall as color and market value as size

Correlation heatmaps: Showed relationships between age, overall, potential, value_eur, and wage_eur

Key Insights

Data can challenge common assumptions in football.

Market value often favors younger players with high potential.

Club popularity doesn’t always reflect squad value.

Technologies Used

Python: Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook for interactive analysis and visualizations
