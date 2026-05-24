# Quantium Retail Analytics Virtual Experience

This repository contains my work completed as part of Quantium's Retail Analytics Virtual Experience program.

The project focused on analysing customer purchasing behaviour in the chips category and evaluating the impact of trial store layouts using transactional and customer data.

---

# Project Overview

The work was completed across three tasks:

1. Customer analytics and purchasing behaviour
2. Trial store experimentation and uplift analysis
3. Commercial reporting and business recommendations

The goal was to translate raw retail transaction data into meaningful commercial insights that could support category planning and strategic decision-making.

---

# Task 1 — Customer Analytics & Purchasing Behaviour

## Objective

Analyse customer transaction data to identify:

- key customer segments
- purchasing behaviour patterns
- brand preferences
- pack size trends
- repeat purchasing behaviour

## Work Completed

### Data Preparation
- Cleaned and merged transaction and customer datasets
- Converted date columns and handled invalid transactions
- Removed outliers (including extreme quantity purchases)
- Extracted pack sizes and brand names from product descriptions

### Exploratory Analysis
Analysed:
- total sales
- transactions
- customer counts
- pack sizes
- brand distribution
- monthly sales trends

### Customer Segmentation
Compared customer groups across:
- LIFESTAGE
- PREMIUM_CUSTOMER segments

Metrics included:
- total sales
- transactions per customer
- units per transaction
- average price per unit

## Key Findings

- Older Families were the highest spending customer segment
- Young Singles/Couples contributed strongly through customer volume
- Kettle, Doritos and Smiths were the leading brands
- 150g and 175g packs were the most commonly purchased pack sizes
- Family-oriented segments purchased more frequently and in larger quantities

---

# Task 2 — Trial Store Experimentation

## Objective

Evaluate whether new store layouts improved sales performance in trial stores:

- Store 77
- Store 86
- Store 88

using matched control stores and historical benchmarking.

## Work Completed

### Store Matching
Selected comparable control stores using:
- sales correlation
- customer correlation
- magnitude similarity

Final control stores:
- Store 77 → Store 233
- Store 86 → Store 155
- Store 88 → Store 178

### Trial Analysis
- Created monthly store-level metrics
- Split pre-trial and trial periods
- Scaled control stores for fair comparison
- Calculated percentage uplift
- Performed statistical significance testing

## Key Findings

### Store 77
- strongest uplift (~31%)
- statistically significant improvement
- successful trial outcome

### Store 86
- moderate uplift (~14%)
- mixed evidence of significance

### Store 88
- negative trial performance
- no evidence supporting rollout

---

# Task 3 — Commercial Reporting

Prepared a client-style PowerPoint presentation using the Pyramid Principle framework.

The presentation included:
- executive summary
- customer insights
- purchasing behaviour analysis
- brand and pack size insights
- trial store performance evaluation
- recommendations and next steps

The focus was on communicating analytical findings clearly to non-technical business stakeholders.

---

# Tools & Libraries

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook
- Excel
- PowerPoint

---

# Skills Demonstrated

- Commercial Thinking
- Communication Skills
- Data Analysis
- Data Cleaning
- Data Validation
- Data Visualization
- Presentation Skills
- Programming
- Statistical Analysis
- Customer Segmentation
- Experimental Analysis
- Business Reporting

---

# Repository Structure

```text
|── certification/
├── data/
├── images/
├── task1/
├── task2/
|── task3_reporting/
├── README.md
```

---

# Notes

This project was completed for learning purposes as part of Quantium's Retail Analytics Virtual Experience program.