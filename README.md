IPL Analysis using Apache Spark on Databricks
Project Overview

This project performs exploratory data analysis (EDA) and insights on Indian Premier League (IPL) cricket data using Apache Spark on Databricks.
The goal is to showcase how big data technologies can be applied for sports analytics, such as player performance, match outcomes, and team statistics.

 Tech Stack

Databricks (Cloud-based Spark platform)

Apache Spark (PySpark)

Python (Pandas, Matplotlib, Seaborn for visualization)

IPL Dataset (matches & deliveries CSV files)

 Analysis Performed

Data Cleaning & Transformation (using PySpark DataFrames)

Top run scorers, wicket takers, and man of the match awards

Team-wise win percentage analysis

Toss decisions vs match results

Visualization of runs, wickets, strike rates, and economy rates

Year-wise performance trends of teams & players

 Dataset

matches.csv → Match-level details (teams, toss, results, venue, etc.)

deliveries.csv → Ball-by-ball details (runs, wickets, players, etc.)

(Dataset available on Kaggle - IPL Dataset
) or stored in Databricks FileStore.

 How to Run

Import dataset (matches.csv, deliveries.csv) into Databricks FileStore or DBFS.

Import the provided notebooks/scripts into Databricks.

Run the PySpark code step by step.

Visualize results using built-in Databricks display functions or export to Pandas/Matplotlib.

Sample Insights

Most successful team across IPL seasons.

Top run scorers and strike rates of players.

 Best bowlers by wickets and economy.

 Toss impact on match results.

 Future Scope

Build dashboards using Databricks SQL or Power BI/Tableau.

Real-time streaming analytics using Spark Structured Streaming.

Store and query IPL data in a data lake with Delta Lake.
