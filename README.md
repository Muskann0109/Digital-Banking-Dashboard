# 📊 Digital Banking Performance Dashboard  
### A Managerial 360° Banking Insights Dashboard | Power BI | Excel | DAX

---

## 🚀 Project Overview  
This project presents a complete **Digital Banking Performance Dashboard** built using **Power BI**, **Excel**, and **DAX**, based entirely on realistic dummy datasets.  
It provides a **managerial-level 360° view** of banking operations, including:

- Customer Acquisition  
- Cross-Sell Performance  
- Lead Funnel Conversion  
- Customer Complaints & TAT  
- Channel Usage & Digital Adoption  

The dashboard is designed to mirror real corporate BI reporting while using 100% free tools and synthetic data.

---

## 🛠️ Tech Stack  
- **Power BI Desktop (Free)**  
- **Excel / CSV files**  
- **Power Query**  
- **DAX Measures**  
- **Star Schema Data Modeling**

---

## 📂 Datasets (Dummy, Self-Created)  
The solution uses 5 generated CSV datasets:

1. **Customer Acquisition** (date, product type, channel, branch)  
2. **Cross-Sell Data** (primary-product → cross-sold product)  
3. **Lead Funnel Data** (lead stages & conversion path)  
4. **Customer Complaints** (category, TAT, status)  
5. **Channel Usage** (ATM, mobile app, web transactions)

All datasets follow standardized date formats, no duplicates, cleaned & transformed in Power Query.

---

## 🧱 Data Model  
A clean **star schema** was built with:

- **Dim_Date**  
- **Dim_Branch**  
- Five fact tables (acquisition, cross-sell, leads, complaints, channel usage)

Each fact table connects to Dim_Date and Dim_Branch using a **many-to-one** single-direction relationship.

---

## 🧮 Key DAX Measures  
The dashboard includes KPI measures such as:

- **Total Acquisitions**  
- **Cross-Sell Conversion %**  
- **Lead Stage Counts & Funnel Conversion %**  
- **Total Complaints & Avg TAT**  
- **Digital Adoption %**  
- **Rolling 7-day Metrics**  

All measures are created in a dedicated **__Measures** table.

---

## 📊 Dashboard Pages  

### **1️⃣ Executive Summary**
- Top KPIs (Acquisition, Cross-Sell %, Lead Conversion %, Avg TAT, Digital Adoption %)  
- Combined acquisition & digital trend  
- Branch comparison chart  

### **2️⃣ Customer Acquisition**
- Daily acquisition trend  
- Product-wise bar chart  
- Channel-wise donut  
- Branch heatmap  

### **3️⃣ Cross-Sell Performance**
- Product cross-sell matrix  
- Branch-wise cross-sell  
- Cross-sell conversion KPI  

### **4️⃣ Lead Conversion Funnel**
- Funnel chart  
- Drop-off analysis  
- Leads over time trend  

### **5️⃣ Complaints & Service Quality**
- Category volume  
- Resolved vs Pending  
- Avg TAT card  
- Monthly TAT trend  

### **6️⃣ Channel Performance**
- Digital adoption KPI  
- Digital transactions trend  
- Stacked area of App/Web/ATM  
- Branch vs Digital usage (if available)

---

## 🎨 Visual & UX Features  
- Conditional formatting (heatmaps)  
- Drill-through for Branch Detail  
- Bookmark navigation (optional)  
- Sync slicers (Date & Branch) across pages  
- Buttons & clean color theme

---

## 📝 How to Use the Project  
1. Download or clone this repository  
2. Open `Digital_Banking_Dashboard.pbix` in Power BI Desktop  
3. Explore report pages from Executive Summary → detailed insights  
4. Modify datasets or visuals as needed  
5. Export dashboard to PDF for presentations

---
 
