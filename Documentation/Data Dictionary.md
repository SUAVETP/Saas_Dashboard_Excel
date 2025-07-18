\# Data Dictionary



This file defines each column used in the SaaS dataset for the Excel dashboard.



---



\### 🧾 Customer-Level Fields



| Column Name                | Description |

|---------------------------|-------------|

| `Customer\_ID`             | Unique identifier for each customer (e.g., CUST0001). |

| `Signup\_Date`             | Date when the customer signed up. |

| `Cancel\_Date`             | Date when the customer canceled their subscription (if churned). |

| `Plan\_Type`               | Subscription plan chosen by the customer — Basic, Pro, or Enterprise. |

| `Country`                 | Country where the customer is based. |

| `Region`                  | Geographic grouping — North America, Europe, Asia, Other. |

| `Industry`               | Industry sector the customer belongs to — EdTech, FinTech, E-commerce, etc. |



---



\### 💰 Financial Metrics



| Column Name                | Description |

|---------------------------|-------------|

| `Monthly\_Recurring\_Revenue` | Monthly fee paid by the customer based on their plan. |

| `Total\_Contract\_Value`      | Full value of the contract (if prepaid or long-term). |

| `Currency`                  | The currency used (USD, EUR, etc). |

| `Payment\_Method`            | How the customer paid — PayPal, Wire, Credit Card. |



---



\### 🧍 Customer Status Fields



| Column Name                | Description |

|---------------------------|-------------|

| `Churned`                  | Indicates whether the customer has churned — Yes/No. |

| `Customer Status`          | Status description — Active, Churned. |

| `Is\_Active`                | Binary flag (Yes/No) indicating if customer is currently active. |

| `Active Months`            | Total number of months a customer has stayed subscribed. |



---



\### 🤔 Feedback \& Behavior



| Column Name                | Description |

|---------------------------|-------------|

| `Churn\_Reason`             | Reason for cancellation (e.g., Pricing, Bugs, Switched Competitor, etc). |

| `NPS\_Score`                | Original Net Promoter Score submitted by customer. |

| `NPS\_Scrore\_Clean`         | Cleaned version (0–10 scale) for calculating averages. |

| `Support\_Tickets\_Opened`   | Number of times a customer reached out for support. |



---



\### 📈 Acquisition Insights



| Column Name                | Description |

|---------------------------|-------------|

| `Acquisition\_Channel`      | Source of acquisition — Paid, Organic, Referral. |

| `Is\_Referral\_Customer`     | Binary flag (Yes/No) indicating if referred by another user. |

| `Cohort\_Month`             | Year-Month of the customer’s signup date (used for cohort analysis). |



---



These fields were cleaned, categorized, and analyzed in Excel for the final dashboard presentation.



