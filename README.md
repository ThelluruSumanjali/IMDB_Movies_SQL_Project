Here is a clean, professional **README description** you can upload to GitHub for your IMDB Movie Analytics project.
(You can copy-paste directly into your README.md.)

---

# 📊 IMDB Movie Analytics – SQL & Power BI Project

This project delivers an end-to-end data analysis workflow using **MySQL** for data extraction & processing and **Power BI** for interactive visualizations. The objective is to analyze the **IMDB Movies Dataset** to uncover insights about directors, movie performance, revenues, audience engagement, and industry patterns.

---

## 🔍 Project Overview

The project includes:

* Creating and preparing a MySQL database using `LOAD DATA LOCAL INFILE`.
* Cleaning, validating, and transforming movie and director data.
* Writing SQL queries to answer key analytical questions.
* Building a Power BI dashboard for rich visual exploration.
* Generating insights on movie popularity, profitability, directors’ performance, and yearly trends.

---

## 🗂️ Dataset Description

### **Directors Table**

Contains details such as:

* Director Name
* Director ID (unique)
* Gender (0/2 = Male, 1 = Female)
* Department

**Total Records:** 2349 directors

### **Movies Table**

Includes:

* Movie ID
* Title & Original Title
* Popularity
* Budget & Revenue
* Vote Average & Vote Count
* Overview & Tagline
* Director ID (mapped with Directors table)

**Total Records:** 47 movies

---

## ⚙️ Technology Stack

* **Database:** MySQL
* **Visualization:** Power BI Desktop
* **Languages:** SQL, DAX
* **Tools:** MySQL Workbench, Excel

---

## 🧹 Data Preparation Steps

* Imported data using SQL commands.
* Corrected data types, handled nulls, and verified relationships.
* Joined Movies & Directors tables for combined analysis.
* Prepared clean datasets for Power BI modeling.

---

## 🧠 SQL Analysis

Key analytical queries include:

* Most popular movies
* Highest revenue-generating directors
* Female directors count
* Movies released after 2000 with best ratings
* Directors who created the most movies
* Total movies in the dataset

---

## 📈 Power BI Dashboard Highlights

Visuals used:

* Card visuals (Total Directors, Total Movies, Revenue, Profit)
* Bar/Column charts (Top Revenue Movies, Popularity, Budget vs Revenue)
* Donut chart (Top Movies by Votes)
* Line chart (Movies released per year)
* Slicers for filtering by movie, year, and director

Custom DAX measures, such as **Profit** and **Profit %**, were created to analyze financial performance.

---
## 📊 Power BI Dashboard
<img width="795" height="481" alt="image" src="https://github.com/user-attachments/assets/abe487b9-6862-4faf-96e6-1572df7d1cf6" />
<img width="793" height="469" alt="image" src="https://github.com/user-attachments/assets/55de5cc9-e82e-4e06-ba10-9736f730b4e3" />


## 📑 Key Insights

* Popularity strongly correlates with revenue.
* James Cameron emerged as the most bankable director.
* Female director representation is significantly low.
* Some low-budget films achieved high profitability.
* Most movie activity occurred between 2010–2016.

---

## 🎯 Conclusion

This project demonstrates the complete analytics lifecycle—data loading, cleaning, SQL-based analysis, and Power BI dashboard creation. It offers valuable insights into movie trends, director performance, and audience engagement, showcasing how data analytics supports effective decision-making.

**© 2025 S. Asmita & T. Sumanjali — Created under Datamites. All Rights Reserved.**


