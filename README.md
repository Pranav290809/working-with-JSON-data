# 🧹 JSON Data Cleaning & Analysis with Python

A hands-on Python project that simulates real-world messy data
and cleans it from scratch — no pandas, just pure Python logic.

---

## 📌 Project Overview

Real-world data is rarely clean.
This project simulates a messy customer feedback dataset in JSON format
and walks through the full process of:
- Loading raw JSON data
- Identifying data quality issues
- Cleaning and structuring the data
- Performing basic analysis
- Generating simple recommendations

---

## 🗂️ Project Structure
json-data-cleaning/
│
├── store_data.json # Raw messy dataset
├── thinking_data.ipynb # Main Jupyter notebook
└── README.md # You are here



---

## 🔍 What Made the Data Messy?

| Issue              | Example                        |
|--------------------|--------------------------------|
| Wrong data type    | rating = "four" instead of 4   |
| Missing fields     | age field completely absent    |
| Duplicate records  | Same user appearing twice      |
| Whitespace issues  | " Charlie" instead of "Charlie"|
| Inconsistent case  | "BAD EXPERIENCE " with spaces  |

