# 🏥 Hospital Management Analytics — Exploratory Data Analysis

## 📌 Project Overview

This project focuses on analyzing hospital management data using **Python and Exploratory Data Analysis (EDA)**.

The project combines multiple hospital-related datasets, performs data cleaning and preprocessing, handles missing and duplicate records, standardizes inconsistent values, integrates datasets, creates new analytical features, and generates healthcare-related KPIs and visualizations.

The main objective is to transform raw hospital data into a clean and structured dataset that can be used for **healthcare analytics and business reporting**.

---

## 🎯 Project Objectives

* Import and inspect multiple hospital datasets
* Clean and preprocess raw data
* Handle missing values and duplicate records
* Standardize inconsistent data
* Merge datasets into a unified analytical dataset
* Perform feature engineering
* Calculate healthcare business KPIs
* Perform Exploratory Data Analysis using visualizations
* Identify useful patterns and insights from hospital data

---

## 📂 Datasets

The project contains five datasets:

| Dataset    | Description                                |
| ---------- | ------------------------------------------ |
| Patients   | Patient demographic and health information |
| Admissions | Hospital admission and discharge details   |
| Doctors    | Doctor information and experience          |
| Hospitals  | Hospital details, ratings and bed capacity |
| Treatments | Disease, medicine and billing information  |

---

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook**

---

## 🧹 Data Cleaning & Preprocessing

The following steps were performed:

### Data Inspection

* Checked dataset dimensions
* Checked column names and data types
* Inspected missing values
* Checked duplicate records
* Verified unique values

### Missing Value Treatment

* Filled missing hospital ratings
* Filled missing recovery days
* Estimated missing discharge dates
* Filled missing bill amounts
* Filled missing age, height and weight values
* Filled missing diabetes and smoking status
* Filled missing doctor experience

### Data Quality

* Removed duplicate doctor records
* Converted admission and discharge dates into datetime format
* Corrected numerical data types
* Standardized gender values
* Corrected disease and medicine names
* Removed unwanted spaces
* Validated age, hospital ratings and recovery days

---

## 🔗 Data Integration

The **Admissions** and **Treatments** datasets were merged to create a unified analytical dataset for further analysis.

---

## ⚙️ Feature Engineering

Two new features were created:

* **Age Group**
* **BMI**

These features were used to analyze patient demographics and health-related patterns.

---

## 📊 Key Business KPIs

The project calculates several healthcare KPIs, including:

* Total Patients
* Total Hospitals
* Total Doctors
* Total Revenue
* Total Beds
* Average Bill Amount
* Average Patient Age
* Average Recovery Days
* Average BMI
* Average Hospital Rating
* Average Doctor Experience
* Average Daily Revenue
* Diabetes Rate
* Smoking Rate
* Healthy BMI Percentage
* Highest Billing Hospital
* Highest Revenue Department

---

## 📈 Exploratory Data Analysis

The following analyses and visualizations were performed:

* Patient Count by Disease
* Patient Distribution by Age Group
* Monthly Hospital Admissions
* Revenue by Hospital
* Gender Distribution of Patients
* Treatment Cost Distribution
* Recovery Days by Department
* Doctor Count by Department
* BMI Distribution
* Diabetes and Smoking Status Distribution

---

## 🔍 Key Insights

Based on the analysis:

* Total hospital revenue was approximately **₹63.8 Crore**.
* The average bill amount was approximately **₹1.3 Lakh**.
* The average patient age was **45 years**.
* Average recovery time was **16 days**.
* Doctors had an average experience of **20 years**.
* The average hospital rating was **4.2/5**.
* Average daily revenue per patient was approximately **₹13,248**.
* Average patient BMI was **29.7**.
* Approximately **67.4%** of patients had diabetes.
* Approximately **32.3%** of patients were smokers.
* Approximately **21.3%** of patients had a healthy BMI.
* **Hospital H06** generated the highest billing at approximately **₹86.49 Lakh**.
* The **ICU department** generated the highest revenue at approximately **₹98.29 Lakh**.

---

## 📁 Project Structure

```text
Hospital-Management-EDA/
│
├── data/
│   ├── patients.csv
│   ├── admissions.csv
│   ├── doctors.csv
│   ├── hospitals.csv
│   └── treatments.csv
│
├── Hospital_Management_EDA.ipynb
│
├── README.md
│
└── report/
    └── EDA_Report.pdf
```

---

## 🚀 Workflow

```text
Raw Datasets
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Data Cleaning
     ↓
Missing Value Treatment
     ↓
Duplicate Removal
     ↓
Data Standardization
     ↓
Data Integration
     ↓
Feature Engineering
     ↓
KPI Calculation
     ↓
Exploratory Data Analysis
     ↓
Business Insights
```

---

## 💡 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Preprocessing
* Missing Value Handling
* Duplicate Detection & Removal
* Data Standardization
* Data Integration
* Feature Engineering
* KPI Development
* Exploratory Data Analysis
* Data Visualization
* Business Insight Generation

---

## 📌 Conclusion

This project demonstrates an end-to-end **Exploratory Data Analysis workflow** on hospital management data, starting from raw datasets and progressing through data cleaning, integration, feature engineering, KPI development, visualization, and insight generation.

The analysis provides a structured view of **patients, hospitals, doctors, treatments, revenue, and healthcare-related metrics**.
