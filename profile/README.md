## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# 🧾 GoldRush Project Assessment Guide

This project consists of **four microservice repositories**, spread across **two AWS accounts**, and is visualized through a **client dashboard on AWS QuickSight**.

---

## 📁 Repositories Overview

| Microservice         | Purpose                            | Link |
|----------------------|------------------------------------|------|
| **ETL**              | Extracts and transforms financial data using `yfinance`. | [yfinance-data-etl](https://github.com/goldrushproject/yfinance-data-etl) |
| **Model Training**   | Trains machine learning models in a serverless environment. | [serverless-train](https://github.com/goldrushproject/serverless-train) |
| **Model Inference**  | Deploys trained models to serve predictions via API. | [serverless-inference](https://github.com/goldrushproject/serverless-inference) |
| **Data Assessment**  | Combines and evaluates model outputs for quality and accuracy. | [data-assess](https://github.com/goldrushproject/data-assess) |

---

## 📊 Client Dashboard

The dashboard aggregates the outputs from all services and is hosted on AWS QuickSight.

🔗 **Dashboard URL:**  
[GoldRush QuickSight Dashboard](https://us-west-2.quicksight.aws.amazon.com/sn/accounts/650251730947/dashboards/44fa45e2-8d5f-4843-95cc-4c22ba2978a5?directory_alias=GoldRushQuickSightBI)

📌 **Note:** Log in using the provided **viewer account** to access the dashboard.

---

## ✅ Assessment Instructions

1. **Review Each Repository:**
   - Confirm code quality and service separation.
   - Ensure README explains deployment, environment setup, and key logic.

2. **Check the Dashboard:**
   - Validate that it displays:
     - Extracted financial data.
     - Model predictions.
     - Summary/assessment metrics.
   - Confirm data updates or refresh as expected.

3. **No Active Testing Required:**
   - All services are live and integrated.
   - The system's functionality can be assessed through dashboard insights.

---

