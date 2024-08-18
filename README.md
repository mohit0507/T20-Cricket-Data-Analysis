# T20-Cricket-Data-Analysis

## Project Overview

This project involves creating an end-to-end cricket data analytics solution designed to analyze and visualize T20 World Cup 2022 data. The objective is to select the best 11 cricket players to form a team based on certain criteria. The project utilizes CSV files, Power BI, and data modeling techniques to derive actionable insights and support decision-making in team selection.

## Problem Statement

In the realm of analytics, making informed decisions based on extensive data can be challenging. Traditional methods may not effectively analyze complex datasets or provide interactive insights. This project addresses these challenges by developing an interactive dashboard in Power BI that allows users to explore, filter, and visualize cricket data dynamically. This facilitates better decision-making, particularly in selecting a well-balanced and high-performing cricket team.

## Data Sources

- **Dataset**: A collection of CSV files containing detailed match results, batting and bowling scorecards, and player-specific information is provided in the project repository, formatted as CSV files for easy import into Power BI.

## Exploratory Data Analysis (EDA)

EDA was conducted to address the following key questions:

1. **What are the overall performance trends of players?**
2. **Which players excel in specific roles?**
3. **What is the ideal team for the final 11?**

## Steps Followed

## Data Collection

CSV files containing match details, player statistics, and other relevant information were made from the data in ESPN Cric info website. The data was stored in the following csv files:

- Match results  (dim_match_summary.csv)
- Batting summaries (dim_bating_summary.csv)
- Bowling summaries (dim_bowling_summary.csv)
- Player-specific details (dim_players.csv)

## Data Transformation (Power BI)

### Importing Data

The CSV files were imported into Power BI using the "Get Data" option.

### Data Cleaning

Power Query was used to clean and transform the data. This involved:

- Renaming columns
- Removing duplicates
- Handling null values
- Creating new calculated columns as per requirement

### Fact and Dimension Tables

Fact tables and dimension tables were established by linking corresponding columns.

## Data Modeling

- Relationships were created between the tables to enable comprehensive data analysis.
- Calculated columns and measures were created using DAX (Data Analysis Expressions) for detailed insights.

## Dashboard Creation

Multiple dashboards were built in Power BI to visualize data and assist in player selection. Visuals include:

- Bar charts for total runs
- Line charts for strike rates, batting averages,bowling averages,economy,balls faced,boundary percentage,dot ball percentage 
- Filters for selecting players based on specific criteria.
- Enabled Page Navigation to browse through the dashboards.
- Enabled Tooltips to display detailed information when hovered over the graphs.

The final dashboard allowed for the selection of the top 11 players based on data-driven insights.

## Player Selection

The final eleven were selected using insights generated from the dashboards. Parameters such as batting averages, strike rates, and bowling economy rates were considered.

## Improving the Dashboard

The dashboard's look and feel were enhanced by applying conditional formatting, sorting, and organizing data into a user-friendly format.

## Results/Findings

1. **Enhanced Data Integrity**:
   - Data cleaning and structuring in Power BI improved the accuracy of the analysis and ensured reliable insights.

2. **Insights into Player Performance**:
   - Visualizations revealed various performance trends such as strike rates, batting averages,bowling averages,economy,balls faced,boundary percentage,dot ball percentage.

3. **Optimal Team Selection**:
   - Analysis of various metrics led to the selection of the best 11 players, balancing the team with a mix of specialists and all-rounders.

4. **Dynamic Exploration**:
   - The interactive features of the dashboard allowed for in-depth exploration of player statistics, enhancing decision-making.

5. **Improved User Experience**:
   - Customization of the dashboard's design resulted in a user-friendly interface, making the data accessible and understandable.

## Screenshots

![Dashboard](https://github.com/user-attachments/assets/a79e11cc-68a6-4422-970b-34f7cfdb6ab0)

