# Hospital_Dashboard# 🏥 Hospital Patient Visits & Mortality Analysis

## 📌 Project Overview

This project analyzes hospital patient visit records using **Microsoft Excel**, **Pivot Tables**, and **Data Visualization**.

The dataset contains **403 hospital visits** recorded throughout 2019. The analysis focuses on patient risk categories, outcomes, monthly mortality, and changes in the number of deaths over time.

The goal is to transform raw hospital records into meaningful insights that can help understand **mortality patterns and patient risk levels**.

---

## 📊 Dataset

The dataset contains four main columns:

| Column          | Description                               |
| --------------- | ----------------------------------------- |
| `Visit ID`      | Unique identifier for each hospital visit |
| `Check in Date` | Date of the patient's hospital visit      |
| `Risk Category` | Patient risk level: `High` or `Low`       |
| `Outcome`       | Patient outcome: `Live` or `Die`          |

### Dataset Size

* **Total Visits:** 403
* **Live Patients:** 334
* **Deaths:** 69
* **High-Risk Cases:** 182
* **Low-Risk Cases:** 221
* **Data Period:** January 2019 – December 2019

---

## 🎯 Project Objectives

The analysis answers the following business questions:

1. What is the total number of hospital cases?
2. What is the total number of deaths?
3. What are the percentages of deaths and surviving patients?
4. What is the percentage of high-risk vs. low-risk cases?
5. What is the monthly death rate compared with total visits?
6. How does the number of deaths change from month to month?
7. What is the monthly percentage change in deaths?
8. What is the cumulative number of deaths each month?
9. Are deaths more common among high-risk patients than low-risk patients?

---

## 📈 Key Results

### Overall Outcomes

| Metric         |     Result |
| -------------- | ---------: |
| Total Visits   |    **403** |
| Live Patients  |    **334** |
| Deaths         |     **69** |
| Survival Rate  | **82.88%** |
| Mortality Rate | **17.12%** |

### Risk Categories

| Risk Category | Cases | Percentage |
| ------------- | ----: | ---------: |
| High Risk     |   182 |     45.16% |
| Low Risk      |   221 |     54.84% |

### Deaths by Risk Category

| Risk Category | Deaths | Live |
| ------------- | -----: | ---: |
| High Risk     |     39 |  143 |
| Low Risk      |     30 |  191 |

The dataset contains **39 deaths among high-risk cases** and **30 deaths among low-risk cases**.

---

## 📅 Monthly Mortality Analysis

| Month     | Total Visits | Deaths | Death Rate | Cumulative Deaths |
| --------- | -----------: | -----: | ---------: | ----------------: |
| January   |           62 |      8 |     12.90% |                 8 |
| February  |           46 |      9 |     19.57% |                17 |
| March     |           31 |      6 |     19.35% |                23 |
| April     |           30 |      5 |     16.67% |                28 |
| May       |           31 |      5 |     16.13% |                33 |
| June      |           30 |      6 |     20.00% |                39 |
| July      |           31 |      4 |     12.90% |                43 |
| August    |           31 |      9 |     29.03% |                52 |
| September |           30 |      6 |     20.00% |                58 |
| October   |           31 |      5 |     16.13% |                63 |
| November  |           30 |      5 |     16.67% |                68 |
| December  |           20 |      1 |      5.00% |                69 |

---

## 📊 Excel Analysis

The project uses **Pivot Tables** to analyze:

* Total number of visits
* Number of deaths and survivors
* Risk category distribution
* Monthly deaths
* Monthly mortality rates
* Monthly percentage changes
* Cumulative deaths
* Relationship between risk category and patient outcome

### Visualizations

Charts can be used to present:

* 📊 Total Visits vs. Deaths
* 🥧 Live vs. Die Distribution
* 📊 High Risk vs. Low Risk Cases
* 📈 Monthly Death Trend
* 📈 Cumulative Deaths
* 📊 Deaths by Risk Category

---

## 🛠️ Tools & Technologies

* **Microsoft Excel**
* **Pivot Tables**
* **Pivot Charts**
* **Data Analysis**
* **Data Visualization**
* **Percentage & Trend Analysis**

---

## 🔍 Main Insights

* There were **403 total hospital visits** in the dataset.
* **334 patients survived**, while **69 patients died**.
* The overall mortality rate was **17.12%**.
* Low-risk cases represented **54.84%** of all visits.
* High-risk cases represented **45.16%** of all visits.
* There were more deaths among **high-risk patients (39)** than low-risk patients (30).
* **August recorded the highest monthly mortality rate at 29.03%**.
* **December recorded the lowest monthly mortality rate at 5.00%**.
* The cumulative number of deaths reached **69 by the end of the year**.


## 👨‍💻 Skills Demonstrated

This project demonstrates practical skills in:

* Excel Data Analysis
* Pivot Table Creation
* Pivot Chart Creation
* KPI Calculation
* Percentage Analysis
* Time-Series Analysis
* Trend Analysis
* Healthcare Data Analysis
* Data Visualization
* Business Insight Generation
