# 🧬 COVID-19 Vaccination Data Analysis & Processing  

## 📋 **Project Overview**  
This project focuses on **analyzing and processing COVID-19 vaccination data** to uncover key insights such as **gender-based trends**, **age group statistics**, and **overall vaccination progress**.  
The main goal is to clean, process, visualize, and convert the vaccination dataset for further use in analytics and research.

---

## 🎯 **Objective**  
- Load and explore vaccination data from Excel files.  
- Clean and preprocess the dataset to remove inconsistencies.  
- Generate visualizations highlighting vaccination patterns.  
- Export the processed data into CSV format for seamless usage.

---

## ⚙️ **Key Steps & Processes**

### 🔹 **1. Data Import & Exploration**  
- Imported the dataset using **Pandas** from an Excel file.  
- Conducted initial data exploration: checked columns, data types, and null values.  
- Identified redundant and inconsistent data for cleaning.

### 🔹 **2. Data Cleaning**  
- Removed unnecessary columns such as `AEFI` and unused age-specific dose columns.  
- Resolved column name mismatches (e.g., corrected `"SputniV (Doses Administered)"` to `"Sputnik V (Doses Administered)"`).  
- Handled missing data and standardized all column names for smooth analysis.

### 🔹 **3. Data Transformation**  
- Aggregated **gender-specific** and **age-specific** vaccination data.  
- Renamed columns for clarity and consistency.  
- Converted the cleaned and transformed data into **CSV format** for portability.

### 🔹 **4. Data Visualization**  
- Created a **gender-based pie chart** showing male vs female vaccination ratios.  
- Used **Plotly** to build **interactive and visually appealing charts**.

---

## 🧩 **Challenges & Solutions**

| Challenge | Solution |
|------------|-----------|
| **FileNotFoundError** due to incorrect paths | Verified and updated file path references. |
| **Mismatched column names** | Renamed columns after inspection for consistency. |
| **Null values in numeric fields** | Replaced missing values with appropriate defaults to enable calculations. |

---

## 💾 **File Conversion**
After the data analysis:
- The cleaned dataset was exported as a **CSV file** using Pandas.  
- Ensured compatibility with external analytics tools and data pipelines.

---

## 🧠 **Technologies Used**

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python |
| **Libraries** | Pandas, Plotly, OS |
| **Data Formats** | Excel (.xlsx), CSV (.csv) |

---

## 📊 **Results & Insights**
✅ Cleaned and structured vaccination dataset ready for advanced analysis.  
✅ Interactive **gender-based visualizations** revealing vaccination distribution.  
✅ Exported **CSV file** for future integrations and analysis.  

---

## 🚀 **Future Scope**
- 🔍 Extend analysis to include **geographical and time-series trends**.  
- 🤖 Apply **machine learning models** to predict vaccination rates.  
- ⚡ Automate the entire **data cleaning and processing pipeline** for similar datasets.

---

## 🧾 **Conclusion**
This project demonstrates a **complete data analysis workflow** — from cleaning raw Excel data to creating insights-driven visualizations.  
It effectively handles real-world data challenges like missing values, file inconsistencies, and formatting issues, while showcasing the power of **Python for data analytics**.

---

## 👨‍💻 **Author**
**Malik Hammad Farooq**  
📂 **GitHub:** [@hammadfarooq-ai](https://github.com/hammadfarooq-ai)

---

## 🏷️ **Badges**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-FF6F00?style=for-the-badge)
![CSV](https://img.shields.io/badge/CSV-43A047?style=for-the-badge&logo=files&logoColor=white)
