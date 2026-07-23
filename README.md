Bank Marketing Campaign Performance Analysis using Power BI

An interactive Power BI dashboard built to analyse bank marketing campaign performance and understand the factors influencing customer subscription outcomes. The project uses the Bank Marketing dataset from the UCI Machine Learning Repository and demonstrates an end-to-end data analytics workflow, including data cleaning, transformation, DAX calculations, data visualization, and business insight generation.

Objectives

The main objectives of this project are:

* Analyse the performance of bank marketing campaigns.
* Understand customer subscription behaviour.
* Calculate key marketing performance indicators and KPIs.
* Analyse **Subscription Rate by Call Duration**.
* Analyse **Subscription Rate by Campaign Contact Frequency**.
* Identify customer segments with stronger campaign responses.
* Understand patterns in customer and campaign data.
* Build an interactive and user-friendly Power BI dashboard.
* Generate data-driven insights to support targeted marketing strategies.
* Provide recommendations for improving campaign effectiveness and resource allocation.

Dataset Information

The dataset used in this project is the **Bank Marketing Dataset**, obtained from the **UCI Machine Learning Repository**.

The dataset contains information related to direct marketing campaigns conducted through phone calls by a Portuguese banking institution. The main objective is to predict whether a client will subscribe to a **bank term deposit**.

Dataset Details

| Attribute           | Details                                               |
| ------------------- | ----------------------------------------------------- |
| **Dataset Name**    | Bank Marketing                                        |
| **Source**          | UCI Machine Learning Repository                       |
| **Domain**          | Banking / Marketing Analytics                         |
| **Dataset Type**    | Multivariate                                          |
| **Task**            | Classification                                        |
| **Instances**       | 45,211                                                |
| **Features**        | 16 input features                                     |
| **Target Variable** | `y` – Whether the client subscribed to a term deposit |
| **Missing Values**  | No                                                    |

🔗 Original Dataset Source

[UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing?utm_source=chatgpt.com)

Key Dataset Attributes

The dataset includes customer demographic information, financial information, current marketing campaign details, and previous campaign outcomes.

Important attributes include:

* `age` – Age of the customer
* `job` – Type of job
* `marital` – Marital status
* `education` – Education level
* `default` – Credit default status
* `balance` – Average yearly balance
* `housing` – Housing loan status
* `loan` – Personal loan status
* `contact` – Contact communication type
* `day` – Day of the month when the customer was contacted
* `month` – Month of the campaign contact
* `duration` – Duration of the last contact
* `campaign` – Number of contacts performed during the current campaign
* `pdays` – Number of days since the customer was last contacted in a previous campaign
* `previous` – Number of contacts performed before the current campaign
* `poutcome` – Outcome of the previous marketing campaign
* `y` – Target variable indicating whether the customer subscribed to a term deposit

Tools & Technologies Used

Power BI

Used for:

* Interactive dashboard development
* Data visualization
* Data modelling
* KPI development
* Business intelligence reporting

Power Query

Used for:

* Data cleaning
* Data transformation
* Data type standardization
* Data preparation
* Creating analysis-ready data

DAX

Used for:

* Creating calculated measures
* KPI calculations
* Subscription rate analysis
* Campaign performance analysis
* Call duration analysis

Microsoft Excel

Used where applicable for:

* Initial data inspection
* Data preparation
* Data validation

Data Cleaning and Transformation

The following data preparation and transformation steps were performed:

1. Imported the Bank Marketing dataset into Power BI.
2. Reviewed the dataset structure and available attributes.
3. Checked and standardized data types.
4. Reviewed missing and inconsistent values.
5. Checked for duplicate records where applicable.
6. Standardized categorical values for consistent analysis.
7. Prepared customer and campaign attributes for analysis.
8. Created derived analytical fields for dashboard reporting.
9. Converted **Call Duration** into meaningful categories for comparison.
10. Prepared the transformed dataset for Power BI visualization.
11. Created DAX measures to calculate key campaign performance metrics.

Data Analysis & DAX

