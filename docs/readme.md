# 🏏 IPL Data Analysis using Databricks Lakehouse

**Team Name:** DATA LOADING… PLEASE WAIT

---

## 📌 Project Overview

This project focuses on analyzing **Indian Premier League (IPL)** data using the **Databricks Lakehouse architecture**.
An end-to-end data pipeline is developed to process raw cricket data and generate meaningful insights for performance analysis and strategic decision-making.

---

## 🎯 Objectives

* Process large-scale IPL datasets efficiently
* Build a **Bronze → Silver → Gold** data pipeline
* Generate insights on players, matches, and venues
* Enable fast and scalable analytics using Databricks

---

## 🏗️ Architecture

The project follows a **multi-layered Lakehouse architecture**:

### 🔹 Bronze Layer

* Raw data ingestion (matches, deliveries, players)
* Stored as Delta tables with schema enforcement

### 🔹 Silver Layer

* Data cleaning and transformation
* Handling null values and removing duplicates
* Structured data ready for analysis

### 🔹 Gold Layer

* Aggregated and analytics-ready tables
* Optimized for reporting and insights

---

## 📊 Dataset Description

The dataset consists of:

* Match-level data (teams, winners, venues, seasons)
* Ball-by-ball data (runs, wickets, players)
* Player information

This dataset is chosen due to its **real-world, high-volume nature**, making it ideal for big data analytics and performance evaluation.

---

## ⚙️ Technologies Used

* Databricks
* PySpark
* Delta Lake
* SQL

---

## 🔍 Key Insights

* Identified **top-performing players** based on runs, wickets, and strike rate
* Analyzed **match-winning patterns** (chasing vs defending)
* Evaluated **toss impact** on match outcomes
* Discovered **high-scoring venues** and ground-specific advantages
* Calculated **Player Impact Score** for ranking players

---

## 🥇 Gold Layer Tables

* `gold.top_run_scorers`
* `gold.top_wicket_takers`
* `gold.strike_rate_analysis`
* `gold.toss_impact_individual_matches`
* `gold.venue_analysis`
* `gold.player_impact_score`
* `gold.top_batsman_per_season`

---

## 🚀 How to Run the Project

1. Upload the dataset to Databricks
2. Create Bronze layer tables
3. Transform data into Silver layer
4. Execute PySpark scripts to generate Gold tables
5. Use `display()` for visualization and analysis

---

## 👥 Team Members

* **Gudala Lakshmi Sri Naga Ganesh**
* **Bokka Teenanjali**
* **Gadiraju Sai Ramanajaneya Varma**
* **Vepuri Mohan Babu**

---

## 📌 Conclusion

This project demonstrates how a **Lakehouse architecture** can transform raw IPL data into actionable insights.
It enables **efficient data processing, scalable analytics, and improved decision-making**.

---
