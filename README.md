# IBM Employee Attrition Analysis

## 📌 Introduction

Employee attrition is an important issue for every organisation. When employees leave, companies may face higher recruitment costs, loss of experienced employees, and additional workload for existing staff.

In this project, I worked with the **IBM Employee Attrition dataset** to understand the factors that may be connected with employees leaving the organisation.

I used Python to clean and explore the data and created different charts and tables to make the results easier to understand.

## 🎯 Project Goals

The main purpose of this project was to find answers to questions like:

- Which department has more employee attrition?
- Which job roles have higher attrition?
- Is there any difference in attrition based on gender?
- Does overtime have a relationship with employee attrition?
- Which employee groups might need more attention from HR?

## 🧹 Data Cleaning

Before starting the analysis, I performed some basic checks on the dataset.

I:
- Loaded the dataset into Python.
- Checked the rows and columns.
- Checked the data types.
- Looked for missing values.
- Checked categorical columns and their unique values.
- Handled unnecessary columns where required.
- Renamed columns wherever needed.

## 🔍 Exploring the Data

After cleaning the data, I explored different employee characteristics.

I checked the distribution of:

- **Gender**
- **Age**
- **Department**

I used **Value Counts, Barplots and Countplots** to understand the employee distribution.

I also used `describe()` to get a statistical summary of the numerical columns.

To understand relationships between numerical variables, I performed **correlation analysis** and created a **Pair Plot**.

## 📊 Attrition Analysis

The main focus of this project was understanding employee attrition.

I grouped the data and calculated average attrition for:

- Department
- Job Role
- Gender
- Overtime

I used **Barplots and Subplots** to compare the results visually.

This made it easier to identify groups with relatively higher or lower attrition.

## 📋 Pivot Table Analysis

To explore the data in more detail, I created pivot tables for:

- **Department vs Job Role vs Attrition**
- **Overtime vs Job Role vs Attrition**
- **Gender vs Job Role vs Attrition**

These tables helped me analyse multiple factors together.

## 📈 Dashboard

Finally, I brought the important analysis together into a simple dashboard.

The dashboard includes:

- Department
- Job Role
- Overtime
- Job Role vs Attrition
- Department vs Attrition
- Gender vs Attrition
- Overtime vs Attrition

The aim was to make the analysis easy to understand at a glance instead of relying only on raw numbers.

## 💡 Key Takeaway

Working on this project helped me understand how **data analysis can be used to study real business problems**.

Instead of only looking at numbers, I learned how to clean data, find patterns, compare employee groups, and present insights using visualisations.

This project also gave me practical experience with **Pandas, GroupBy, Pivot Tables, Matplotlib, Seaborn and Exploratory Data Analysis**.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure

IBM-Employee-Attrition-Analysis/
│
├── IBM_Employee_Attrition_Analysis.ipynb
├── IBM_Employee_Attrition.csv
├── IBM_Employee_Attrition_Report.pdf
├── README.md
└── images/
    └── Charts & Dashboard

## 👨‍💻 Skills Practiced

**Python • Data Cleaning • Exploratory Data Analysis • Pandas • GroupBy • Pivot Tables • Data Visualisation • Matplotlib • Seaborn • Business Insights**
