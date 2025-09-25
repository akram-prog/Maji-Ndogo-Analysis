# 💧 WEAVING THE DATA THREADS OF MAJI NDOGO'S NARRATIVE
**Integrated Project Part III – Unveiling the Water Crisis in Maji Ndogo**

---

## 📌 Project Overview
This project investigates the **water crisis in Maji Ndogo**, a fictional town, through a **data-driven approach**. Using **SQL in MySQL** and a **Jupyter Notebook environment**, the analysis compares a surveyor’s dataset with a recent audit report to uncover discrepancies, identify patterns, and determine accountability.

The ultimate goal is to **improve data integrity, resource allocation, and decision-making** around water accessibility in the region.

---

## ❓ Key Questions Answered
- Is there a difference between the quality scores reported by surveyors and auditors?
- If so, what patterns emerge in these discrepancies?
- Which employees are responsible for the incorrect data entries?
- What are the potential root causes of these data-related issues?

---

## 🛠️ Technologies Used
- **SQL (MySQL):** Querying, manipulation, and analysis  
- **Jupyter Notebook:** Documentation and execution of queries  
- **md_water_services database:** Core dataset for analysis

---

## 🔍 Analysis Workflow
1. Load and explore the **surveyor dataset** and **audit report**  
2. Compare quality scores across both sources  
3. Identify mismatched records and measure the extent of discrepancies  
4. Investigate employee activity linked to incorrect records  
5. Document findings and highlight responsible individuals

---

## 📊 Key Findings
- **193 records** had discrepancies between surveyor and auditor quality scores  
- The **type of water source** was consistently reported correctly → not the cause of errors  
- Four employees were flagged as outliers with excessive errors:
  - **Zuriel Matembo**
  - **Malachi Mavuso**
  - **Bello Azibo**
  - **Lalitha Kaburi**
- Evidence suggests **human error or misconduct** as the root cause

## 📒 Notebook
The full SQL analysis is documented in this Jupyter Notebook:  
👉 [maji_ndogo.ipynb](maji_ndogo.ipynb)
