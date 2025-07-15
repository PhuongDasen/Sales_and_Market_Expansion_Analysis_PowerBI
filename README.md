<p align="center">
  <img src="https://github.com/user-attachments/assets/3552fdb1-671e-4b7c-8b2d-9b2e15e3889c" width="90%">
</p>
<h1> 📊 Sales Performance & Market Expansion for a global Superstore with PowerBI</h1><br>
Author: Phuong Dasen<br>
Tool: PowerBI<br>

## 📌 Table of Contents
- [📌 Background & Overview](#-background--overview)
- [📁 Dataset Description & Data Structure](#-dataset-description--data-structure)
- [🧠 Design Thinking Process](#-design-thinking-process)
- [📊 Key Insights & Visualizations](#-key-insights--visualizations)
- [🔍 Recommendations](#-recommendations) 
  
## [📌 Background & Overview](#-background--overview)

## 🔍 What is this project about?<br>
- Superstore is a global reteil company sepcializing in selling consumer goods across furniture, office supplies, and technology through its eCommerce Platform.<br>
- Analyzes company-wide sales data to assess performance across products, regions, and customer segments.<br>
- Deliver actionable insights through a Power BI dashboard for strategic decision-making and market expansion.<br>

## 👤 Who is this project for?<br>
- Senior management, including sales and regional directors.<br>  

## ❓ Business questions<br>
- Which regions, categories, and products generate the most sales and profit? <br>
- Where are the gaps or opportunities for improving performance or expanding into new markets?<br>

## [📁 Dataset Description & Data Structure](#-dataset-description--data-structure)
## 📌 Data Source
* Source : Kaggle<br>
* Size:<br>
        - The Orders table contains 51,290 records<br>
        - The People table contains 13 records<br>
        - The Returns table contains 1,172 records<br>
        - Format: .csv<br>
        
## 📊 Data Structure & Relationships<br>
## 1️⃣ Tables Used:
The dataset consists of three tables:
<details>
<summary>🔽 Table 1: Orders - Contains detailed transaction and customer information</summary>
<img width="2800" alt="Screenshot 2025-07-02 at 8 37 03 PM" src="https://github.com/user-attachments/assets/c020dce8-b8da-4125-87ab-4edeb0f111a9" />
<br>
</details>
<details>
<summary>🔽 Table 2: Returns – Stores data on returned orders</summary>
<img width="1500" alt="Screenshot 2025-07-02 at 8 38 03 PM" src="https://github.com/user-attachments/assets/3fc1168d-6c3a-4249-b3b6-223d735fb081" />
<br>
</details>

<details>
<summary>🔽 Table 3: People – Holds information about sales representatives</summary>
<img width="1500" alt="Screenshot 2025-07-02 at 8 38 28 PM" src="https://github.com/user-attachments/assets/1a60b3da-e5f5-4083-bf3d-eca8ed202f13" />
<br>
</details>

<details>
<summary>🔽 Data Dictionary</summary>
<img width="1000" alt="Screenshot 2025-07-02 at 8 38 28 PM" src="https://github.com/user-attachments/assets/e4c9474f-1c34-4264-af36-dcdbf2351208" />
<br>
</details>

## 2️⃣ Data Relationships:
<img width="1500" alt="Screenshot 2025-07-02 at 8 49 25 PM" src="https://github.com/user-attachments/assets/58e02e22-a7ed-48d4-86a9-162d1bc386ca" /><br>
---
## [🧠 Design Thinking Process](#design-thinking-process)
<h2>1️⃣ Step 1 - Empathize </h2><br>

<img width="1900" height="700" alt="Screenshot 2025-07-15 at 10 37 13 AM" src="https://github.com/user-attachments/assets/04af0965-5da9-4b53-8470-49d500288f29" /><br>
<img width="1900" height="700" alt="Screenshot 2025-07-15 at 10 37 33 AM" src="https://github.com/user-attachments/assets/e70b8998-dd6c-48ec-af87-dfd1bdb7f2a9" /><br>

<h2>2️⃣ Step 2 - Define Point of view </h2><br>

<img width="1110" height="629" alt="Screenshot 2025-07-15 at 10 46 28 AM" src="https://github.com/user-attachments/assets/e442af23-1ae8-4093-9ac4-f328bb488135" /><br>

<h2>3️⃣ Step 3 - Ideate </h2><br>

<img width="1900" height="700" alt="Screenshot 2025-07-15 at 10 37 56 AM" src="https://github.com/user-attachments/assets/7f6061fc-d067-4760-b256-e32556aeaf97" /><br>
<img width="1900" height="700" alt="Screenshot 2025-07-15 at 10 38 08 AM" src="https://github.com/user-attachments/assets/cb9cee26-1bb7-417d-a4f2-601f5f61a1d9" />
<br>

## [📊 Key Insights & Visualizations](#-key-insights--visualizations)

<h2>1. Business Overview </h2>
<img width="1900" alt="Screenshot 2025-07-11 at 1 53 20 PM" src="https://github.com/user-attachments/assets/745cbac5-efc5-4d37-b5ee-db15ab606e4f" /><br>

## 🔍 Key Insights
### 🌍 **Business Overview Dashboard**

- 📍 **Strong Regional Performance:** *Central* and *South* regions drive highest total sales (**$2.8M** and **$1.6M**), signaling strong market opportunities.
- 📅 **Most Profitable Year:** *2014* shows peak profit performance—worth investigating past strategies for replication.
- 📦 **Low Return Rates Across Products:** Product categories maintain high satisfaction, validating current quality and service models.
- 📈 **Sales Momentum:** *YoY Sales Growth* of **+26.3%** confirms successful business strategy and readiness for scale.

<h2>2. Product & Person </h2>
<img width="1180" height="677" alt="Screenshot 2025-07-11 at 3 07 48 PM" src="https://github.com/user-attachments/assets/8fd7110f-ea2f-4a07-aeb5-c59b361794f9" /><br>

## 🔍 Key Insights
### 🧑‍💼 **Product & Person Dashboard**

- 💼 **Top Performer:** *Anna Andreadi* generated the highest revenue (**$2.82M**), outperforming all others—ideal for modeling best practices in sales training.
- 🪑 **High-Revenue Sub-Categories:** *Phones* and *Chairs* lead in net revenue (**$1.61M** and **$1.41M**)—suggesting areas for increased marketing and procurement focus.
- ✅ **Low Return Rate:** Only **2.29%** of total orders were returned, indicating excellent product satisfaction and fulfillment efficiency.
- 👥 **Top Customers Identified:** Loyal buyers like *Tom Ashbrook* (40.49K orders) should be targeted with loyalty and retention strategies.

## [🔍 Recommendations](#-recommendations)
## ✅ Recommendations for Action

1. 🧑‍🏫 **Leverage top sales performers** (e.g., Anna Andreadi) as internal mentors to share successful selling strategies with other team members.
2. 🎯 **Focus marketing and inventory planning** on high-revenue sub-categories like Phones and Chairs to maximize ROI.
3. 💳 **Develop loyalty programs** for high-frequency customers to increase retention and lifetime value.
4. 🌐 **Invest in high-performing regions** (Central and South) with tailored marketing campaigns and logistical support for market expansion.

<b>2. Product Focus:</b><br>
- Invest in Phones and Copiers<br>
- Maintain strong push on Office Supplies category.<br>
- Consider reviewing and improving the quality or return policy for Binders, given the high retuen rate <br>




  


