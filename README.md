# Data Tagging and Data Analysis Assignment

This repository contains the completed assignments for two tasks related to data tagging and data analysis, performed using Excel and Python. Below is a detailed explanation of each task using the **STAR Method** (Situation, Task, Action, Result).

---

## ✅ Task 1: Data Tagging

### **S – Situation**
The dataset consisted of free-text service logs in three columns: Complaint, Cause, and Correction. Along with it, a taxonomy sheet provided a fixed set of categories across five tagging fields: Root Cause, Symptom_Condition, Symptom_Component, Fix_Condition, and Fix_Component.

### **T – Task**
The goal was to tag each row by correctly assigning the appropriate category to each of the five fields using logical mapping from the taxonomy, ensuring consistency and clarity for downstream analysis.

### **A – Action**
- Carefully reviewed each entry to understand the context in the free-text columns.
- Used exact term matching and contextual interpretation to assign the correct tags from the taxonomy sheet.
- Applied data validation dropdowns in Excel to ensure consistency and avoid manual typing errors.
- Where ambiguity existed, judgment was used to assign the most relevant tag by comparing similar records.

### **R – Result**
- Successfully created a clean, tagged dataset.
- Generated a **summary report** that highlighted:
  - Repetitive failure patterns in connectors and seals.
  - High incidence of installation errors.
  - Most fixes were simple actions (tightening, replacing).
  - Overlap between problem and fix components suggests isolated rather than systemic issues.
- The tagging system is now usable for further analytics and can aid in reducing quality issues in field service operations.

---

## ✅ Task 2: Data Analysis & Insights Generation (Python)

### **S – Situation**
A large dataset containing 52 columns of vehicle service data, including numeric, categorical, and free-text fields. The aim was to analyze, clean, and generate meaningful insights and features for business decision-making.

### **T – Task**
- Perform column-wise data profiling.
- Clean and preprocess the data (nulls, inconsistencies, outliers).
- Identify 5 critical columns for stakeholders and generate visual insights.
- Extract tags from free-text fields to highlight patterns.
- Provide actionable insights and recommendations.

### **A – Action**
- Cleaned missing and inconsistent values using imputation, deletion, and formatting fixes.
- Treated outliers using IQR and Z-score techniques.
- Identified 5 critical columns: `VIN`, `REPAIR_AGE`, `KM`, `CUSTOMER_VERBATIM`, `CAUSAL_PART_NM`.
- Generated visualizations:
  - Histogram (Repair Age)
  - Boxplot (Repair Cost vs. Platform)
  - Bar Chart (Top Causal Parts)
  - Heatmap (Correlation Matrix)
  - Word Cloud (Customer Verbatim)
- Used keyword extraction on free-text fields to generate tags like: *Engine Issue*, *Transmission Fault*, *Noise Complaint*, *Electrical Failure*, *Repeat Visit*.

### **R – Result**
- Produced a clean dataset with insightful tags for further analysis.
- Delivered a 2-page analytical report with charts and actionable insights:
  - High repair rates within 3 years suggest warranty policy review.
  - Common issues and fix patterns could improve technician training.
  - Tag insights from customer comments can support product development and CX improvements.
  - Business can adopt predictive maintenance models using high-impact features like `KM` and `REPAIR_AGE`.

---

### 📁 Deliverables

- Task 1:
  - Tagged Excel file
  - Summary report (PDF)

- Task 2:
  - Cleaned CSV
  - Jupyter Notebook (Python Analysis)
  - 2-page Analytical Report (PDF)

---

### 📌 Tools Used

- **Excel (Data Tagging, Dropdowns, Preprocessing)**
- **Python (Pandas, NumPy, Matplotlib, Seaborn, NLP Techniques)**
- **Jupyter Notebook (For Task 2 Analysis and Visualization)**

---

### 🙌 Author
**Abhishek Mahadev Raut**  
Aspiring Data Analyst | Skilled in SQL, Python, Excel, Power BI  
📧 [abhishekraut1224@gmail.com](mailto:abhishekraut1224@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/abhishek-raut-215191249/)

