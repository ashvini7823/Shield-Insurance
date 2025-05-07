# 🛡️ Shield Insurance

This Power BI project was developed as part of my virtual internship at **AtliQ Technologies** through the **CodeBasics Data Analytics Bootcamp**. It focuses on analyzing customer behavior, sales performance, and policy insights to support data-driven decisions for a fictional insurance company.

---

## 🎯 Objective

To build an interactive Power BI dashboard that helps Shield Insurance understand its business performance across different cities, age groups, sales modes, and policies. This includes tracking revenue, customer growth, and settlement behavior to identify opportunities and areas for improvement.

---

## 🏢 About the Company

**Shield Insurance** is a leading 
insurance provider operating across major Indian cities. It offers a wide range of policies to customers of different age groups through both online and offline sales channels.

---

## 🧩 Task

- Analyze total revenue and total customers
- Track daily revenue and customer growth rates
- Understand revenue and customer trends by city, age group, and policy
- Assess performance by sales mode
- Provide actionable insights and recommendations

---

## 🗂️ Datasets Used

| **Table Name**       | **Description**                                                              |
|----------------------|------------------------------------------------------------------------------|
| `dim_customer`       | Customer details including ID, DOB, and city                                 |
| `dim_date`           | Date hierarchy including day, month, and week number                         |
| `dim_policies`       | Policy information including base cover and premium amount                   |
| `fact_premiums`      | Premium transactions by date, customer, policy ID, and sales mode            |
| `fact_settlements`   | Age-wise policy settlement percentage                                        |

---

## 🔗 Data Model Diagram

![Shield Insurance Data Model](https://github.com/user-attachments/assets/9df5c614-0a3b-4223-8620-36401cfad5ba)

A star schema was used with fact tables (`fact_premiums`, `fact_settlements`) connected to dimension tables (`dim_customer`, `dim_date`, `dim_policies`).

---

## 📊 Report Pages & Descriptions

### 1. Home Page  
- Project title and navigation icons linking to other report pages  
- Clean layout for user-friendly access
  
![shield insuarnce Dahboard_page-0001](https://github.com/user-attachments/assets/ce52b32d-743d-449f-8791-52dc6d91a0ee)

### 2. General View  
- Overview of revenue and customer trends by **city** and **age group**  
- Monthly performance tracking and switch between segment views
  
![shield insuarnce Dashboard_page-0002](https://github.com/user-attachments/assets/09212760-88b5-442a-a841-28773d6fbb35)

### 3. Sales Mode Analysis  
- Revenue and customer distribution across **sales channels**  
- Visual switch to analyze by **sales mode vs age group**
  
![shield insuarnce Dashboard_page-0003](https://github.com/user-attachments/assets/bd0c8c27-558c-4d40-ac3e-928629aa835f)

### 4. Age Group Analysis  
- Detailed policy preference by age group  
- Average settlement amounts  
- Revenue and customer trends across months
  
![shield insuarnce Dashboard_page-0004](https://github.com/user-attachments/assets/2fa5e4b2-3bbd-44f3-8d50-4a1a7f6c1757)

---

## 🔍 Key Insights

- 31–40 age group is the top contributor to both revenue and customer base
- Policy **POL2005HEL** generates the highest revenue, while **POL4321HEL** attracts the most customers
- **Delhi NCR** leads in both customer acquisition and revenue
- **Offline-Agent** channel is the most effective sales mode
- Peak business activity observed in **March**
- Younger age groups (18–24) underperform in both revenue and engagement

---

## ✅ Recommendations

- Promote top-performing policies and phase out or rewamp underperforming ones
- Continue investment in **Offline-Agent** while boosting digital sales channels
- Design targeted plans for **younger age groups**
- Replicate March campaign strategies across other months
- Re-evaluate performance in low-engagement cities like **Indore** and **Chennai**

---

## 📚 Learnings

- Developed hands-on experience in data modeling and DAX  
- Built a fully interactive, business-ready Power BI report  
- Strengthened skills in data storytelling, dashboard design, and stakeholder communication

---

## 🔗 Important Links

- 🔗 [Live Dahboard](https://app.powerbi.com/view?r=eyJrIjoiYzVlNTQ4YTUtOWY1Yy00Y2FkLWIzM2ItY2YwY2M0MGQzYTM5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=4b16207fa71d7bf9a39f)  
- 🔗 [Shield Insurance Dashboard](https://github.com/ashvini7823/Shield-Insurance/blob/d5170e26d02820cbc36cae5422ac165ddc3620e6/shield%20insuarnce%20Dashboard.pdf)
- 🔗 [Shield Insurance Presentation](https://github.com/ashvini7823/Shield-Insurance/blob/d5170e26d02820cbc36cae5422ac165ddc3620e6/Shield%20Insurance%20Presentation.pdf)
- 🔗 [Shield Insurance Documentation](https://github.com/ashvini7823/Shield-Insurance/blob/d5170e26d02820cbc36cae5422ac165ddc3620e6/Shield%20Insurance%20Documentation.pptx)
- 🔗 [Credits](https://github.com/ashvini7823/Shield-Insurance/blob/d5170e26d02820cbc36cae5422ac165ddc3620e6/CREDITS.md)
- 🔗 [Video Presenation](https://youtu.be/xYMLDGOVAss)

---

## 🙏 Thank You

Thank you for reviewing my project!  
This internship experience helped me apply analytics skills to solve real-world business problems.  
Feel free to explore the dashboard and reach out with any feedback.

