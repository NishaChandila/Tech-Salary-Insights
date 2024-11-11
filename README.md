# Data Engineer Salary Analysis

> "Data engineering is the foundation of data science. If you don't have the right data pipeline, you won't have the right insights."

## **Introduction**
As a data analyst, I’ve undertaken a comprehensive analysis of data engineer job roles, focusing on key factors such as salary, employment type, remote work ratios, and experience levels. To gain deeper insights, I started with an exploratory data analysis (EDA) using Python, which allowed me to clean, explore, and visualize the data from various angles. Through this process, I was able to identify patterns and trends related to compensation, work structure, and geographical differences within the data.

Following the initial analysis, I created an interactive Power BI dashboard to provide a more visual and user-friendly representation of the findings. This dashboard is designed to help stakeholders easily understand the relationships between experience levels, job titles, salaries, remote work arrangements, and company sizes, making it easier for decision-makers to draw actionable insights and make informed choices. The goal of this project is to present the data in an accessible format, ensuring that both technical and non-technical stakeholders can grasp key insights at a glance.

By visualizing this data, I aimed to bring clarity to trends and compensation structures in the data engineering job market, helping stakeholders make strategic decisions related to hiring, compensation policies, and remote work structures.

- [**Power BI Dashboard Link**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/Data-Eng-Dashboard.pdf)
- [**Python EDA PDF**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/data-engineer-salary-eda.ipynb)
- [**Dataset Link**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/Dataset%20salary%202024.csv)

## **Data Structure**
This dataset contains job-related information for roles in the field of data engineering, with a focus on salary, employment type, remote work ratio, and company characteristics. With over 15,000 rows of data, the dataset provides insights into compensation trends, work preferences, and company-related factors that influence data engineering roles. It can be used to analyze trends in salary based on experience, job title, location, and remote work arrangements.

![Dataset Preview](https://github.com/NishaChandila/project-assets/blob/main/data-eng-dataset.PNG)

### **Data Columns**
- **company_location**: The country where the company is based.
- **company_size**: The size of the company (Small, Medium, Large).
- **employee_residence**: The country where the employee resides.
- **employment_type**: The type of employment (Full-time, Part-time, Contract, Freelance).
- **experience_level**: The experience level of the employee (Entry, Mid, Senior, Lead).
- **job_title**: The specific job role or title of the employee (e.g., Data Engineer, Data Scientist).
- **remote_ratio**: The percentage of remote work (0% = On-site, 50% = Hybrid, 100% = Fully Remote).
- **salary**: The salary of the employee in local currency.
- **salary_currency**: The currency in which the salary is paid (e.g., USD, EUR).
- **salary_in_usd**: The employee's salary converted into USD.
- **work_year**: The year the data was recorded.

- [**Dataset Link**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/Dataset%20salary%202024.csv)

## **Executive Summary**
![Home](https://github.com/NishaChandila/project-assets/blob/main/data-eng1.PNG)

This Power BI dashboard offers key insights into data engineering compensation trends. Senior roles earn higher salaries, with data engineers in larger companies earning more on average. Medium-sized companies pay around $151K, while small companies pay less. Remote and hybrid roles, especially in larger companies, tend to have higher salaries. Full-time positions dominate, with part-time and contract roles earning less. These insights help organizations understand salary trends based on experience, company size, and remote work preferences, aiding in competitive talent acquisition strategies.

### **Page 1: Compensation Insights**
![Compensation insights](https://github.com/NishaChandila/project-assets/blob/main/data-eng2.PNG)

- **Compensation by Experience Level**: Senior-level data engineers earn the highest salaries, with an average of $164K. Entry-level roles earn significantly less, with an average salary of $195K for mid-level and $164K for senior roles, reflecting career progression.
- **Salary by Job Title and Company Size**: Data Engineers and Data Scientists have the highest average salaries, at $192K and $189K, respectively. Larger companies (M and L size) offer higher salaries, with medium companies paying $151K on average, while small companies pay less at $87K.
- **Geographical Insights**: Employees in regions with higher remote work ratios (e.g., larger companies) tend to earn higher salaries. Remote positions in medium and large companies see higher average salaries, particularly in locations offering more flexibility.

### **Page 2: Remote Work & Employment Trends**
![Remote Work](https://github.com/NishaChandila/project-assets/blob/main/data-eng3.PNG)

- **Remote Work & Salary**: Employees with a higher remote ratio (especially in hybrid or fully remote positions) generally earn higher salaries, particularly in medium and large-sized companies, where salaries can reach up to $481K.
- **Employment Type Distribution**: Full-time roles dominate with the highest salaries. Part-time and contract roles are less common but typically come with lower pay.
- **Company Size and Employment Distribution**: Larger companies (M and L) offer better salaries and more remote work options compared to smaller companies. These insights help evaluate competitive compensation and work flexibility strategies across company sizes.

- [**Power BI Dashboard Link**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/Data-Eng-Dashboard.pdf)

## **EDA and Data Cleaning**
In the exploratory data analysis (EDA) phase, I performed essential data cleaning to ensure the dataset was well-prepared for further analysis. I analyzed the average salary by job title, company location, and company size to identify salary trends and patterns across different roles and regions. Additionally, I examined salary trends over the years to observe any shifts or growth in compensation over time. Using Python, I generated key insights on these variables and translated them into a Power BI dashboard. This dashboard was designed with non-technical stakeholders in mind, providing clear, visual insights that help them easily understand the data and make informed decisions based on salary trends, company size, and location-specific compensation data.

- [**Python EDA PDF**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/data-engineer-salary-eda.ipynb)

## **Recommendations**
1. **Competitive Compensation**: Revise salary strategies, especially for medium and small-sized companies, to stay competitive with larger firms, particularly in data engineering roles.
2. **Focus on Senior Roles**: Enhance salary offerings and career growth opportunities for senior data engineers to retain experienced talent.
3. **Promote Remote Work**: Expand remote and hybrid work options, as they are linked to higher salaries and can attract top talent.
4. **Adjust Salaries by Location**: Consider geographic salary adjustments, especially for regions with higher demand and competitive pay for data engineers.
5. **Highlight Full-Time Employment**: Promote the advantages of full-time roles, as they tend to offer higher salaries compared to part-time or contract positions.
6. **Leverage Company Size for Remote Work**: Medium and large companies should offer more remote work opportunities, aligning with higher pay and competitive advantages.

## **Conclusion**
The analysis provides valuable insights into the compensation landscape for data engineers, highlighting the importance of competitive salary packages, senior role retention, and flexibility in work arrangements. By aligning company policies with these insights, organizations can attract and retain top talent, ensuring long-term success in a competitive job market.

- [**Power BI Dashboard Link**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/Data-Eng-Dashboard.pdf)
- [**Python EDA PDF**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/data-engineer-salary-eda.ipynb)
- [**Dataset Link**](https://github.com/NishaChandila/Data-Engineer-Salay-EDA-/blob/main/Dataset%20salary%202024.csv)
