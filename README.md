# Quantium Retail Strategy & Analytics

This repository contains my work completed as part of the Quantium Retail Strategy & Analytics Virtual Experience Program on Forage.

The project focuses on analysing supermarket transaction and customer data to understand purchasing behaviour within the chips category and generate commercially relevant recommendations for category strategy.

---

# Project Objective

The objective of the analysis was to identify:

- Which customer segments contribute most strongly to chip sales
- Purchasing behaviour differences across customer groups
- Multi-pack buying behaviour
- Brand and pack-size preferences
- Seasonal sales trends
- Customer segments that should be prioritised for future category planning

The analysis was designed to support recommendations for the supermarket’s upcoming category review.

---

# Dataset

The analysis used:

- 264,836 transaction records
- 72,637 customer records

The datasets included:

- transaction dates
- store numbers
- product names
- quantities purchased
- total sales
- loyalty card numbers
- customer lifestage segmentation
- premium customer segmentation

---

# Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Excel (initial data inspection)

---

# Analysis Performed

## Data Preparation and Cleaning

- Checked for missing values and inconsistent data types
- Converted Excel serial dates into datetime format
- Identified and removed transaction outliers
- Standardised inconsistent brand names

## Feature Engineering

Derived additional analytical features including:

- pack size extraction from product names
- brand extraction and standardisation
- multi-pack purchase indicator
- transaction frequency metrics
- units per transaction
- average price per unit

## Customer Behaviour Analysis

Analysed customer segments using:

- total sales contribution
- transaction frequency
- basket size behaviour
- multi-pack purchasing behaviour
- average price per unit

## Brand and Product Analysis

- Identified highest-performing brands
- Compared brand performance across customer segments
- Examined pack-size purchasing patterns

## Time-Based Analysis

- Analysed monthly sales trends
- Identified seasonal sales fluctuations and purchasing patterns

---

# Key Findings

- Budget Older Families generated the highest overall chip sales.
- Older Families showed the highest purchase frequency and strongest multi-pack purchasing behaviour.
- Mainstream Young Singles/Couples represented the largest customer base and paid the highest average price per unit.
- Kettle, Doritos and Smiths were the strongest-performing brands across the category.
- Monthly sales showed a noticeable increase in December and decline in February, suggesting seasonal purchasing behaviour.

---

# Commercial Recommendations

## 1. Prioritise Budget Older Families

This segment contributed strongly through frequent and higher-volume purchases.  
Recommended actions include:

- family-size packs
- multi-buy promotions
- value-focused offers

## 2. Target Mainstream Young Singles/Couples

This segment showed the highest average price per unit and represented the largest customer group.  
Recommended actions include:

- premium product positioning
- convenience-focused offers
- new flavour launches

## 3. Maintain visibility for leading brands

Kettle, Doritos and Smiths consistently performed strongly across customer groups and should remain key focus brands within category planning and promotional activity.

---

# Repository Structure

```text
data/
├── raw/
└── processed/

task1/
├── notebook/
├── report/
└── images/

task2/
task3/