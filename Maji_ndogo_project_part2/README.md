# 🌍 Maji Ndogo Water Crisis Analysis – Part 2  
**From Analysis to Action: Charting a Practical Path for Maji Ndogo’s Future**

---

## 📌 Project Overview  
This project is part of the larger **Maji Ndogo Water Crisis Analysis**, a fictional but data-driven case study. In this phase, we focus on **moving from insights to action**, by combining data across multiple tables, generating a comprehensive analysis, and building a **practical plan** for improving water access.  

The work includes:  
- Creating integrated SQL views for cross-table analysis.  
- Identifying **patterns of inequality in water access** across provinces and towns.  
- Designing a **Project Progress database table** to track interventions.  
- Transforming analysis into **actionable recommendations** for decision-makers.  

---

## 🔑 Key Insights  
- **43%** of citizens rely on **shared taps**, often overcrowded (2,000 people per tap).  
- **31%** of households have taps installed, but **45% are broken** due to failing infrastructure.  
- **18%** rely on **wells**, but only **28% are clean** (many polluted with biological or chemical contaminants).  
- Citizens face **long wait times** (often >120 minutes), with queues peaking on **Saturdays, mornings, and evenings**.  
- Access disparities exist: in provinces like **Sokoto**, many drink unsafe river water, while wealthier citizens enjoy in-home taps.  

---

## 🛠️ Plan of Action  
1. **Rivers** → Drill wells (short + long-term solution).  
2. **Wells** → Install filters (RO for chemical, UV+RO for biological contaminants).  
3. **Shared taps** → Add taps where queues > 30 min, and send tankers temporarily.  
4. **Broken infrastructure** → Prioritize repairs in towns like **Amina, Lusaka, Zuri, Djenne**, and rural **Amanzi**.  
5. **Tracking progress** → Built a `Project_progress` SQL table for engineers to log repairs, status updates, and completion dates.  

---

## 🗄️ Technologies Used  
- **MySQL** → For queries, joins, CTEs, and database design.  
- **SQL Views & Temporary Tables** → For performance and modular analysis.  
- **Jupyter Notebook** → Documenting SQL queries and results.  
- **Power BI (planned)** → A dashboard will be developed in the **next phase** of this project (to be stored in a `bi_dashboard/` folder).  

---


## 📊 Example Outputs  
- Provincial breakdowns of water access (% households using wells, taps, rivers).  
- Town-level disparities (e.g., Harare in Akatsi vs Harare in Kilimani).  
- Queue time analysis by **day of week & time of day**.  
- `Project_progress` table to track and manage water source improvements.  

---

## 🚀 How to Use  
1. Clone the repository.  
2. Set up a **MySQL database** and load the provided schema/data.  
3. Open the Jupyter Notebook in the `notebook/` folder.  
4. Run the SQL queries step by step to replicate the analysis.  
5. (Coming soon) Open the **Power BI dashboard** in the `bi_dashboard/` folder once developed.  

---

## 📌 Final Note  
This phase highlights how **data science and database engineering** can be combined to not only **diagnose a crisis**, but also **design actionable interventions**.  

A **Power BI dashboard** will be developed in the next phase of the project to strengthen storytelling and decision-making.  
 
