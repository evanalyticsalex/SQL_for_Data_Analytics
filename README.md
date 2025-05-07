# SQL_for_Data_Analytics

# Table of Contents

## 0. Intro
- [Import Libraries & Database - (Open in Colab)]()
- [Colab Notebooks - (Open in Colab)]()
- [Database Overview - (Open in Colab)]()

## 1. Pivot With Case Statements
- [Basic Aggregation - (Open in Colab)]()
- [Statistical Aggregations - (Open in Colab)]()
- [Advanced Segmentation - (Open in Colab)]()

## 2. Date Time
- [Date Format - (Open in Colab)]()
- [Date Filtering - (Open in Colab)]()
- [Date Differences - (Open in Colab)]()

## 3. Windows Functions
- [Syntax - (Open in Colab)]()
- [Aggregation - (Open in Colab)]()
- [Ranking - (Open in Colab)]()
- [Lag Lead - (Open in Colab)]()
- [Frame Clause - (Open in Colab)]()

## 4. Local DB Setup
- [Install PostgreSQL - (Open in Colab)]()
- [Install DBeaver - (Open in Colab)]()

## 5. Views
- [View Intro - (Open in Colab)]()
- [Project Cohort Revenue - (Open in Colab)]()
- [Install VSCode - (Open in Colab)]()

## 6. Data Cleaning
- [Conditional Handle Nulls - (Open in Colab)]()
- [String Formatting - (Open in Colab)]()
- [Project Customer Segmentation - (Open in Colab)]()

## 7. Query Optimization
- [Explain Intro - (Open in Colab)]()
- [Optimization Techniques - (Open in Colab)]()
- [Project Customer Retention - (Open in Colab)]()

---

# How to Run SQL Files

## Method 1️⃣: Run in Google Colab
_Recommended to start the course._

**Prerequisites:**
- Google Account

**Steps:**
1. Click the "Open in Colab" button at the top of any notebook.
2. Run all cells in the notebook.

---

## Method 2️⃣: Run Database Locally w/ PGAdmin
_Second half of course uses this method._

**Prerequisites:**
- PostgreSQL Installed  
- pgAdmin Installed  

**Steps:**
1. Download the Contoso database.  
2. Open pgAdmin 4.  
3. In Object Explorer, connect to your PostgreSQL server.  
4. Right-click on "Databases" > "Create" > "Database...".  
5. Enter `contoso_100k` for "Database" and click "Save".  
6. In Object Explorer, right-click on the `contoso_100k` database > "PSQL Tool".  
7. In the PSQL Tools Window, enter:

   ```sql
   \i '/Users/lukebarousse/Desktop/contoso_100k.sql'
