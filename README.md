# Cricket-player-analysis
# 🏏 T20 World Cup – Best Playing 11

## 📌 Project Overview

A data analytics project focused on identifying the **Best Playing 11** from T20 World Cup player performance data using data-driven analysis.

The project analyzes batting, bowling, match results, and player information to compare player performances and build a balanced team.

---

## 🎯 Project Objectives

- Analyze player performance using statistical metrics
- Compare batting and bowling performances
- Identify the strongest players across different roles
- Build a balanced Best Playing 11
- Create an interactive Power BI dashboard for player comparison
- Demonstrate an end-to-end data analytics workflow

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **JSON**
- **Power BI**
- **DAX**
- **Microsoft Excel**

---

## 🔄 Project Workflow

```text
Raw JSON Files
      ↓
Python & Pandas
      ↓
Data Cleaning & Preparation
      ↓
JSON → Structured CSV Files
      ↓
Power BI
      ↓
Data Transformation & Data Modeling
      ↓
DAX Measures
      ↓
Interactive Dashboard
      ↓
Player Performance Analysis
      ↓
Best Playing 11
🐍 Data Preparation Using Python

The raw cricket data was provided in JSON format.

Python and Pandas were used to:

Read and process JSON files
Convert JSON data into structured DataFrames
Prepare match results data
Create match IDs for connecting datasets
Prepare batting summary data
Create an Out/Notout column from dismissal information
Prepare bowling summary data
Prepare player information data
Remove unnecessary columns
Export cleaned datasets into CSV files
Generated Datasets
matches_summary.csv
Batting.csv
Bowling.csv
player_info.csv
📊 Power BI Transformation

The cleaned CSV files were imported into Power BI.

Power BI was used for:

Data transformation
Data modeling
Creating relationships between datasets
Preparing player performance data
Creating parameters for player analysis
Building calculated metrics
🧮 DAX Measures

DAX measures were created to calculate and compare important player performance metrics.

These measures were used to evaluate players based on their:

Batting performance
Bowling performance
Runs
Strike Rate
Wickets
Economy
Other performance metrics
📈 Power BI Dashboard

An interactive Power BI dashboard was created to compare players across multiple performance dimensions.

Dashboard Features
Player comparison
Batting performance analysis
Bowling performance analysis
Player role analysis
Performance filters
Dynamic player selection
Comparative visualizations
Performance trends
Data-driven team selection
🏆 Best Playing 11

Based on the analysis, the final Best Playing 11 was selected by considering different player roles and performance metrics.

Openers
Jos Buttler (WK)
Rilee Rossouw
Middle Order
Alex Hales
Virat Kohli
Suryakumar Yadav
Finishers
Glenn Phillips
Marcus Stoinis
All-Rounders
Hardik Pandya
Rashid Khan
Bowlers
Sam Curran
Anrich Nortje
💡 Key Outcome

The project demonstrates how raw cricket data can be transformed into meaningful performance insights and used to make data-driven team selection decisions instead of relying purely on subjective assumptions.

📌 Key Skills Demonstrated
Data Cleaning
Data Transformation
Python
Pandas
JSON Data Processing
Power BI
Data Modeling
DAX
Data Visualization
Exploratory Data Analysis
Player Performance Analysis
Data-Driven Decision Making
