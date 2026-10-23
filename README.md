# Credit Risk Analytics
Graduation project for the Professional Data Analysis Track, built on the Home Credit Default Risk dataset.

## Project Idea :
- Banks lose money when customers fail to repay their loans. This project analyzes real consumer-credit data from *Home Credit* to understand *what drives loan default* and to build a model that *predicts the probability of default* for each applicant.

## Team Members :
1. MAYA Mohammed Alsaadany
2. Feby Hossam Mouris Hana
3. Abdallah Mohamed Abdelaziz Elgendy
4. Nejar Ahmed Mohamed ElSheikha
5. Zeinab Alaa Ali Ebrahim
6. Alaa Ahmed Fahim Mohamed

## Project Work Plan :

**Tools:** SQL, Power BI

---

### Week 1: Build Data Model, Data Cleaning and Preprocessing

**Tasks**
- Data Preprocessing: explore the dataset, build a data model, then clean and preprocess the data.
  - Inspect structure, data types, and row counts.
  - Identify and handle missing values, duplicates, and outliers.
  - Standardize formats and fix inconsistent or invalid values.
  - Remove irrelevant columns and create new derived columns.
  - Organize the data into related tables with clear keys.
  - Document every column in a data dictionary.
- **Tools:** SQL

**Deliverables**
- Cleaned dataset ready for analysis.
- Documented SQL scripts for the data model and preprocessing steps.

---

### Week 2: Analysis Questions Phase

**Tasks**
- Determine Data Analysis Questions: define all possible analysis questions that can be answered from the dataset and would interest the organization's decision makers.
  - Answer each question using SQL queries (aggregations, grouping, comparisons).
  - Summarize the key insight behind each result.
- **Tools:** SQL

**Deliverables**
- Set of analysis questions that can be answered via the dataset.
- Query results and written insights for each question.

---

### Week 3: Forecasting Questions Phase

**Tasks**
- Determine a set of forecasting or prediction questions and answer them using the trends and patterns found in the dataset.
  - Build a rule-based scoring or trend-based estimation in SQL from the strongest factors found in Week 2.
  - Group results into categories (e.g., Low / Medium / High) and validate them against actual outcomes.
  - Prepare visuals that answer each forecasting question.
- **Tools:** SQL, Power BI

**Deliverables**
- Scoring or estimation tables with validation results.
- Visualizations answering the forecasting questions.

---

### Week 4: Visualization Dashboard and Final Presentation

**Tasks**
- Build a Visualization Dashboard: build a Power BI dashboard that visualizes the answers to all analysis and forecasting questions.
  - Connect Power BI to the data and set up relationships.
  - Create measures (KPIs) and interactive filters.
  - Design clear, consistent pages (overview, detailed analysis, forecasting).
- Final Presentation: prepare a report and presentation summarizing the project work, including data preparation, analysis, forecasting, and recommendations.
- **Tools:** SQL, Power BI

**Deliverables**


- Visualization dashboard.
- Final report and presentation.

## Roles & Responsibilities :

1. **MAYA Mohammed Alsaadany**: Power BI, Dashboard 1.
2. **Feby Hossam Mouris Hana**: Power BI, Dashboard 2.
3. **Abdallah Mohamed Abdelaziz Elgendy**: Power BI, Dashboard 3.
4. **Nejar Ahmed Mohamed ElSheikha**: SQL, data cleaning (missing values, duplicates, outliers).
5. **Zeinab Alaa Ali Ebrahim**: SQL, data modeling (related tables and data dictionary).
6. **Alaa Ahmed Fahim Mohamed**: SQL, data preprocessing (drop irrelevant columns, standardize names and types).

## KPIs :

1. **Default Rate**: share of customers who failed to repay (about 8%). The main KPI of the dashboard.
2. **Average Credit-to-Income Ratio**: loan amount divided by total income, compared between defaulters and non-defaulters.
3. **Average Loan Size**: average loan amount per customer.
4. **Average Customer Income**: average income, broken down by segment.
5. **Model ROC-AUC**: how well the model separates defaulters from non-defaulters, reported with Precision and Recall for the default class.

## Instructor Name :
- **Mahmoud Emad**

## Project Files :

1. **Dataset**: [application_train.csv (Google Drive)](https://drive.google.com/file/d/1_aDmilNPefGGBukW29Dtm1mk_bHVnDqJ/view?usp=sharing)
2. **Original source**: [Kaggle, Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/data?select=application_train.csv)
