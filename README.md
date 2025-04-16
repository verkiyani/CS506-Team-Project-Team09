# CS506-Team-Project-Team09

**Project Title:** IPL Match Data Analysis using Kaggle Dataset

**Submission 01 – Pandas DataFrame** - **Week04**

Overview - This module explores detailed IPL match data using Pandas, focusing on:

1. Understanding match outcomes

2. Team and player performance

3. Toss decisions and their impact

4. Match durations and margins of victory

It demonstrates core Pandas functionality, exploratory data analysis (EDA), and visualization to derive insights from historical IPL data.


**Dataset**: A single dataset containing comprehensive IPL match-level data (all_season_summary.csv)

Columns include team names, toss details, scores, captains, key players, venue, umpires, and more

**Concept	Usage Example:**

1. DataFrame operations	Data cleaning, column creation
2. apply()	Custom logic for extracting result types
3. groupby()	Aggregation by team and result type
4. assign()	Chaining transformations for win margins
5. value_counts()	Frequency of result types
6. merge() (optional)	Joining datasets if extending with player/team stats
7. datetime handling	Calculating match duration using start and end dates

**Visualizations Included:**

1. Chart Type	Insight Provided
2. Barplot	Match result type distribution (runs, wickets, tie, etc.)
3. Histogram	Duration of matches in days
4. Horizontal Barplot	Top 10 highest win margins by team (runs/wickets)
5. Horizontal Barplot	Average win margin per team for runs vs wickets
6. All plots are built using Seaborn with consistent styling for clarity.

**Insights Extracted:**

1. Teams winning by runs vs wickets
2. Most dominant teams based on victory margins
3. How often matches are tied or decided by narrow margins
4. Toss decisions and their impact on match results
5. Match delays based on multi-day durations

**Dependencies:**

1. Python 3.7+
2. Pandas
3. Matplotlib
4. Seaborn

**Install with:** pip install pandas matplotlib seaborn

**File Structure**
IPL-Pandas-Module
├── all_season_summary.csv           # Main dataset
├── CS506_TP01_Team09_Ashwin Akarsh Divakar Sara.ipynb     # Jupyter Notebook with full EDA
└── README.md                 # This file

**Contributors:**

Ashwin Paturi – Data Cleaning & Result Analysis

Akarsh Lakshmana – Visualizations & Toss Analysis

Divakar Reddy – Win Margin Computation & Team Insights

Sara Verkiyani – Match Duration & Documentation

