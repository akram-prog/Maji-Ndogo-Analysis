# 💧 WEAVING THE DATA THREADS OF MAJI NDOGO'S NARRATIVE  
**Integrated Project: From Detecting Corruption to Designing Solutions**

---

## 📌 Project Overview  
The **Maji Ndogo Water Crisis Analysis** is a fictional but realistic case study exploring how **data analysis, SQL, and business intelligence** can improve access to water and strengthen accountability.  

The project unfolds in two key stages:  

### 🔹 Part 1 – Detecting Discrepancies & Corruption  
- Compared surveyor reports with an audit dataset.  
- Identified **193 discrepancies** in quality scores.  
- Ruled out water source type as the cause of errors.  
- Exposed **four employees** (Zuriel Matembo, Malachi Mavuso, Bello Azibo, Lalitha Kaburi) as responsible for misconduct.  

### 🔹 Part 2 – From Insights to Action  
- Combined multiple datasets to identify inequalities in water access.  
- Highlighted disparities between provinces, towns, and social groups.  
- Designed a `Project_progress` table for tracking repairs.  
- Proposed an actionable plan (new wells, filters, tap expansions, repair prioritization).  
- Developed **Power BI dashboards** to visualize the improvement plan, vendors, and regional disparities (`bi_dashboard/` folder).  

---

## 🔑 Key Insights  
- **193 audit discrepancies** → Human error or misconduct suspected.  
- **4 employees** were responsible for most inaccurate survey entries.  
- **43%** of residents rely on shared taps, often overcrowded (~2,000 per tap).  
- **31%** of homes have taps, but **45% are broken**.  
- **18%** of residents use wells, only **28% safe**.  
- Wait times exceed **120 minutes** at peak times (Saturdays, mornings, evenings).  
- Rural areas like **Amanzi** and provinces like **Sokoto** are the most underserved.  

---

## 🛠️ Plan of Action  
1. Drill wells to replace unsafe river sources.  
2. Install filters in wells (**RO for chemical**, **UV+RO for biological contaminants**).  
3. Expand shared taps where queues exceed 30 minutes; deploy temporary tankers.  
4. Repair failing infrastructure in **Amina, Lusaka, Zuri, Djenne, Amanzi**.  
5. Track interventions with the `Project_progress` SQL table.  

---

## 🗄️ Technologies Used  
- **MySQL** → Queries, joins, CTEs, database design  
- **SQL Views & Temporary Tables** → Modular analysis  
- **Jupyter Notebook** → Documenting queries and findings  
- **Power BI** → Dashboards showing national improvement plan, vendor analysis, and disparities  

---

## 📊 Dashboards  

### National Improvement Plan  
![Improvement Plan](images/Improvement_Plan.JPG)  

### Vendor & Location Analysis  
![Vendor Analysis](images/vendor_charges.JPG)  

---

## 📂 Repository Structure  
