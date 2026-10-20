# Healthcare Data Analysis and Insights

## 📌 Project Overview
This project focuses on analyzing a comprehensive healthcare dataset comprising patient hospitalization details, medical examination metrics, and customer profiles. The objective is to identify key health trends, analyze healthcare expenditure patterns, and build an interactive reporting dashboard to support data-driven decision-making.

## 🛠️ Tools & Technologies Used
- **Tool:** Microsoft Excel
- **Data Cleaning & Handling:** Blank/Missing value imputation (Mean, Mode), Text-to-Columns, Formula-based replacements
- **Formulas & Functions:** `VLOOKUP`, `DATEDIF`, `INDEX/MATCH`, `MODE`, `COUNTIF`, `AVERAGE`
- **Analytics:** Summary statistics, Multi-table consolidation, Categorical groupings (BMI status, Diabetes status)
- **Visualization & Reporting:** Interactive Excel Dashboard, Pivot Tables, Pivot Charts (Donut Charts, Clustered Bar Charts, Scatter/Line Plots), Slicers

## 🔍 Key Objectives & Workflow
1. **Data Cleaning:** Imputed missing values using appropriate statistical measures (Mean for Year, Mode for Categorical variables like Hospital Tier, City Tier).
2. **Data Transformation:**
   - Split customer names into Title, First Name, and Last Name.
   - Categorized health indicators into standardized categories (Weight Status based on BMI, Diabetes Status based on HbA1c).
   - Created standardized Date of Birth and computed patient age dynamically as of June 8, 2023 using `DATEDIF`.
3. **Data Integration:** Consolidated disparate datasets (Hospitalisation Details, Medical Examinations, Customer Names) into a unified `Healthcare` table utilizing `VLOOKUP`.
4. **Data Visualization & Dashboard:**
   - Evaluated the distribution of cancer history across smokers vs. non-smokers.
   - Assessed surgical interventions and HbA1c levels against transplant histories.
   - Compared hospital charges across different hospital tiers and states.
   - Incorporated dynamic slicers (`Weight Status` and `Diabetes Status`) for interactive analysis.