DAX measures were used to create important analytical KPIs for the dashboard.

Key metrics include:

* **Total Customers**
* **Total Subscribers**
* **Total Non-Subscribers**
* **Subscription Rate (%)**
* **Average Call Duration**
* **Average Campaign Contacts**
* **Subscription Rate by Call Duration**
* **Subscription Rate by Campaign Contact Frequency**

Subscription Rate

The Subscription Rate measures the percentage of customers who subscribed to the promoted bank term deposit.

This KPI provides an overall indication of the effectiveness of the marketing campaign.

Call Duration Analysis

The original `duration` field was transformed into **Call Duration Categories** to make it easier to compare subscription performance across different call-duration groups.

This analysis helps understand the relationship between customer interaction time and subscription outcomes.

Campaign Contact Analysis

The `campaign` field was analysed to understand how the number of contacts made during the campaign relates to customer subscription behaviour.

Dashboard Features

The Power BI dashboard provides an interactive view of bank marketing campaign performance.

Key Dashboard Components

1. KPI Cards

Displays important campaign performance metrics such as:

* Total Customers
* Total Subscribers
* Subscription Rate
* Average Call Duration
* Average Campaign Contacts

<img width="569" height="54" alt="Screenshot 2026-07-23 191709" src="https://github.com/user-attachments/assets/251f3d0a-3e08-483f-8cd7-b1ec5f6c8468" />


2. Subscription Rate Analysis

Provides an overview of the percentage of customers who subscribed to the bank's term deposit

3. Subscription Rate by Call Duration

Shows the subscription rate across different call-duration categories.

This helps identify patterns between the length of customer interactions and subscription performance.

4. Subscription Rate by Campaign Contact

Analyses subscription performance based on the number of contacts made with customers during the campaign.

5. Customer Segmentation

Enables analysis of customer subscription behaviour across different attributes such as:

* Age
* Job
* Education
* Marital Status
* Housing Loan
* Personal Loan
* Financial Characteristics

6. Interactive Filters and Slicers

Users can dynamically filter and explore campaign performance based on available customer and campaign attributes.

7. Interactive Visualizations

The dashboard uses Power BI interactive features such as:

* Cards
* Bar Charts
* Column Charts
* Line Charts
* Scatter Plots
* Tables
* Slicers
* Filters
* Cross-filtering

📸 Dashboard Screenshot

<img width="635" height="356" alt="Screenshot 2026-07-23 191548" src="https://github.com/user-attachments/assets/15920b11-3ed1-499d-9cd9-10d81f5885d0" />
<img width="633" height="355" alt="Screenshot 2026-07-23 191610" src="https://github.com/user-attachments/assets/53b67b28-3d63-416f-a866-6f1d959924c7" />
<img width="633" height="355" alt="Screenshot 2026-07-23 191629" src="https://github.com/user-attachments/assets/630c27a5-0a39-439a-8c48-3dcda534e0ed" />
<img width="634" height="357" alt="Screenshot 2026-07-23 191651" src="https://github.com/user-attachments/assets/f13c9d9c-83b7-4fd3-be6c-788489b7421f" />

🔍 Key Findings

The dashboard focuses on the following key findings and analytical areas:

1. Overall Subscription Performance

The **Subscription Rate** provides an overall measure of how effectively the marketing campaign converts contacted customers into term-deposit subscribers.

**Metric:** Subscription Rate (%)

2. Call Duration and Subscription

The **Subscription Rate by Call Duration** visual helps identify differences in customer subscription behaviour across different call-duration categories.

This analysis provides insights into customer engagement during marketing calls.

**Metric:** Subscription Rate (%) by Call Duration Category

3. Campaign Contact Frequency

The **Subscription Rate by Campaign Contact** visual analyses how subscription performance varies with the number of contacts made during the campaign.

This helps evaluate the potential impact of repeated customer outreach.

**Metric:** Subscription Rate (%) by Campaign Contact Frequency

4. Customer Segmentation

