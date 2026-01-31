# Innomatics_Research_Hackathon
# Food Delivery Data Analysis – Hackathon Submission

## 📌 Project Overview
This project presents an end-to-end data analysis solution for a food delivery platform.  
The objective is to combine data from multiple real-world formats (CSV, JSON, SQL), create a unified dataset, and answer analytical questions using **SQL queries executable in Google Colab**.

The notebook demonstrates data ingestion, integration, and analysis while ensuring correctness, reproducibility, and clarity.

---

## 📂 Datasets Used
The following datasets were provided as part of the hackathon:

- **orders.csv** – Transactional order-level data  
- **users.json** – User master data (city, membership type)  
- **restaurants.sql** – Restaurant master data (cuisine, rating)

These datasets were merged using **LEFT JOINs** to ensure no order records were lost.

---

## 🧱 Final Dataset
After merging all three datasets, a single dataset was created:

- **final_food_delivery_dataset.csv**

This dataset is treated as the **single source of truth** for all analysis, MCQs, numerical questions, and fill-in-the-blanks.

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- SQLite (in-memory, for SQL execution)  
- Google Colab  
- Jupyter Notebook  

---

## 🗄️ SQL Execution in Google Colab
To make SQL queries runnable in Google Colab:
- The final dataset is loaded into an **in-memory SQLite database**
- All analytical questions are answered using **pure SQL queries**
- Running each SQL cell directly returns the required answer

---

## 📊 Analysis Covered
The notebook answers the following using SQL:
- Multiple Choice Questions (MCQs)
- Numerical questions
- Fill-in-the-blank questions
