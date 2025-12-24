# Baku Real Estate Market Analysis (2023)

## 📌 Project Overview
This project analyzes the **Baku real estate market** using real estate listings data based on **Bina.az**.  
The focus of the project is **data cleaning, transformation, and visualization** of a real-world dataset.

The final result is an **interactive Power BI dashboard** presenting key market insights.

---

## 📊 Data Source
- Dataset taken from **Kaggle**
- Original data was **scraped from Bina.az by the dataset author**
- Web scraping was **not performed by me**
- Dataset was used as **raw input for analysis**

---

## 🧹 Data Cleaning & Transformation (SQLite)
All data cleaning and transformation were performed using **SQLite (SQL)**:

- Removed **duplicates, errors, and invalid records**
- Fixed formatting issues and extra spaces
- Renamed existing columns and added **new calculated columns**
- Split columns containing multiple values  
  - Example: `5/12` →  
    - `apartment_floor`
    - `total_floors`
- Converted binary values:
  - `1 / 0` → `Yes / No`
- Standardized categorical values for consistency

This step ensured **clean, structured, and analysis-ready data**.

---

## 📈 Visualization & Analysis
- Data was imported into **Power BI** after cleaning
- Built interactive dashboards showing:
  - Average price by location
  - Relationship between price, area, and mortgage availability
  - Repair status and legal documentation distribution
  - Price trends by apartment floor

---

## 🛠 Tools & Technologies
- **Kaggle Dataset**
- **SQLite** (data cleaning & transformation)
- **Power BI** (visualization)

---

## ✅ Key Takeaway
This project demonstrates the ability to:
- Clean and transform **messy real-world data using SQL**
- Work with **SQLite databases**
- Build professional **Power BI dashboards** for data-driven insights

---

📍 *Data represents Baku real estate listings from 2023.*