Customer attributes can be used to identify segments that show stronger or weaker responses to the marketing campaign.

This supports more targeted customer outreach and campaign planning.

5. Marketing Campaign Effectiveness

The dashboard provides a consolidated view of campaign performance, enabling users to monitor KPIs and explore customer response patterns through interactive filtering.

Business Insights

Based on the dashboard analysis, the project provides the following business perspectives:

* Identify customer groups with stronger subscription potential.
* Understand the relationship between call duration and subscription outcomes.
* Analyse the impact of campaign contact frequency on customer response.
* Identify customer segments that may require different marketing approaches.
* Support targeted marketing campaigns using data-driven insights.
* Improve campaign planning and resource allocation.
* Monitor campaign KPIs through an interactive Power BI dashboard.

Recommendations

Based on the analytical approach, the following recommendations can support future marketing campaigns:

1. **Focus on High-Response Segments**
   Prioritize customer groups that demonstrate stronger historical subscription performance.

2. **Optimize Customer Conversations**
   Use call-duration analysis to understand effective customer engagement rather than focusing only on increasing call length.

3. **Review Contact Frequency**
   Analyse the effectiveness of repeated customer contacts and avoid unnecessary outreach where additional contacts do not improve results.

4. **Improve Customer Targeting**
   Use demographic and financial characteristics to develop more targeted marketing strategies.

5. **Monitor Campaign Performance**
   Track subscription rate and other KPIs regularly to evaluate campaign effectiveness.

6. **Use Data-Driven Decision Making**
   Leverage Power BI insights to support marketing strategy, campaign planning, and resource allocation.

Analytical Approach

The project follows a structured analytical framework:

Descriptive Analytics

Understand overall campaign performance through KPIs such as:

* Total Customers
* Total Subscribers
* Subscription Rate
* Average Call Duration
* Average Campaign Contacts

Diagnostic Analytics

Explore factors associated with customer subscription behaviour, including:

* Call Duration
* Campaign Contact Frequency
* Customer Segments
* Previous Campaign Outcomes

Predictive Perspective

Historical campaign patterns can be used as a foundation for identifying customer segments that may be more likely to subscribe in future campaigns.

Prescriptive Perspective

Use identified patterns to improve customer targeting, optimize campaign contact strategies, and allocate marketing resources more effectively.

Skills Demonstrated

This project demonstrates practical skills in:

* Power BI
* DAX
* Power Query
* Data Cleaning
* Data Transformation
* Data Modelling
* Data Visualization
* KPI Development
* Dashboard Development
* Marketing Analytics
* Customer Analytics
* Campaign Performance Analysis
* Business Intelligence
* Descriptive Analytics
* Diagnostic Analytics
* Data-Driven Decision Making
* Business Insight Generation

Project Outcome

The **Bank Marketing Campaign Analysis** project transforms raw banking marketing data into an interactive business intelligence solution using Power BI.

The dashboard enables users to explore customer subscription behaviour, campaign contact frequency, call duration, and customer segments. The resulting insights can help stakeholders understand campaign effectiveness and support more targeted and data-driven marketing decisions.

This project demonstrates an end-to-end **Data Analyst workflow**, from data preparation and transformation to dashboard development and business insight communication.

Author

**Bhavya Chellapandian**

**Role:** Aspiring Data Analyst | Power BI Developer

**Skills:** Power BI | DAX | Power Query | Excel | Data Analytics | Data Visualization

🔗 Connect With Me

* LinkedIn: [Bhavya Chellapandian on LinkedIn](https://www.linkedin.com/in/bhavya-chellapandian?utm_source=chatgpt.com)
* GitHub: [Bhavya Chellapandian on GitHub](https://github.com/Bhavya-Chellapandian?utm_source=chatgpt.com)

---

📚 Dataset Reference

Moro, S., Rita, P., & Cortez, P. (2014). **Bank Marketing [Dataset]. UCI Machine Learning Repository.**

**Original Dataset:** [UCI Machine Learning Repository – Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing?utm_source=chatgpt.com)
