# Voice Of Customer & Chatbot Effectiveness Analysis

## Project Overview

This project analyzes customer support operations, chatbot effectiveness, and operational cost performance for a synthetic fintech company, XYZ Finance.

The objective is to evaluate how effectively customer issues are resolved through self-service automation and human-assisted support while identifying opportunities to improve customer experience, reduce escalations, and optimize support costs.

The project follows an end-to-end analytics workflow including:

* Synthetic data generation using Python
* Data storage and analysis in Databricks
* SQL-based business analysis
* Data modeling in Power BI
* Interactive dashboard development
* Business recommendations based on analytical findings

---

## Business Problem

XYZ Finance provides digital banking products including cards, direct deposits, e-transfers, rewards programs, subscription plans, and account security services.

As customer support volume grows, management wants to understand:

* How effectively customer issues are being resolved
* Whether chatbot automation is performing as expected
* Which issue categories generate the most support demand
* Which customer issues drive dissatisfaction
* Where support costs are highest
* Whether future investment should focus on chatbot automation, human support, or a hybrid approach

---

## Data Source

This project uses synthetic customer support and chatbot interaction data generated in Python for portfolio and learning purposes.

The dataset was designed to simulate a real-world fintech customer support environment and includes:

* Customer information
* Customer support contacts
* Chatbot interactions
* Issue categories
* Chatbot intents
* Voice of Customer (VOC) tags
* Escalation tiers
* Customer satisfaction scores
* Support cost metrics

---

## Tools Used

* Python
* Pandas
* Databricks
* PySpark
* SQL
* Power BI
* GitHub

---

## Skills Demonstrated

* Data Modeling
* SQL Query Development
* Business Analytics
* Customer Experience Analytics
* KPI Development
* Dashboard Design
* Root Cause Analysis
* Data Visualization
* Synthetic Data Generation
* Customer Support Analytics

---

## Business Questions

### Customer Support Performance

* Which support channels receive the highest customer contact volume?
* What is the overall support resolution rate?
* How does resolution rate differ by support channel?
* Which issue categories generate the most customer contacts?
* Which issue categories have the lowest customer satisfaction scores?

### Chatbot Effectiveness

* What is the chatbot resolution rate?
* Which chatbot intents have the highest and lowest resolution rates?
* What percentage of chatbot interactions require agent handoff?
* Which intents generate the highest fallback rates?
* How does chatbot performance compare with human-assisted support?

### Cost & Operational Impact

* What is the average cost per contact by support channel?
* Which issue categories generate the highest support costs?
* What is the cost difference between successful automation and agent-assisted interactions?

---

## Dashboard Pages

### Customer Support Performance

<img width="2004" height="1104" alt="Customer Support Performance" src="https://github.com/user-attachments/assets/c74893f8-ed9d-4723-be9c-899d9550c7b3" />



### Chatbot Effectiveness
<img width="2056" height="1124" alt="Chatbot effectiveness" src="https://github.com/user-attachments/assets/8458b5c5-0a78-4cce-9859-0d7bc9c3ee39" />



### Cost & Operational Impact

<img width="1950" height="1196" alt="Cost and Operational Impact" src="https://github.com/user-attachments/assets/32e1cc8b-0373-4a19-874f-2b19fac85c76" />


---

## Key Findings

* Overall support resolution rate was approximately 89%.
* Chatbot was the highest-volume support channel.
* Human-assisted support achieved a significantly higher resolution rate than chatbot support.
* Approximately one-third of chatbot interactions required escalation to a human agent.
* Direct Deposit generated the highest support volume and support costs.
* Card Status exhibited the highest chatbot fallback rate.
* Fraud & Security issues recorded the lowest customer satisfaction scores.

---

## Recommendations

### Short-Term

* Improve chatbot workflows for Card Status and Direct Deposit intents.
* Reduce fallback rates through additional chatbot training and improved knowledge base coverage.
* Monitor high-volume issue categories for recurring operational problems.

### Long-Term

* Continue investing in chatbot automation for low-complexity inquiries.
* Maintain human-agent support for complex, high-risk, or emotionally sensitive issues.
* Use Voice of Customer insights to prioritize product and process improvements.
* Implement proactive monitoring for escalation trends and customer dissatisfaction.

---

## Repository Structure

```text
customer-support-analytics-dashboard/

├── data/
├── notebooks/
│   ├── Voc Data Generator.ipynb
│   ├── Voc Data Generator.html
│
├── sql/
│   ├── SQL Analysis Queries.ipynb
│   ├── SQL Analysis Queries.html
│
├── dashboard/
│   ├── Customer_Support_Analytics.pbix
│
├── images/
│   ├── customer_support_performance.png
│   ├── chatbot_effectiveness.png
│   ├── cost_operational_impact.png
│
└── README.md
```

---

## Future Enhancements

Future iterations of this project will include:

* Voice of Customer sentiment analysis
* Silent churn risk identification
* Customer segmentation
* Predictive analytics
* Executive summary dashboard
* Customer retention analysis

---

## Author

**Adenireti Jaiyeoba**

Business Analytics & Insights Student | Product & Customer Experience Analytics Enthusiast

Ontario, Canada
