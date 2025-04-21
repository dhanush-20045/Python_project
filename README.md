# Data Analyst Job Market Exploration – India

This project explores the Data Analyst job landscape in the US, focusing on the most in-demand skills, top companies hiring, salary trends, and optimal skill combinations. The project leverages job posting data to extract meaningful insights that can guide aspiring analysts or professionals planning their next career move.

### Key Insights

1) Top Hiring Companies: Includes SAZ India, S&P Global, PepsiCo, JPMorgan Chase & Co.

2) Most In-Demand Skills: SQL, Excel, Python, Tableau, and Power BI lead the demand.

3) Skill Trends: Python and cloud technologies are showing increasing relevance.

4) Salary Insights: Roles with Python and BI tools tend to offer higher salaries.

5) Optimal Combinations: Python + SQL + BI tool (e.g., Power BI/Tableau) = better opportunities.

### 🔍 1. Exploratory Data Analysis 

 **Goal:**  
 
  Understand the data science job landscape across roles, countries, and benefits.

 **Tools Used:**  
 
  Python (Pandas, Seaborn, Matplotlib), HuggingFace Datasets

 **Main Tasks:** 
 
  ● Cleaned and parsed job posting data 
  
  ● Visualized top job roles, countries, and companies
  
  ● Analyzed key job perks like remote work, degree requirements, and insurance  
  
  ● Zoomed in on **Data Analyst** roles in India  
  
    ● Identified top cities and hiring companies  
    
    ● Explored job benefits specific to this role

 **Findings:**  
 
  ● Top roles: **Data Engineer**, **Data Scientist**, **Data Analyst**  
  
  ● **India** and **USA** dominate job postings  
  
  ● Many jobs offer **remote work** and have **flexible degree requirements**  
  
  ● **Bangalore**, **Mumbai**, **Hyderabad** are hot spots for Data Analyst jobs

  ### 📊 2. Skill Demand Analysis 

 **Goal:**  
 
  Identify the most in-demand skills across top data roles in India.

 **Tools Used:**  
 
  Python (Pandas, Seaborn, Matplotlib), HuggingFace Datasets

 **Main Tasks:**  
 
  ● Filtered job postings to focus on India
  
  ● Extracted and exploded skill lists from job descriptions  
  
  ● Counted and ranked skills for each role  
  
  ● Converted counts into percentages for better comparison 
  
  ● Visualized top 5 skills for each of the top 3 roles

 **Top 3 Roles Analyzed:**  
 
  ● Data Analyst  
  
  ● Data Engineer  
  
  ● Data Scientist

 **Findings:** 
 
  ● **SQL** and **Python** dominate across all roles  
  
  ● **Data Engineers** often require **Spark** and **AWS**
  
  ● **Data Scientists** lean heavily on **Machine Learning** and **Python**  
  
  ● Skill demand varies, but Python and SQL are consistently foundational

  ### 📈 3. Skill Trends

 **Goal:**  
 
  Track how demand for key skills in Data Analyst roles changes over time in the India.

 **Tools Used:**  
 
  Python (Pandas, Seaborn, Matplotlib), HuggingFace Datasets

 **Methodology:**  
 
  ● Aggregated monthly job postings for Data Analyst roles 
  
  ● Exploded skills list for row-wise skill-level granularity
  
  ● Created pivot tables of monthly skill counts 
  
  ● Normalized counts as percentages of total monthly postings 
  
  ● Plotted monthly skill trends for top 5 skills  

 **Top Skills Analyzed (Based on % Share Over Time):**  
 
  ● SQL  
  
  ● Excel  
  
  ● Tableau 
  
  ● Python  
  
  ● Power BI  

 **Key Insights:**  
 
  ● **SQL** consistently dominates with over 50–60% presence in job posts
  
  ● **Excel** and **Tableau** show steady demand across the year  
  
  ● **Python** shows slight upward momentum in later months  
  
  ● **Power BI** maintains moderate but consistent demand  
  
  ● Trendlines suggest SQL and Python are foundational, while BI tools vary

### 💼 4. Salary Analysis for Data Analyst Roles

**Goal:**  

  Analyze the salary trends for Data Analyst roles across different job titles and skills, focusing on the United States.

**Tools Used:**  

  Python (Pandas, Seaborn, Matplotlib), HuggingFace Datasets

**Methodology:**

 ● Filtered the dataset to include only **Data Analyst** positions in the **India**.
 
 ● Aggregated salaries by **job title** and **skills** to evaluate median and distribution trends.
 
 ● Visualized the salary distributions for the top 6 data job titles using box plots.
 
 ● Identified the **highest-paying skills** and the **most in-demand skills** based on median salaries and skill frequency.

**Key Steps in the Analysis:**  

  **Job Title Salary Distribution:**  
  
   ● Filtered job titles to focus on the top 6 data jobs.
   
   ● Analyzed the **median salary** for each job title and visualized using a **box plot**.
   
  **Skill-Based Salary Distribution:**  
  
   ● Focused on **Data Analyst** roles.
   
   ● Used the **explode** function to break down the **job_skills** column into individual rows for skill-level analysis.
   
   ● Calculated the **median salary** for each skill and sorted them by highest pay.

  **Salary vs Skill:** 
  
   ● Identified the **top 10 highest-paying skills** (e.g., **dplyr**, **bitbucket**, **solidity**) by calculating the 
     median salary for each.
     
   ● Identified the **top 10 most in-demand skills** (e.g., **python**, **tableau**,






