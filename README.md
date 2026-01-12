
<a href="/vish7715.github.io"> Home </a>

# Starbucks Rewards – Loyalty program Analysis and Customer Segmentation

## 📌 Business Use Case

Starbucks was born as a whole coffee beans seller in Pike’s place market in Seattle, Washington in 1971 . It is now the biggest coffee chain in the world expanding globally with over 40,000 stores globally as of 2025. 

As part of their Loyalty program, Starbucks rewards , different offer types have been sent to customers over a month of time. The use case is to study customer behaviour towards each offer type and then to segment those customers based on their behaviours for Starbucks to come up with data driven strategies to enhance customer experience.

---

## 🎯 Project Objectives

For this project, a simulation of the Starbucks rewards program dataset containing customers information including thr demographic details and offer types (BOGO,Discount) and interactions (offers viewed vs offers completed)  has been collected from Kaggle. 

## 📊 Business Question

In this project , key business questions to be answered are -

1. What are the most popular offer types ?
2. What is the most viewed offers vs most completed offers ?
3. Based on customers interactions within the app, what segments they can be put into ?

## 🧱 Data Structure

Dataset contains mainly 3 tables - 

### 1️⃣ profile.csv

| Column | Data Type |
|------|---------|
| gender | object |
| age | number |
| became_member_on | int64 |
| income | float 

---

### 2️⃣ portfolio.csv
| Column | Data Type |
|------|-------------|
| id | object |
| rewards | int |
| channels | object |
| difficulty | int |
| duration | int |
| offer type | onject

---

### 3️⃣ transcript.csv

| Column | Data Type |
|------|---------|
| person | object |
| event | object |
| value | object |
| time | int |

## 🛠️ Tools & Technologies
-Python (Pandas , Numpy , json)
- ML (K means clustering )

## Data Cleaning 

Data cleaning and transformation has been done via Pandas , python library. 

## Data Insights 

1. What is the most viewed offers vs most completed offers ?

   Based on Data Analysis done, below are the findings -
 
<img width="452" height="237" alt="image" src="https://github.com/vish7715/Customer-Segmentation--Starbucks-Dataset/tree/main/images/Image 12-01-26 at 08.59.png"/>

   







