# Shoppers-Behaviour-and-Revenue-Analysis

# 🛍️ Shoppers Behaviour and Revenue Analysis

This repository contains data analysis and modeling on an e-commerce dataset that tracks user behavior and purchase intent. The primary goal is to understand the factors that influence whether a user will generate revenue (make a purchase) or not.

---

## 📁 Dataset Summary

**Filename**: `Shoppers_Behaviour_and_Revenue.csv`  
**Rows**: 12,330  
**Columns**: 18  
**Target Variable**: `Revenue` (True/False)

---

## 🧾 Column Description

| Column Name                | Description                                                                 | Data Type     |
|---------------------------|-----------------------------------------------------------------------------|---------------|
| `Administrative`          | Number of administrative pages visited during the session                   | Continuous    |
| `Administrative_Duration`| Time (in seconds) spent on administrative pages                              | Continuous    |
| `Informational`           | Number of informational pages visited                                       | Continuous    |
| `Informational_Duration` | Time (in seconds) spent on informational pages                               | Continuous    |
| `ProductRelated`          | Number of product-related pages visited                                     | Continuous    |
| `ProductRelated_Duration`| Time (in seconds) spent on product-related pages                             | Continuous    |
| `BounceRates`             | Percentage of visitors who left the site after viewing one page             | Continuous    |
| `ExitRates`               | Percentage of exits from the site                                           | Continuous    |
| `PageValues`              | Value of pages visited by the user                                          | Continuous    |
| `SpecialDay`              | Indicates closeness to a special day (like Valentine's or Mother's Day)     | Continuous    |
| `Month`                   | Month of the visit (e.g., Feb, Mar, etc.)                                   | Categorical   |
| `OperatingSystems`        | Coded value representing the OS used by the visitor                         | Categorical   |
| `Browser`                 | Coded value representing the browser used                                   | Categorical   |
| `Region`                  | Geographical region code                                                    | Categorical   |
| `TrafficType`             | Traffic source code                                                         | Categorical   |
| `VisitorType`             | Type of visitor: Returning_Visitor, New_Visitor, or Other                   | Categorical   |
| `Weekend`                 | Boolean: True if the visit happened on the weekend                          | Categorical   |
| `Revenue`                 | Boolean: True if the session ended in a purchase                            | Categorical   |

---

## 🎯 Project Goals

- 📊 Perform exploratory data analysis (EDA)
- 📈 Build classification models to predict `Revenue`
- 🧠 Understand key behavioral metrics that influence purchases
- 👥 Segment visitors based on their browsing behavior

---


