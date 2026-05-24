# Quantium Retail Analytics — Forage Virtual Experience

Customer segmentation, trial store experimentation, and commercial reporting on retail transaction data. Completed as part of Quantium's Data Analytics job simulation on Forage.

---

## What the project covers

Three connected tasks that follow how retail analytics actually flows — from understanding your customers, to testing a change, to explaining what it means to a business audience.

**Task 1 — Customer analytics**

Cleaned and merged transaction and customer datasets, extracted pack sizes and brand names from product descriptions, and analysed purchasing behaviour across customer segments (lifestage × premium tier).

Key findings:
- Older Families were the highest-spending segment in total sales
- Young Singles/Couples contributed strongly through customer volume — a different commercial lever
- Kettle, Doritos and Smiths led brand sales
- 150g and 175g were the most purchased pack sizes
- Family segments bought more frequently and in larger quantities per transaction

**Task 2 — Trial store experimentation**

Evaluated whether new store layouts improved performance in three trial stores (77, 86, 88) using matched control stores and pre/post comparison.

Control store matching used sales correlation, customer count correlation, and magnitude similarity — not just a simple average comparison.

Results:
- **Store 77**: ~31% uplift, statistically significant → clear case for rollout
- **Store 86**: ~14% uplift, mixed significance → inconclusive
- **Store 88**: negative performance → data does not support rollout

The Store 77/88 split is the interesting part. Same intervention, opposite outcomes. The analysis shows why you don't just look at the average across all trial stores.

**Task 3 — Commercial reporting**

Built a client-style presentation using the Pyramid Principle: lead with the recommendation, support with evidence, don't make the stakeholder wade through methodology first. The output was structured for a category manager, not a data team.

---

## Tools

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

---

## Repository structure

```
task1/              ← customer analytics notebook
task2/              ← trial store experimentation notebook
task3_reporting/    ← presentation slides
data/               ← transaction and customer datasets
images/             ← charts and visualisation outputs
certification/      ← completion certificate
```
