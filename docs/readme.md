
🏏 IPL Data Analysis using Databricks Lakehouse
Team: DATA LOADING… PLEASE WAIT
📌 Project Overview

This project focuses on analyzing Indian Premier League (IPL) data using the Databricks Lakehouse architecture.
We built an end-to-end data pipeline to process raw cricket data and generate meaningful insights for performance analysis and strategy building.

🎯 Objectives
Process large-scale IPL datasets efficiently
Build a Bronze → Silver → Gold data pipeline
Generate insights on players, matches, and venues
Enable fast and scalable analytics using Databricks
🏗️ Architecture

We implemented a multi-layered Lakehouse architecture:

Bronze Layer
Raw data ingestion (matches, deliveries, players)
Silver Layer
Data cleaning, transformation, and validation
Gold Layer
Aggregated tables for analytics and insights
📊 Dataset Description

The dataset includes:

Match-level data (teams, winners, venues, seasons)
Ball-by-ball data (runs, wickets, players)
Player information

This dataset was chosen because it provides real-world, high-volume sports data suitable for big data analytics.

⚙️ Technologies Used  :  Databricks,PySpark,Delta Lake,SQL
🔍 Key Insights
Identified top-performing players based on runs, wickets, and strike rate
Analyzed match-winning patterns (chasing vs defending)
Evaluated toss impact on match outcomes
Found high-scoring venues and ground advantages
Calculated Player Impact Score
🥇 Gold Layer Tables
gold.top_run_scorers
gold.top_wicket_takers
gold.strike_rate_analysis
gold.toss_impact_individual_matches
gold.venue_analysis
gold.player_impact_score
gold.top_batsman_per_season
🚀 How to Run the Project
Upload dataset to Databricks
Create Bronze tables
Transform data into Silver layer
Run PySpark scripts for Gold layer
Use display() for visualization
👥 Team Members
Member 1 GUDALA LAKSHMI SRI NAGA GANESH
Member 2 BOKKA TEENANJALI
Member 3 GADIRAJU SAI RAMANAJANEYA VARMA
Member 4 VEPURI MOHAN BABU
📌 Conclusion

This project demonstrates how a Lakehouse architecture can transform raw IPL data into actionable insights.
It enables faster analytics, better decision-making, and scalable data processing.
