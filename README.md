# WELCOME. Hi, I'm Hong 👋  

I’m a Digital Marketing executive with over 2 years of experience in **content creation, campaign execution, customer insights, SEO Optimization, and Meta & Google Ads**.  
Along the way, I discovered my passion for **data and analytics**, and started building strong technical skills in **SQL, Python, Pandas, Power BI, and Tableau**.  

Currently, I’m exploring opportunities in **Marketing & Data Analysis**, where I can combine my business background with data-driven problem solving.  

🔎 My curiosity drives me to continually search for answers, uncover patterns, and transform data into meaningful stories that support informed decisions.  

Outside of work, I enjoy learning new things, hanging out, and sharing my knowledge.  

# PORTFOLIO DATA SCIENCE - PROJECT 
## I/ Sementation Project:

Customer segmentation is the best method to understand customer insight, which is the process of dividing customers into smaller groups based on their attributes. This generates insight clearer and more actionable when analyzing the entire population at once. 

In customer segmentation analytics, this can be done in various ways, such as Percentile Scoring (IQR), Cohort, RFM, K-Means Models, and so on.  

**What I did in the project:**
- Cleaned and pre-processed the Online Retail Dataset
- Performed exploratory data analysis (EDA) to identify trends and insights
- Applied percentile analysis to rank customers by value contribution
- Built cohort tables to track retention rate, churn rate and CLV
- Conducted RFM analysis to classify customers into actionable groups (e.g., loyal, at-risk, new)
- Applied K-Means clustering to uncover hidden customer segments beyond rule-based methods

**🛠 Dataset**
- Online Retail Dataset (UCI Machine Learning Repository)

- Transactional data including Invoice No., Product, Quantity, Invoice Date, Unit Price, and Customer ID.

<img width="1114" height="523" alt="Screenshot 2025-09-09 at 11 10 05" src="https://github.com/user-attachments/assets/16f354f5-13a8-4dad-b9d9-b4db6b396ae8" />

**🔧 Methods & Applications**
### **1. Percentile Scoring**
- The Percentile method is a simple yet powerful way to segment customers based on their attributes. In this project, I applied Excel, SQL (BigQuery), and Python to calculate and assign percentile scores to customers.
- By ranking customers into groups such as the top 10% or top 25%, I was able to identify high-value customers and compare them with lower-value segments.

*Percentile by using Excel*
<img width="1420" height="403" alt="Screenshot 2025-09-09 at 11 40 24" src="https://github.com/user-attachments/assets/9a81652c-c63e-476b-bfdf-9ae7f5a7e659" />

*Percentile by using SQL*
<img width="643" height="376" alt="Screenshot 2025-09-09 at 11 42 10" src="https://github.com/user-attachments/assets/f9c1699d-7118-49fe-83dc-3b474c6ddc87" />

### **2. Cohort Analysis**
- The Cohort method groups customers by their acquisition time and tracks how their behavior evolves over time. In this project, I used SQL and Python to build cohorts based on the month of first purchase, then calculated retention rates across subsequent months to analyze customer loyalty and churn patterns.

*Cohort Analysis using SQL combined with Google Sheet*
<img width="1219" height="551" alt="Screenshot 2025-09-09 at 14 43 44" src="https://github.com/user-attachments/assets/ecfaeef1-d2af-4e62-9ecf-6be38ddaed8f" />

*Cohort Analysis using Python*
<img width="1316" height="424" alt="Screenshot 2025-09-09 at 14 44 56" src="https://github.com/user-attachments/assets/3fa07b0e-f8ce-4070-9741-6436d62aae71" />

### **3. RFM Analysis**
- I calculated RFM 3 features: 
  - [Recency (R)]: How recently a customer purchased
  - [Frequency (F)]: How often they purchased
  - [Monetary (M)]: How much they spent

*Treemap Based on RFM*
<img width="824" height="548" alt="Screenshot 2025-09-09 at 15 09 12" src="https://github.com/user-attachments/assets/7a34ab8e-bfbf-48b5-84d2-1971f0d8f84f" />

### **4.KMeans Clustering**
- To uncover hidden customer segments beyond rule-based methods, I combined RFM features (Recency, Frequency, Monetary) and applied the K-Means clustering algorithm. The optimal number of clusters was determined using the Elbow Method, ensuring meaningful and well-separated customer groups for deeper business insights.
