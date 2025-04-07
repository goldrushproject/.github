## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# 🧾 GoldRush Project Access Guide

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

The dashboard aggregates and visualizes the outputs from all services and is hosted on AWS QuickSight.

🔗 **Dashboard URL:**  
[GoldRush QuickSight Dashboard](https://us-west-2.quicksight.aws.amazon.com/sn/dashboards/44fa45e2-8d5f-4843-95cc-4c22ba2978a5)

---

## 🔐 How to Access the Dashboard

To access the dashboard, use the following AWS IAM user credentials:

- **Account ID:** `650251730947`  
- **IAM Username:** `quicksight-reader`  
- **Password:** `Goldrushvisitor%`  
- **AWS Console Login URL:** [https://650251730947.signin.aws.amazon.com/console](https://650251730947.signin.aws.amazon.com/console)

### Steps:

1. Open the AWS Console login URL above.
2. Enter:
   - **IAM Username**: `quicksight-reader`
   - **Password**: `Goldrushvisitor%`
3. Once logged in, navigate to QuickSight (you can search for "QuickSight" in the AWS search bar).
4. Open the dashboard directly via this link:  
   [View Dashboard](https://us-west-2.quicksight.aws.amazon.com/sn/dashboards/44fa45e2-8d5f-4843-95cc-4c22ba2978a5)

📌 **Note:** This account is view-only and intended for assessment purposes only.

---
