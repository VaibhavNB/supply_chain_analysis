# 📦 Supply Chain Analytics Project

---

## 📊 Project Overview

This project performs an end-to-end analysis of supply chain operations using Python and Power BI to uncover inefficiencies, optimize performance, and enable data-driven decision-making.

The analysis transforms raw transactional data (12,000+ records) into actionable business insights across delivery performance, product demand, supplier efficiency, and customer experience.

---

## 🎯 Business Problem

Modern supply chains face multiple operational challenges:

- Delayed or failed deliveries  
- Inefficient supplier performance  
- Poor warehouse allocation  
- High return rates  
- Lack of real-time performance visibility  

This project aims to identify where inefficiencies occur, what drives them, and how they can be improved using data analytics.

---

## 🧠 Objectives

- Perform data cleaning and preprocessing on raw supply chain data  
- Conduct in-depth Exploratory Data Analysis (EDA)  
- Identify patterns in delivery performance, returns, and product demand  
- Build KPI-driven insights for business decision-making  
- Develop an interactive Power BI dashboard for monitoring operations  

---

## 📁 Project Structure

supply_chain_analysis/
│
├── data/                     # Raw and cleaned datasets  
├── notebooks/                # Data cleaning & EDA notebooks  
├── visuals/                  # Generated plots and charts  
├── dashboard/                # Power BI dashboard files  
├── README.md                 # Project documentation  

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy)  
- Matplotlib & Seaborn (EDA Visualizations)  
- Power BI (Dashboard & KPI Monitoring)  
- Jupyter Notebook  

---

## 🧹 Data Cleaning & Preparation

The dataset was preprocessed to ensure accuracy and consistency:

- Converted date columns to datetime format  
- Handled missing values (especially customer ratings)  
- Removed duplicates and invalid records  
- Standardized categorical values (supplier, warehouse, city)  
- Resolved inconsistent entries (e.g., "Unknown")  

---

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted to uncover patterns across multiple dimensions:

- Delivery performance trends  
- Product demand and pricing behavior  
- Supplier and warehouse performance  
- Return patterns and operational inefficiencies  
- Time-based order trends  

### Key Visualizations:
- Bar charts (product, supplier, city analysis)  
- Line charts (order trends over time)  
- Histograms (rating distribution)  
- Heatmaps (correlation analysis)  

---

## 📌 Key Business Insights

- Delivery performance is inconsistent, with cancellations and pending orders indicating operational inefficiencies  
- Revenue is highly concentrated among a small subset of products (Pareto effect)  
- Supplier performance varies significantly, impacting delivery success and returns  
- Warehouse allocation inconsistencies (e.g., "Unknown") highlight tracking issues  
- Customer satisfaction is moderate (~3/5), with missing feedback data limiting visibility  
- Returns are strongly linked to delivery issues and product performance  

---

## 📊 Key Performance Indicators (KPIs)

The following KPIs were developed to measure supply chain efficiency:

- OTIF (On-Time In-Full %) — Measures timely and successful deliveries  
- Delivery Success Rate — Delivered Orders / Total Orders  
- Return Rate — Returned Orders / Total Orders  
- Average Delivery Time — Based on order & delivery dates  
- Revenue — (Price × Quantity) - Discount  
- Delivered to Returned Ratio — Fulfillment quality indicator  

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was built to monitor supply chain performance across 5 key areas:

1. Executive Overview  
2. Delivery Performance Analysis  
3. Product & Revenue Analysis  
4. Supplier & Warehouse Performance  
5. Customer Experience & Returns  

### Features:
- KPI tracking (OTIF %, Return Rate, Revenue)  
- Multi-dimensional filtering (city, supplier, product)  
- High-risk order identification  
- Data-driven operational insights  


---

## 💡 Business Recommendations

- Improve delivery operations by enforcing SLA-based monitoring (OTIF tracking)  
- Optimize supplier performance using KPI benchmarking  
- Eliminate warehouse mapping issues for better logistics visibility  
- Focus on high-performing products while improving low performers  
- Reduce return rates through quality and fulfillment improvements  
- Implement continuous KPI monitoring using dashboards  

---

## 📈 Future Improvements

- Add real-time data pipeline for automated reporting  
- Implement predictive models for delivery delays  
- Build supplier performance scoring system  
- Enhance dashboard with advanced analytics  
- Integrate demand forecasting models  

---

## 📸 Visualizations & Dashboard 

- Delivery performance charts
  <img width="1618" height="799" alt="2" src="https://github.com/user-attachments/assets/d9105165-04d5-4ebd-8574-4dbcad13de20" />

- Product revenue distribution
  <img width="1627" height="801" alt="5" src="https://github.com/user-attachments/assets/ded68579-c1e8-40d9-8078-e817a4604c9e" />

- Supplier efficiency visuals
  <img width="1618" height="790" alt="3" src="https://github.com/user-attachments/assets/a6b17dcd-d60d-42d9-afd1-bc0081723a98" />

- Customer rating analysis
- <img width="1596" height="797" alt="4" src="https://github.com/user-attachments/assets/92b8ea9e-9d1a-4d70-beec-a980901c2f9a" />

- Power BI dashboard screenshots  
<img width="1628" height="798" alt="1" src="https://github.com/user-attachments/assets/7090bebd-2332-46cc-bd48-e372cb1c11b8" />

---

## 🚀 How to Run This Project

Clone repository:
git clone https://github.com/VaibhavNB/supply_chain_analysis.git

Navigate to project folder:
cd supply_chain_analysis

Install dependencies:
pip install -r requirements.txt

Run Jupyter Notebook:
jupyter notebook

---

## 👨‍💻 Author

Vaibhav Badiger  
Aspiring Data Analyst | Python | SQL | Power BI  

---

## ⭐ Project Status

This project is actively evolving with ongoing improvements in:
- Dashboard design  
- KPI enhancement  
- Advanced analytics integration  

---

## 📬 Feedback

Feel free to connect or provide feedback to improve this project further.
