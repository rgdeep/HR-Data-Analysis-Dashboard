# HR-Data-Analysis-Dashboard
HR analytics dashboard visualizing attrition, job satisfaction, and demographics.

Some Questions based on the HR Analytics Dashboard:
1. What is the total number of employees in the organization?
2. How many employees have left the organization (attrition count)?
3. What is the attrition rate of the organization?
4. How many active employees are currently in the organization?
5. What is the average age of employees?
6. Which department has the highest attrition rate?
7. How does attrition vary by department (R&D, Sales, HR)?
8. What is the distribution of employees by age group?
9. What is the gender-wise distribution of employees within different age groups?
10. How does job satisfaction vary across different job roles?
11. Which job role has the highest job satisfaction rating?
12. Which job role has the lowest job satisfaction rating?
13. How does education field impact attrition rates?
14. Which education field has the highest attrition count?
15. Which education field has the lowest attrition count?
16. What is the attrition rate for different age groups?
17. Which age group has the highest attrition rate?
18. How does gender influence attrition rates across age groups?
19. What percentage of employees in each age group have left the company?
20. How does the attrition rate compare between male and female employees?

### **Charts Used in the HR Analytics Dashboard:**
1. **KPI Cards** – Displays Overall Employee Count, Attrition, Attrition Rate, Active Employees, and Average Age.
2. **Pie Chart** – Department-Wise Attrition.
3. **Stacked Bar Chart** – Number of Employees by Age Group (segregated by gender).
4. **Table Chart** – Job Satisfaction Rating by Job Role.
5. **Bar Chart** – Education Field-Wise Attrition.
6. **Doughnut Charts** – Attrition Rate by Gender for Different Age Groups.

---

### **Steps to Prepare a Chart in Power BI:**
#### **1. Data Preparation**
   - **Collect Data**: Gather HR data from sources such as Excel, SQL databases, or APIs.
   - **Clean Data**: Remove duplicates, handle missing values, and ensure consistency.
   - **Transform Data**: Use Power Query to format data appropriately.

#### **2. Data Modeling**
   - **Create Relationships**: Connect different tables using primary and foreign keys.
   - **Add Calculated Columns**: Use DAX to create new columns if needed.
   - **Define Measures**: Use DAX functions for calculations like Attrition Rate.

#### **3. Visualization**
   - **Choose Appropriate Chart Types**: Based on the type of data (e.g., pie charts for proportions, bar charts for comparisons).
   - **Drag and Drop Fields**: Assign appropriate fields to the X-axis, Y-axis, values, and legends.
   - **Apply Filters & Slicers**: Allow interactive filtering.

#### **4. Formatting & Customization**
   - **Adjust Colors & Labels**: Improve readability.
   - **Set Data Labels**: Display values clearly.
   - **Add Titles & Tooltips**: Provide context for better understanding.

#### **5. Publishing & Sharing**
   - **Publish to Power BI Service**: Share with stakeholders.
   - **Schedule Data Refresh**: Keep reports updated automatically.

### **Final Outcomes from the HR Analytics Dashboard**  

This **HR Analytics Dashboard** provides key insights into employee attrition, job satisfaction, and workforce demographics. Below are the final takeaways:  

### **1. Workforce Overview**
- **Total Employees**: 1,470  
- **Active Employees**: 1,233  
- **Attrition Count**: 237 employees have left.  
- **Attrition Rate**: 16.12%  
- **Average Age of Employees**: 37 years  

### **2. Department-Wise Attrition**
- **R&D Department**: Highest attrition (133 employees, 56.12%).  
- **Sales Department**: 92 employees (38.82%) left.  
- **HR Department**: Lowest attrition (12 employees, 5.06%).  

### **3. Employee Age Group Distribution**
- Majority of employees are aged **25-34 (646 employees)** and **35-44 (505 employees)**.  
- **Attrition is highest among younger employees** (Under 35).  

### **4. Job Satisfaction Analysis**
- The **Sales Executive role has the highest attrition (326 employees)** despite a mixed satisfaction rating.  
- **Research Scientist role** has a high workforce (292 employees) but moderate satisfaction levels.  
- **Healthcare Representatives & HR roles have the lowest workforce but better satisfaction scores.**  

### **5. Education Field & Attrition**
- Employees from **Life Sciences & Medical backgrounds have the highest attrition (89 & 63 respectively).**  
- **HR & Technical Degrees have the least attrition**, indicating better retention in these fields.  

### **6. Gender-Wise Attrition Across Age Groups**
- **Attrition is higher among younger employees (Under 35 years).**  
- **25-34 age group** has the highest attrition (112 employees, 61.61% are male).  
- **Older employees (Above 45) have a lower attrition rate.**  

### **Key Business Insights & Recommendations**
✅ **Focus on Employee Retention in R&D & Sales Departments.**  
✅ **Improve Job Satisfaction for Sales Executives to reduce attrition.**  
✅ **Younger Employees (Under 35) Need Better Engagement Programs.**  
✅ **Targeted Retention Strategies Needed for Life Sciences & Medical Professionals.**  
✅ **Monitor Gender-Based Attrition Trends & Implement Retention Initiatives.**  
