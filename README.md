# RavenStack Customer Retention & Churn Analysis

## 📌 Project Overview
This repository features an end-to-end data analysis project focused on customer attrition for **RavenStack**, a B2B subscription service. Using a dataset of 5,000+ records, I developed an interactive dashboard to visualize churn drivers and formulated strategic recommendations to improve long-term retention and Customer Lifetime Value (CLV).

## 📊 Dashboard Data Sources (The Core Files)
The following files were processed and linked to build the **Customer Retention & Churn Dashboard**:

* **`ravenstack_subscriptions.csv`**
    * **Tag:** `Financial & Revenue Metrics`
    * **Dashboard Role:** Used to calculate **Total MRR**, **Average Revenue per User**, and **Billing Frequency** (Monthly vs. Annual) impact.
* **`ravenstack_account.csv`**
    * **Tag:** `Customer Segmentation`
    * **Dashboard Role:** Powers the **Industry Breakdown** (FinTech, EdTech, etc.) and geographic distribution charts.
* **`ravenstack_churn_event.csv`**
    * **Tag:** `Attrition Analysis`
    * **Dashboard Role:** The primary source for the **Churn Reason Analysis** (Competitor, Pricing, Features) and feedback trends.
* **`ravenstack_support_ticket.csv`**
    * **Tag:** `Service Quality Metrics`
    * **Dashboard Role:** Correlates **Support Satisfaction Scores** and resolution speed with customer churn probability.
* **`ravenstack_feature_usage.csv`**
    * **Tag:** `Product Engagement`
    * **Dashboard Role:** Tracks active feature engagement to identify "at-risk" users showing low platform activity.

## 💡 Key Insights
* **Overall Churn Rate:** Identified at **22%**.
* **High-Risk Segment:** Monthly subscribers show significantly higher attrition than annual subscribers.
* **Onboarding Friction:** A critical churn spike occurs within the **0-3 month** window.
* **Retention Forecast:** Shifting 10% of monthly users to annual plans is projected to increase total **CLV by 15%**.

## 🛠️ Tools Used
* **Microsoft Excel:** Advanced Pivot Tables, Slicers, and Dynamic Dashboarding.
* **Data Modeling:** Trendline analysis and cohort segmentation.
* **Documentation:** Professional reporting via Microsoft Word and Markdown.

## 📂 How to Access the Project
1.  **View the Dashboard:** Open **`all churn data set NEW.xlsx`** in Microsoft Excel. Use the slicers to filter by industry or plan tier.
2.  **Read the Strategy:** Refer to **`churn insights and reccommendations.docx`** for the full executive summary and strategic billing recommendations.
3.  **Explore the Raw Data:** All source datasets are available in `.csv` format for microsoft excel.

---
*Developed and compiled by muthokapuritymumbi as part of a Data Science internship*****
