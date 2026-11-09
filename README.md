# Customer-Churn-Retention-Analytics

# Customer Purchase Behaviour & Churn Analytics
### Customer Retention | RFM Segmentation | Cohort Analysis | Customer Lifetime Value

An end-to-end customer retention analytics project designed to uncover purchasing patterns, identify churn risks, evaluate customer lifetime value, and develop data-driven retention strategies.

Built using **SQL, Python, and Power BI**, this project transforms raw e-commerce transaction data into actionable customer insights through data preparation, RFM analysis, cohort retention modelling, and interactive business dashboards.

---

## 1. Project Overview

Customer retention is essential for sustainable business growth. However, businesses often lack visibility into customer inactivity, purchasing behaviour, and the revenue impact of churn.

This project addresses a key business challenge:

**How can a D2C brand identify customers who are likely to churn, understand their purchasing behaviour, and prioritise retention efforts based on customer value?**

The analysis focuses on:
- Understanding customer purchasing behaviour.
- Measuring customer retention and churn patterns.
- Segmenting customers based on purchasing value.
- Estimating Customer Lifetime Value (CLV).
- Identifying high-priority customers for re-engagement.
- Developing actionable retention strategies.

## 2. Business Problem

A D2C brand has limited visibility into:

- Which customers are becoming inactive?
- When do customers stop making repeat purchases?
- Which customer segments contribute the most revenue?
- Which lapsed customers are worth re-engaging?
- Where are the biggest opportunities to improve retention?

The objective is to convert transactional data into a structured retention analytics framework that supports customer prioritisation and revenue protection.

## 3. Dataset & Technology Stack

**Dataset:** Olist Brazilian E-commerce Dataset

Source: [Download Dataset from Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

**Technology Stack**

| Category | Tools & Technologies |
|---|---|
| Database & Querying | SQL, SQLite |
| Programming | Python |
| Data Manipulation | Pandas |
| Data Visualization | Matplotlib, Seaborn |
| Business Intelligence | Power BI |
| Analytical Methods | RFM Analysis, Cohort Retention, CLV Estimation |

## 4. Analytical Methodology

The project follows a three-phase analytics pipeline.

### Phase 01 — SQL | Data Preparation & Integration

Prepared and consolidated raw e-commerce data into an analysis-ready master dataset.

**Key Activities:**
- Loaded five Olist tables into SQLite.
- Filtered transactions to include delivered orders only.
- Integrated orders, order items, customers, payments, and reviews.
- Created a consolidated master view using SQL joins.
- Applied LEFT JOIN for reviews to preserve all orders.

**Outcome:** A unified dataset ready for customer-level analysis.

### Phase 02 — Python | Customer Analytics & Feature Engineering

Applied analytical techniques to understand customer behaviour, purchasing frequency, retention, and value.

**RFM Analysis**

Evaluated customers across three dimensions:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer purchased.
- **Monetary:** How much a customer spent.

Assigned scores from 1–4 using quantile-based bucketing.

**Customer Segmentation**

Classified customers into five behavioural segments:

| Segment | Description |
|---|---|
| Champions | Highest-value customers |
| Loyal | Customers with repeat purchasing behaviour |
| Promising | Customers with potential for growth |
| At Risk | Customers requiring retention attention |
| Churned | Customers who have become inactive |

**Cohort Retention Analysis**
- Grouped customers by acquisition cohort.
- Analysed month-over-month customer retention.
- Identified early-stage retention declines.
- Examined customer purchasing patterns over time.

**Customer Lifetime Value (CLV)**

Estimated customer value using:

`CLV = Average Order Value × Purchase Frequency`

**Outcome:** Customer-level analytical features and segmentation data for business intelligence reporting.

### Phase 03 — Power BI | Interactive Dashboard Development

Developed a three-page interactive dashboard to communicate customer behaviour, retention performance, and business priorities.

## 5. Dashboard Architecture

The dashboard is structured into three analytical views.

### Page 01 — Executive Overview

Provides a consolidated view of customer performance and revenue contribution.

**Key Analysis:**
- Customer KPIs
- Customer segment distribution
- Customer Lifetime Value by segment
- Revenue contribution across customer segments

### Page 02 — Customer Retention Analysis

Evaluates customer retention patterns and identifies critical churn periods.

**Key Analysis:**
- Cohort retention heatmap
- Month-over-month retention trends
- Customer drop-off patterns
- Early-stage retention analysis

### Page 03 — Customer Prioritisation & Action Plan

Identifies customer segments that require targeted retention and re-engagement strategies.

**Key Analysis:**
- Customer segmentation scatter plot
- Customer value and behavioural patterns
- Priority customer identification
- CRM-ready customer action table

## 6. Dashboard Previews

### Executive Overview
![Executive Overview](images/overview.png)

### Key Findings
![Key Findings](images/key_findings.png)

### Retention Gaps
![Retention Gaps](images/gaps.png)

### Strategic Recommendations
![Recommendations](images/recommendations.png)

## 7. Key Analytical Findings

The analysis revealed several important customer retention and revenue patterns.

**01. Early-Stage Customer Churn**

61% of customers do not return after their first purchase, with the steepest retention decline occurring between Month 0 and Month 1.

**Business Implication:** The post-purchase experience represents the most critical opportunity for improving customer retention.

**02. Champions Drive Disproportionate Revenue**

Champions represent 17.1% of customers but contribute 26.2% of total revenue.

**Business Implication:** High-value customers deserve focused loyalty and retention initiatives.

**03. At Risk Customers Present a Recovery Opportunity**

At Risk customers account for 6.2% of the customer base and remain highly recoverable due to recent engagement.

**Business Implication:** Targeted win-back campaigns can prioritise this segment.

**04. Churned Customers Represent Historical Revenue Loss**

Churned customers account for 19% of the customer base and represent 15.9% of lost historical revenue.

**Business Implication:** Early retention and reactivation strategies are important before customers become inactive.

## 8. Strategic Recommendations

Based on the analytical findings, the following retention initiatives are recommended.

| Priority Area | Recommended Action |
|---|---|
| Customer Loyalty | Introduce a loyalty programme with rewards and exclusive offers to convert Loyal customers into Champions. |
| High-Value Retention | Develop a VIP retention programme with personalised experiences for Champions. |
| Early Churn Prevention | Launch a post-purchase email journey within the first 30 days to improve customer engagement. |
| Customer Reactivation | Run targeted, limited-budget win-back campaigns for churned customers. |
| Churn Identification | Reassess churn thresholds using actual customer repurchase cycles to improve risk identification. |

## 9. Business Impact & Conclusion

This project demonstrates how customer transaction data can support more effective retention strategies and revenue-focused decision-making.

Three major opportunities emerged from the analysis:

1. **Protect High-Value Customers:** Retain Champions through personalised loyalty initiatives and exclusive experiences.
2. **Reduce Early Customer Churn:** Improve post-purchase engagement during the critical first 30 days.
3. **Increase Customer Lifetime Value:** Develop Loyal customers into higher-value customer segments.

By combining SQL-based data integration, Python-driven customer analytics, and Power BI visualisation, this project establishes a structured approach to understanding customer behaviour and prioritising retention opportunities without increasing customer acquisition spend.

## 10. Skills Demonstrated

- SQL Data Cleaning & Data Integration
- Python-Based Data Analysis
- Customer Behaviour Analysis
- RFM Analysis & Customer Segmentation
- Cohort Retention Analysis
- Customer Lifetime Value (CLV)
- Churn Analysis
- Data Visualization
- Power BI Dashboard Development
- Business Intelligence
- Customer Retention Strategy
- Data-Driven Business Recommendations

