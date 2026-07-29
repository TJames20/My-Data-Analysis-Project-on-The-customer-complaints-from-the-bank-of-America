# Bank of America Consumer Complaints Analysis (2017–2023)

**Project Overview**
This project examines consumer complaints filed against Bank of America between 2017 and 2023, using publicly available data from the Consumer Financial Protection Bureau (CFPB). The goal is to surface complaint patterns, assess how effectively the bank responds to customers, and generate insights that could strengthen customer experience, streamline operations, and support better risk management.

**Problem Statement**
Banks and other financial institutions field an enormous volume of customer complaints each year, which makes it hard to spot recurring problems and take corrective action. This project turns raw complaint records into clear, actionable insights that leadership can use to make better decisions.

**Business Questions**
This analysis sets out to answer:

1. Which states generate the highest volume of complaints?
2. Which banking products are complained about most often?
3. How has complaint volume shifted over time?
4. How well does the bank respond to complaints?
5. Where are the opportunities to improve customer satisfaction?

**Dataset**
**Source:** Consumer Financial Protection Bureau (CFPB)
**Time Period:** 2017–2023

**Dataset Summary**
- Total Rows: 62,516
- Total Columns: 12

**Fields Included**
- Complaint ID
- Date Submitted
- Date Received
- State
- Product
- Sub-product
- Issue
- Sub-issue
- Submitted Via
- Company Public Response
- Company Response to Consumer
- Timely Response

**Tools Used**
- Microsoft Excel
- Power BI

**Data Cleaning**
Before analysis, the dataset was prepared as follows:

- Converted the raw data into an Excel Table for easier management
- Checked thoroughly for duplicate records (none were found)
- Expanded abbreviated state codes into full state names
- Handled missing values by labeling:
  - Blank Timely Response entries as "Pending"
  - Blank Sub-product, Sub-issue, and Company Public Response entries as "To be confirmed"
- Structured the cleaned data for import into Power BI

**Data Analysis**

**Power BI Development**
The following were built to support analysis:
- A dedicated Date Table
- Custom DAX measures, including:
  - Total Complaints
  - Timely Response Rate
  - Pending Response Rate
  - Total Products
  - Total States
  - Timely Responses
  - Pending Responses
  - Untimely Responses

**Dashboard**
The final report includes two interactive dashboard pages.

**Page 1 — Customer Complaints Overview**
This page provides a high-level view of:
- Overall complaint volume
- Complaint trends across 2017–2023
- The most common complaint categories
- How the company responds to complaints
- Complaint distribution across states and submission channels

<img width="1328" height="743" alt="Bank of America Customer Compliant Dashboard 1" src="https://github.com/user-attachments/assets/bc63ceed-b3b7-47af-bedd-82428317b30e" />

**Page 2 — Complaint Trends & Response Performance**
This page dives deeper into:
- Key response performance metrics
- The breakdown of timely vs. untimely responses
- Complaint trends by quarter
- Timely response rates broken down by product
- A product-response performance matrix
- Interactive filtering options

<img width="1328" height="743" alt="Bank of America Customer Compliant Dashboard 1" src="https://github.com/user-attachments/assets/0735d352-ea0e-42a9-9967-e4d6ce6f8fd4" />

**Key Insights**

**Where Complaints Concentrate**
California generated the most complaints by far, with 13,709 total, followed by Florida and Texas.

**Checking & Savings Accounts Drive the Most Complaints**
With 24,814 complaints, Checking & Savings Accounts was the single most complained-about product category.

**Response Performance Is Strong**
The bank resolved complaints on time 93.77% of the time, reflecting a generally efficient complaint-handling process.

**Some Complaints Still Go Unresolved or Late**
Despite strong overall performance, more than 3,800 complaints were either still pending or received a late response.

**Q4 Sees a Drop in Complaint Volume**
Complaint volume consistently declined in the fourth quarter each year, which may point to seasonal patterns or improved service delivery during that period.

**Recommendations**
- Focus improvement efforts on the highest-complaint states.
- Simplify and streamline processes tied to Checking & Savings Accounts.
- Investigate root causes behind recurring complaint types.
- Implement SLA monitoring to reduce the number of pending complaints.
- Study and replicate practices used in low-complaint regions.

**Skills Demonstrated**
- Data Cleaning
- Data Transformation
- Power BI
- DAX
- Dashboard Design
- Data Visualization
- Business Intelligence
- Data Storytelling

**Project Files**
- Cleaned Dataset
- Power BI Dashboard (.pbix)
- Excel Workbook
- README
- Dashboard Screenshots

---

**Author:**
James Theophilus Hussaini
theophilusjames9@gmail.com
Corporate Governance | Data Analytics | Power BI | Excel | AI for Business
