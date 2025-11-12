# 🎓 Student Performance Dashboard (Power BI)

## **Overview**
This Power BI dashboard provides an interactive and data-driven analysis of student performance across six subjects (**BCC1–BCC6**).  
The dataset consists of 100 students, each evaluated out of 100 marks per subject.  
The goal of this project is to identify key academic insights such as overall class performance, top and bottom performers, subject-wise averages, and performance trends.  

The dashboard helps educators, analysts, and administrators quickly evaluate class outcomes, identify struggling students, and make data-driven academic decisions.

---

## **Features**

### **KPIs & Metrics**
- **Total Students**
- **Average Marks** (Subject-wise: BCC1–BCC6)
- **Overall Average Percentage**
- **Pass Percentage**
- **Number of Students Below 40%**
- **Top and Bottom 5 Students**

### **Visual Insights**
- **Top 5 and Bottom 5 Students** by Percentage  
- **Roll Number-wise Trend Analysis** (Percentage vs. Roll No)  
- **Subject-Wise Average Comparison**  
- **Interactive Filters** for exploring specific students or subjects  

### **Calculated Columns & Measures (DAX)**
- **Total Marks**  
- **Percentage**  
- **Pass/Fail Flag**  
- **Dynamic KPIs using DAX**

---

## **Tech Stack**

**Tools & Technologies Used:**
- **Power BI** – Dashboard creation and interactive data visualization  
- **DAX (Data Analysis Expressions)** – For KPI calculations and data modeling  
- **MS Excel** – For data cleaning and preprocessing  
- **Data Modeling** – Relationships, measures, and calculated columns  
- **Python (Pandas)** *(optional)* – For dataset generation and preprocessing  

---

## **Insights Derived**
- The **average class performance** stands at **66.88%** across all subjects.  
- **Top performer:** Aarav Reddy with **88% overall**.  
- Subjects **BCC3** and **BCC5** show lower averages, indicating potential areas for academic improvement.  
- The **bottom 5 students** fall below **53%**, requiring targeted intervention.  
- A **performance variation trend** exists across roll numbers, showing diversity in academic consistency.  

---

## **Future Enhancements**
- Add **gender and department-wise performance analytics**.  
- Integrate **attendance and participation data** for correlation analysis.  
- Build a **machine learning model in Python** to predict student success probability based on historical scores.  

---

## **Dataset**
The dataset contains **100 records** with the following fields:
- Serial No  
- Roll No  
- Name  
- BCC1, BCC2, BCC3, BCC4, BCC5, BCC6 (Marks out of 100)  
- Calculated Percentage  

---

## **Dashboard Preview**
![Dashboard Preview](https://github.com/shivam-kumar3/Student-Performance-Dashboard/blob/main/Dashboard%20Preview.jpeg?raw=true)
