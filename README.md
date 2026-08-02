#  Bank Customer Analysis Dashboard

##  Project Overview

This project presents an interactive **Power BI Dashboard** built using the **Bank Marketing Dataset**. The dashboard provides comprehensive insights into customer demographics, financial profiles, and marketing campaign performance to support data-driven business decisions.

The report is divided into three analytical pages:

- Executive Overview
- Customer Analysis
- Campaign Analysis

---

##  Project Objectives

- Analyze customer demographics.
- Evaluate subscription performance.
- Identify customer segments with the highest subscription rates.
- Analyze the effectiveness of marketing campaigns.
- Monitor financial indicators and customer behavior.
- Support strategic decision-making through interactive visualizations.

---

##  Dataset

**Dataset:** Bank Marketing Dataset

The dataset contains customer demographic information, financial attributes, and campaign-related variables collected from a Portuguese banking institution.

### Main Features

| Feature | Description |
|---------|-------------|
| Age | Customer age |
| Job | Customer occupation |
| Marital | Marital status |
| Education | Education level |
| Balance | Average yearly account balance |
| Housing | Housing loan status |
| Loan | Personal loan status |
| Contact | Contact communication type |
| Duration | Call duration |
| Campaign | Number of contacts during the campaign |
| Previous | Number of previous contacts |
| Pdays | Days since last contact |
| Target | Subscription outcome (Yes/No) |

---

# Dashboard Pages

---

## 1️ Executive Overview

Provides a high-level summary of the campaign performance through KPIs and business metrics.

### KPIs

- Total Customers
- Total Subscribers
- Total Non-Subscribers
- Subscription Rate
- Average Balance
- Average Campaign Calls
- Average Call Duration

### Visualizations

- Customers by Month
- Average Balance by Education
- Average Balance by Month

---

##  Customer Analysis

Focuses on customer demographics and financial characteristics.

### Visualizations

- Customers by Job
- Subscription Rate by Job
- Customers by Education
- Customers by Marital Status
- Customers by Age Group
- Customers by Housing Loan
- Customers by Personal Loan

---

##  Campaign Analysis

Analyzes campaign effectiveness and customer interactions.

### Visualizations

- Average Call Duration by Subscription
- Subscription Rate by Contact Type
- Average Days Since Previous Contact
- Average Previous Contacts
- Interactive Filters

---

# Interactive Filters

Users can dynamically filter the dashboard using:

- Subscription Status
- Job
- Education
- Month

---

#  Key Insights

- Students have the highest subscription rate.
- Retired customers also demonstrate strong subscription performance.
- Cellular communication achieves higher subscription rates than other contact methods.
- Customers who subscribed generally had longer call durations.
- Most customers belong to the 30–39 age group.
- Secondary education represents the largest customer segment.
- Customer activity peaks during Month 5.
- Housing and personal loans influence customer distribution.

---

# Tools & Technologies

- Power BI Desktop
- Power Query
- DAX

---

# Dashboard Preview

## Executive Overview

<p align="center">
  <img src="Images/Executive%20Overview.png" width="900">
</p>

---

## Customer Analysis

<p align="center">
  <img src="Images/Customer%20Analysis.png" width="900">
</p>

---

## Campaign Analysis

<p align="center">
  <img src="Images/Campaign%20Analysis.png" width="900">
</p>


---

# Business Recommendations
## 1. Focus marketing efforts on high-conversion customer segments.

Students and retired customers exhibit the highest subscription rates. Allocate a larger portion of the marketing budget to these segments to maximize campaign effectiveness.

## 2. Prioritize cellular communication.

Customers contacted via cellular show better subscription performance than other contact methods. Future campaigns should prioritize mobile communication whenever possible.

## 3. Improve call quality rather than increasing call frequency.

Customers who subscribed generally had longer average call durations, indicating that meaningful conversations are more effective than making additional calls.

## 4. Optimize customer targeting.

Most customers belong to the 30–39 age group, making this segment an important target for future campaigns while continuing to explore opportunities in underrepresented age groups.

## 5. Personalize marketing campaigns based on customer profiles.

Develop customized offers according to customer characteristics such as job, education level, and financial status to improve engagement and increase subscription rates.

## 6. Monitor campaign performance monthly.

Customer activity varies across months. Marketing managers should analyze monthly trends and schedule campaigns during periods with higher customer engagement.

## 7. Improve customer data quality.

A noticeable portion of records contains "Unknown" values (e.g., contact type and education). Improving data collection practices will enable more accurate customer segmentation and better marketing decisions.

## 8. Build predictive models for campaign targeting.

Leverage machine learning models to identify customers with the highest probability of subscribing before launching future campaigns. This can reduce campaign costs while increasing conversion rates.

---

# Expected Business Impact
* Increase subscription conversion rates by targeting high-potential customer segments.
* Reduce unnecessary marketing costs through better customer targeting.
* Improve campaign efficiency by prioritizing the most effective communication channels.
* Enhance customer engagement through personalized marketing strategies.
* Support management with data-driven decision making using interactive dashboards.

---

#  Project Structure

```
Bank-Customer-Analysis/
│
├── Dashboard.pbix
├── Dataset.csv
├── Images/
│   ├── Executive Overview.png
│   ├── Customer Analysis.png
│   └── Campaign Analysis.png
└── README.md
```

---

#  How to Use

1. Download the repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Refresh the dataset if needed.
4. Explore the dashboard using the interactive slicers.

---

#  Author

## Abdelrhman Khalil

AI & Machine Learning Graduate | Data Analyst | Business Intelligence Enthusiast

 **Email**  
abdulrhman.khlil.abdallah@gmail.com

 **LinkedIn**  
https://www.linkedin.com/in/abdulrahman-khalil-abdallah/

 **GitHub**  
https://github.com/ABDELRHMAN4004

---

##  If you found this project useful, don't forget to give it a star!
