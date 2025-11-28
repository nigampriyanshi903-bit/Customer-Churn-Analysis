# Customer-Churn-Analysis

This project analyzes a telecommunications dataset to identify the main drivers of customer churn. By visualizing key metrics, the dashboard aims to provide actionable insights for building targeted retention campaigns and maximizing Total Revenue.

##  Tools and Data

* **Tool:** **Power BI** (Data Modeling, Visualization, and Dashboarding)
* **Data Source:** Telecommunication Customer Dataset (Raw data sample provided in `image_f156d6.png`)
* **Key Focus:** Analyzing churn across Internet Services, Contract Types, and Payment Methods.

## 📊 Key Dashboard Metrics (Overview)

| Metric | Value |
| :--- | :--- |
| **Total Customers** | 7.04K |
| **Total Tech Tickets** | 2,955 |
| **Total Admin Tickets** | [Value not visible in image] |
| **Customers Retained** | [Value not visible in image] |

---

## Top Churn Drivers (Key Findings)

The analysis reveals where customer retention is most challenged:

### 1. Contract Type is Critical

* **Month-to-Month** contracts are the most numerous (**3.88K**) and are the most vulnerable to churn due to lack of commitment.
* **Two-Year (1.7K)** and **One-Year (1.47K)** contracts show higher customer stability.

### 2. Internet Service Dependency

* **Fiber Optic** users represent the largest segment of customers (**3.10K**), making them the largest base at risk. This service's high volume means even a small churn rate here has a large impact.
* **DSL** users are the second largest (**2.42K**).

### 3. Payment Method & Demographics

* **Payment Method:** The most common payment method is **Electronic Check (2.4K)**. High usage of this method may indicate a correlation with churn, possibly due to customer effort or instant cancellation capability.
* **Age:** **Young Customers (5.9K)** far outnumber Senior Citizens (**1.1K**), meaning the churn efforts must primarily focus on the younger demographic.
* **Gender:** The customer base is nearly evenly split between Female (**3.49K**) and Male (**3.56K**).

---

## Recommendations for Retention

Based on the visualized findings, the following strategies are recommended:

1.  **Incentivize Long-Term Contracts:** Offer special deals or discounts to customers currently on a **Month-to-Month** plan to encourage them to switch to **One-Year or Two-Year** contracts.
2.  **Fiber Optic Service Quality:** Since Fiber Optic has the largest user base, prioritize monitoring and improving service reliability and support (Tech Tickets) specifically for this user group to prevent churn.
3.  **Optimize Electronic Check Experience:** Investigate the reason behind the high usage of **Electronic Checks**. Streamline the process or offer a small incentive for automated (Bank Transfer/Credit Card) payments to improve customer stickiness.

---
