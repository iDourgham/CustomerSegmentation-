# Credit Card Customer Segmentation

This project segments credit card customers into distinct behavioral groups using clustering techniques. The goal is to better understand customer credit usage patterns and support tailored business strategies.

---

## 📋 Project Overview

- **Objective:** Segment customers based on their credit card transaction behaviors.
- **Dataset:** Credit card user data including balances, purchases, payments, credit limits, and cash advances.
- **Methodology:**  
  - Data preprocessing and feature selection  
  - Gaussian Mixture Model (GMM) clustering  
  - Cluster interpretation with descriptive names  
  - Visualization of cluster profiles using Plotly

---

## 🧩 Cluster Profiles

| Cluster Name    | Description                                                                                     |
|-----------------|-------------------------------------------------------------------------------------------------|
| Low Users       | Very low balances and spending, minimal credit activity.                                        |
| High Users      | Highest balances and payments, very active and responsible credit users.                        |
| Heavy Holders   | High balances but lower payments, likely revolving credit users.                                |
| Big Spenders    | Very high purchases, often large one-off payments, premium or luxury shoppers.                  |

---

## 📊 Key Features & Visualizations

- Average key metric comparisons across clusters  
- Pie charts showing feature distributions per cluster  

Visualizations are generated using Plotly for interactivity.
