# 🎬 Movie Data ETL Pipeline using Talend Open Studio

## 📖 Overview

This project demonstrates an end-to-end **ETL (Extract, Transform, Load) pipeline** built using Talend Open Studio.

The pipeline processes multiple movie datasets (Adventure, Comedy, Action, Drama, etc.), performs data cleaning and transformation, and loads the data into a structured format for analysis.

---

## 🎯 Objectives

* Extract data from multiple Excel/CSV files
* Clean and preprocess raw data
* Handle missing values and duplicates
* Perform data transformation
* Load processed data for analysis

---

## 🛠️ Tech Stack

* Talend Open Studio
* SQL (PostgreSQL / MySQL)
* Excel / CSV
* Power BI (optional)

---

## 🔄 ETL Pipeline Architecture

Multiple Excel Files → Talend ETL → Data Cleaning → Transformation → Output File / Database

---

## ⚙️ ETL Workflow

### 🔹 Extract

* Source: Multiple Excel files (Adventure, Comedy, Action, etc.)
* Component: tFileInputDelimited

---

### 🔹 Transform

* Clean missing values
* Remove duplicates
* Standardize data
* Create new fields

Example transformation:

rating_category:

* High → rating > 7
* Medium → rating > 5
* Low → rating <= 5

---

### 🔹 Load

* Output file: Clean dataset (out.xlsx)
* Component: tFileOutputDelimited

---

## 📊 Key Insights

* Identified top-rated movies
* Analyzed distribution across genres
* Calculated average ratings
* Combined multiple datasets into a unified structure

---

## 📸 Screenshots

### 🔹 Talend Job Design

(Add screenshot here)

### 🔹 tMap Transformation

(Add screenshot here)

### 🔹 Output Data

(Add screenshot here)

---

## 📂 Project Structure

movie-etl-talend/
│
├── talend_job/
│   ├── process/
│   └── metadata/
│
├── dataset/
│   ├── Adventure.xlsx
│   ├── Comedy.xlsx
│   ├── Action.xlsx
│   └── ...
│
├── output/
│   └── out.xlsx
│
├── screenshots/
│
└── README.md

---

## ▶️ How to Run

1. Open Talend Open Studio
2. Import project
3. Load dataset files
4. Configure output path
5. Run the job

---

## 💡 Key Learnings

* Built ETL pipeline using Talend Open Studio
* Worked with multiple data sources
* Performed data transformation and cleaning
* Applied real-world data engineering workflow

---

## 🚀 Future Improvements

* Add Power BI dashboard
* Automate ETL pipeline scheduling
* Move to cloud-based ELT architecture
* Integrate with data warehouse

---
