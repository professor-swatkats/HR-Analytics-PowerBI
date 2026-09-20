# HR Analytics Dashboard – Power BI

## 📊 Project Overview

This project is an **HR Analytics Dashboard** developed using Microsoft Power BI to analyze workforce information and provide a clear overview of employee demographics, hiring trends, workforce distribution, and employment status.

The project was created as a practical HR Analytics project to demonstrate skills in **Power BI, Power Query, DAX, data modeling, and business-focused data visualization**.

---

## 🎯 Project Objective

The main objectives of this project are to:

* Analyze overall workforce size and employment status
* Understand employee demographics
* Analyze hiring trends over time
* Compare remote and headquarters employees
* Analyze workforce distribution across departments and locations
* Identify patterns that can support HR decision-making

---

## 🗂️ Dataset

The dataset contains **22,214 employee records** with information including:

* Employee ID
* First Name
* Last Name
* Birth Date
* Age
* Gender
* Race
* Department
* Job Title
* Location
* Hire Date
* Termination Date
* City
* State

The dataset is used for **learning and portfolio demonstration purposes**.

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                                                |
| --------------- | ------------------------------------------------------ |
| **Power BI**    | Dashboard development, data modeling and visualization |
| **Power Query** | Data cleaning and transformation                       |
| **DAX**         | Measures and KPI calculations                          |
| **MySQL**       | Data storage and connection to Power BI                |
| **Excel / CSV** | Source data preparation                                |

> **Note:** MySQL was used primarily to store the dataset and establish the connection to Power BI. SQL was not used for the project's analytical calculations.

---

## 🔄 Data Preparation

The data preparation process included:

* Checking data types
* Converting date fields to proper date format
* Cleaning the termination date field
* Removing unnecessary time information from termination dates
* Checking for duplicate employee IDs
* Checking missing values
* Validating age and workforce attributes
* Preparing the data for analysis in Power BI

---

## 📐 Data Modeling

The Power BI model was developed to support HR analysis using:

* Employee fact data
* Date dimension
* Relationships between employee and date data
* DAX measures for KPIs and analysis

The model was designed with a focus on maintaining a simple and understandable structure suitable for HR reporting.

---

## 📈 Dashboard Analysis

### 1. Workforce Overview

Key metrics include:

* Total Employees
* Active Employees
* Terminated Employees
* Active %
* Termination %
* Average Age
* Remote Employees
* Remote %
* Headquarters Employees
* Headquarters %

### 2. Hiring Analysis

The dashboard analyzes:

* Total Hires
* Hiring Trend by Year
* Hires This Year
* Previous Year Hires
* Year-over-Year Hiring Growth

### 3. Workforce Demographics

The analysis includes:

* Gender Distribution
* Age Analysis
* Race Distribution
* Department Distribution
* Job Title Analysis

### 4. Location Analysis

The dashboard provides workforce distribution by:

* Headquarters vs Remote
* State
* City

---

## 💡 Key Business Questions

This dashboard is designed to answer questions such as:

* How large is the current workforce?
* How many employees are active or terminated?
* How has hiring changed over time?
* What is the average employee age?
* How is the workforce distributed across departments?
* What is the gender and racial composition of the workforce?
* How many employees work remotely?
* Which states and cities have the largest workforce?

---

## 📷 Dashboard Preview

<img width="1056" height="742" alt="image" src="https://github.com/user-attachments/assets/f530ed36-6eab-47a9-bd36-524344c03518" />

---

## 📁 Project Structure

```text
HR-Analytics-PowerBI/
│
├── README.md
│
├── Screenshots/
│   └── dashboard.png
│
├── Data/
│   └── Raw file.xlsx
│
└── Documentation/
    └── hr-theme.json
    └── PRDA_03_HR_Analytics_Final.pptx
    └── PRDA_03_HR_Analytics_Report.docx
```

---

## 🚀 Skills Demonstrated

* Power BI
* Power Query
* DAX
* Data Cleaning
* Data Modeling
* KPI Development
* HR Analytics
* Data Visualization
* Business Analysis
* Dashboard Design

---

## 📌 Project Status

**Completed – Portfolio Version**

This project is being maintained as part of my data analytics portfolio and may be enhanced with additional DAX measures, analysis, and visualizations over time.
