# Retention-behavior-and-churn-driver-analysis


> Customer Retention Analysis using Python, Statistical Analysis, Excel, and Power BI to identify customer churn behaviour and provide actionable business recommendations.

---

# Project Overview

Customer retention plays a signuficant role to the long-term growth for most bussiness. Acquiring a new customer is typically more expensive than retaining an already existing one, and retaining cost is also typically more expensive than gaining back the customer that churn away. It is therefore it is an important strategic move to identify the cause behind the customer-churned behavior and prevent the loss of customer and revenue in time.

This project aims to explore churn behavior, prioritize the high risk groups, investigate potential reason behind churn, and identify the individual-level 'churn associated' or 'red flag' products for potential futher investigation and intervention

The analysis combines data processing, cohort analysis, statistical hypothesis tesing, and product-level investigation. This report is  devided into 3 sections: Business 
1. Problem and Work Flow,
2. Methodology
3. Business Findings and Conclusion

---

# Table of content

>Part I: Business Problem and Work Flow

>Part II : Methodology

>Part III : Business Findings and Conclusion



---

# Part I: Business Problem and Work Flow
## Business Problem
The objective of this project is to indentify the possibility to improve the customer retention by
- Identifying the pattern behind churn behavior
- Prioritizing customer group based on their retention pattern with intervention
- Investigate the potential churn driver
- Identifying products associated with customer churn

## Business Questions

### 1. How does customer churn behave?

The project investigate general churn behavior and answer questions such as
- What is customer churn rate?
- How much revenue has been lost due to customer churn?
- How much revenue could be saved if we can protect 'at risk customer' from churning?
- What is the average customer lifespan
- Which aquistioned cohorts perform poorly

### 2. Which customers should be prioritized?
Customer prioritization is conducted using customer segmentation assisted by RFM analysis.

We identify
- High-value customer
- Customer at risk or churn
- Customer needing immediate retention campaigns

### 3. Why do customers churn?

Several hypotheses are statistically tested to determined if churn bahavior is associated with
- Spending bahavior
- Discount campaign
- Shipping fee
- Waiting shipment time
- Product-page session duration

Not just assumtions

Each hypothesis is evaluated by statistical tools

### 4. Which products are associated with customer churn?

Products are futher investigated to determine whether some products appear disprotionately among churn-prone customer

This includes two business concepts
- Churn-associated products
- Retention-friendly product


These findings can support future product quality investigation and marketing campaigns

---

## Dataset

| Item | Description |
|------|-------------|
| Business Domain | E-commerce |
| Transactions | |
| Features | |
| Observation unit |Order ID|
| Period |From 2021-2026|

---

## Project Workflow

```text
Raw Data
     ↓
Data Cleaning
     ↓
EDA
     ↓
Cohort Analysis
     ↓
RFM Analysis
     ↓
Customer Segmentation
     ↓
Group Analysis
     ↓
Hypothesis Testing
     ↓
Product Investigation
     ↓
Business Insights
     ↓
Dashboard
```

---

## Business Definitions

### Customer Churn

...

### At Risk Customer

...

### Cannot Lose Customer

...

### VIP customer

...

### normal customer

...

### 

...

### Churn-associated Product

...

---

# Methodology

## Data Cleaning

...

## Exploratory Data Analysis

...

## Cohort Analysis

...

## RFM Analysis

...

## Customer Segmentation

...

## Group Analysis

...

## Statistical Hypothesis Testing

...

## Product Investigation

...

---

# Part III: Business Findings and Conclusion

## Dashboard

The dashboard summarizes the main findings of this project, including customer segmentation, cohort retention, product analysis, hypothesis testing, and overall business KPIs.

> Dashboard Preview

---

# Business Insights

## Customer Prioritization

Customer retention should not be treated equally across all customer groups.

- Cannot Lose and At Risk customers contribute the highest potential revenue loss and should be prioritized.
- Low Engagement customers account for almost half of all customers, suggesting many users leave before becoming loyal customers.
- Different customer groups require different retention strategies.

---

## Early Customer Drop-off

More than 90% of customers become inactive after their first month across almost every cohort.

This indicates that the biggest retention challenge happens immediately after the first purchase rather than later in the customer lifecycle.

---

## Churn Drivers

Purchase amount shows a statistically significant difference between customer groups.

However, no significant difference was found for

- Discount amount
- Shipping fee
- Waiting time
- Session duration

The current dataset is therefore not sufficient to fully explain why customers churn. Other factors such as product quality, customer satisfaction, and competitor offerings should be investigated.

---

## Product Investigation

Several products were identified as churn-associated products.

These products should not be considered as the direct cause of churn, but as candidates for further investigation.

One notable finding is that At Risk customers purchase Clothes & Apparel significantly more often than other customer groups. This category may deserve additional quality or customer feedback reviews.

Retention-friendly products were also identified and may be considered for higher marketing exposure.

---

## Revenue Performance

Monthly revenue and order volume fluctuate over time but remain relatively stable overall.

Revenue peaks and order peaks occur during the same periods, suggesting that sales performance is mainly driven by order volume.

---

# Business Recommendations

## Customer Strategy

Focus retention resources on customer groups with the highest business impact.

- Cannot Lose → Immediate retention campaign
- At Risk → Personalized retention offers
- VIP → Loyalty and premium benefits
- Low Engagement → Re-engagement campaign
- Lost Customer → Win-back campaign (when economically feasible)

---

## Early-stage Retention

Most customers leave after their first month.

Retention efforts should therefore focus on the first 30 days after acquisition.

Possible initiatives include

- Loyalty point programs
- Daily check-in rewards
- Gamification
- First-month exclusive offers
- Personalized recommendations

The objective is to encourage repeat purchases and build customer habits during the period with the highest drop-off.

---

## Product Strategy

Use churn-associated products as an early warning list.

Further investigation should include

- Product quality
- Return rate
- Customer reviews
- Customer complaints

Retention-friendly products may also be considered for increased exposure in future campaigns.

---

## Marketing Strategy

The analysis suggests that discount campaigns alone are unlikely to solve customer churn.

Future retention strategies should combine pricing with product quality improvements and better customer experience.

---

## Future Data Collection

To better understand customer churn, future datasets should include

- Customer satisfaction
- Product ratings
- Customer support interactions
- Return records
- Customer complaints
- Competitor information

---

# Limitations

This project identifies statistical relationships rather than causal relationships.

Some recommendations require additional operational data before business decisions can be made.

---

# Future Work

Possible extensions of this project include

- Customer Lifetime Value (CLV)
- Churn prediction model
- Survival analysis
- A/B testing for retention campaigns
- Personalized recommendation system
# Tools & Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Excel
- Power BI
- Git
- GitHub
