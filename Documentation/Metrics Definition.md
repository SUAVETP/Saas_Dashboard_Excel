# Metrics Definition

This document defines all the key metrics and KPIs used in the final SaaS dashboard.

---

## 🔢 KPI Cards

### 1. Total Customers
**Definition:** Total number of unique customers that have ever signed up for a plan.  
**Formula:**  
`COUNT(DISTINCT Customer_ID)`

---

### 2. Churned Customers
**Definition:** Customers who canceled their subscription at any point.  
**Formula:**  
`COUNT(Customer_ID) WHERE Churned = "Yes"`

---

### 3. Active Customers
**Definition:** Customers who are currently subscribed (i.e., not churned).  
**Formula:**  
`COUNT(Customer_ID) WHERE Is_Active = "Yes"`

---

### 4. Churn Rate (%)
**Definition:** The percentage of customers who have churned out of the total.  
**Formula:**  
`(Churned Customers / Total Customers) × 100`

---

### 5. Average Monthly Recurring Revenue (MRR)
**Definition:** The average recurring monthly revenue from active customers.  
**Formula:**  
`AVG(Monthly_Recurring_Revenue) WHERE Is_Active = "Yes"`

---

### 6. Lifetime Value (LTV)
**Definition:** Average expected revenue from a customer over their entire lifecycle.  
**Formula:**  
`Average MRR × Average Active Months`

---

### 7. Average NPS Score
**Definition:** The average Net Promoter Score based on customer feedback.  
**Formula:**  
`AVG(NPS_Scrore_Clean)`  
**Scale:** 0 (lowest loyalty) to 10 (highest loyalty)

---

## 📊 Visual Breakdown Metrics

These metrics appear in visual charts, tables, or segment breakdowns.

### • Churn Reason
**Definition:** Categorized reasons why customers canceled (e.g., Pricing, Bugs, Service).  
**Displayed As:** Horizontal bar chart.

---

### • Plan Performance (Basic, Pro, Enterprise)
**Definition:** Breakdown of MRR, churn, and customer count per plan type.

---

### • Acquisition Channel
**Definition:** How customers found the product: Organic, Paid, Referral.

---

### • Region
**Definition:** Where customers are located: North America, Europe, Asia, Other.

---

### • NPS Breakdown
**Definition:** Split into Promoters (9–10), Passives (7–8), and Detractors (0–6).

---

Each metric is designed to help a SaaS company understand growth, retention, revenue health, and customer satisfaction.
