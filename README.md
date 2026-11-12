# **Healthcare Appointment Analysis**

## **Project Overview**

This project analyzes patient appointment data to identify attendance patterns, cancellation trends, and no-show rates. The analysis provides insights to improve operational efficiency and support better appointment management.

## **Project Details**

- **Tools:** Microsoft Excel, Pivot Tables, Google Looker Studio
- **Dataset:** Healthcare Appointment Dataset
- **Total Records:** 200
- **Original Columns:** 7

## **Objectives**

- Identify patient appointment attendance and no-show rates.
- Analyze appointment status distribution.
- Examine appointment patterns across different visit reasons.
- Identify doctors with the highest appointment volumes.
- Compare appointment activity across different time periods.
- Generate recommendations to improve appointment management.

## **Analysis Process**

### **1. Data Overview & Validation**

Performed initial data exploration and validation to assess dataset completeness, consistency, and structure.

**Key Activities:**

- Reviewed dataset structure and column information.
- Checked for duplicate appointment records.
- Identified and checked missing values.
- Validated data types and data formats.
- Examined appointment status distribution.

### **2. Data Cleaning & Preparation**

Performed data cleaning and feature engineering to prepare the dataset for further analysis.

**Key Activities:**

- Removed duplicate records.
- Checked for missing values.
- Standardized date and time formats.
- Validated data types across relevant columns.
- Created additional analytical features:
  - Time Category
  - Month

### **3. Exploratory Data Analysis (EDA)**

Used Excel Pivot Tables to examine appointment patterns and patient attendance behavior.

**Business Questions:**

- What is the distribution of completed, cancelled, and no-show appointments?
- Which visit reasons have the highest appointment volumes?
- Which doctors handle the most appointments?
- How do appointment patterns differ between morning and afternoon?
- What is the overall patient no-show rate?

**Key Findings:**

- 52 appointments resulted in no-shows, representing a 26% no-show rate.
- Checkups recorded the highest appointment volume with 45 appointments.
- Doctor D005 handled the highest number of appointments, with 29 records.
- Afternoon appointments accounted for 125 records, compared to 75 morning appointments.

### **4. Healthcare Appointment Dashboard**

Developed an interactive dashboard using Google Looker Studio to visualize appointment performance, attendance patterns, and no-show trends.

**Dashboard Metrics:**

- Total Appointments: 200
- Completed Appointments: 46
- Cancelled Appointments: 51
- No-Show Appointments: 52
- No-Show Rate: 26%

**Key Analysis:**

- Appointment Status Distribution
- Appointments by Visit Reason
- Appointments by Doctor
- Appointment Trends by Month
- Appointment Distribution by Time Category
- No-Show Rate Analysis

**Interactive Dashboard:**

[**View Live Dashboard – Google Looker Studio**](https://datastudio.google.com/reporting/8b1a6bb6-43d0-4102-9ef3-cbbb7d0487a0)

## **Key Business Recommendations**

- Implement appointment reminders to reduce patient no-shows.
- Review scheduling patterns to improve appointment attendance.
- Monitor doctors' appointment workloads to support better scheduling.
- Evaluate cancellation patterns to improve resource allocation.
- Use appointment trends to support more efficient healthcare operations.

## **Excel Skills Applied**

- Data Exploration
- Data Cleaning & Preparation
- Data Validation
- Data Standardization
- Feature Engineering
- Pivot Tables
- Data Segmentation
- No-Show Rate Calculation
- Exploratory Data Analysis (EDA)
- Dashboard Development
- Data Visualization
- Business Insights & Recommendations

## **Project Files**

- `healthcare_appointment_analysis.xlsx` – Excel file containing data cleaning, feature creation, and exploratory data analysis.
- `healthcare_appointment_dashboard.jpg` – Dashboard preview.
- `README.md` – Project documentation.

## **Conclusion**

The analysis identified appointment attendance patterns, no-show rates, and differences in appointment volumes across doctors, visit reasons, and time periods. These findings provide insights that can help improve appointment scheduling and healthcare operational efficiency.
