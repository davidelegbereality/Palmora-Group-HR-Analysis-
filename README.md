 Palmoria Group HR Analytics Case Study

> Data-driven investigation into gender equality, compensation structure, and regulatory compliance in a Nigerian manufacturing firm.

 Project Overview

Palmoria Group, a manufacturing company based in Nigeria, faced public scrutiny due to allegations of gender inequality across its 3 regional offices. The internal HR team, led by the CHRO, engaged me to perform a *comprehensive HR data analysis* to evaluate key organizational metrics — especially around **gender diversity, pay equity, performance ratings, and salary regulation compliance*.

This project was executed using *Microsoft Power BI*, leveraging multi-source data integration, advanced DAX calculations, and interactive visualizations to uncover insights and support decision-making.

 Business Objectives

- Analyze *gender distribution* across departments and regions.
- Investigate potential *gender pay gaps*.
- Evaluate *performance ratings* by gender.
- Check compliance with the new *minimum salary regulation* of $90,000/year.
- Calculate and allocate *performance-based bonuses*.
- Visualize total *compensation distributions* by region.

 Data Sources

- *Employee Master Data* (`emp-data.csv`):  
  Contains employee demographics, departments, regions, salaries, and ratings.

- *Bonus Rules Table* (`BonusRules.xlsx`):  
  Contains the percentage bonus allocation per rating tier.

 Tools & Techniques

| Tool         | Purpose                                      |
|--------------|----------------------------------------------|
| Power BI     | Interactive data visualization & dashboard   |
| Power Query  | Data cleaning and transformation             |
| DAX          | Calculated fields (Bonus, Total Pay, etc.)   |
| Excel        | Preliminary rule checking and formatting     |

 Key Visual Insights

 1. **Gender Distribution**
- Clear gender imbalance observed in several regions and departments.
- "Undisclosed" gender was normalized as a generic category to ensure inclusivity.

 2. *Gender Pay Gap Analysis*
- Departments such as *Sales* and *Product Management* showed notable differences in average salary by gender.
- Overall, *males had higher average salaries*, with "Undisclosed" sometimes skewing the data due to outlier values.

 3. *Performance Rating Breakdown*
- Female employees were slightly underrepresented in the "Good" rating category.
- Rating distribution was visualized across gender for transparency.

 4. *Salary Band Monitoring*
- Regulatory compliance (min. salary: $90,000) was checked using binning:
  - Less than 15% of employees fall into the compliant salary band ($91k+).
  - Salary band distribution was visualized *per region* to highlight disparities.

 5. *Bonus and Total Compensation*
- Bonus amounts were calculated based on rating and joined using `RELATED()` in DAX.
- A total of *$2.08M* in bonuses was allocated.
- Final total compensation value across the company: *$71.92M*.
- Region-wise breakdown provided for both salary and bonus spend.

 Dashboard Features

- Slicers by department and gender
- KPI tiles for total salary and bonus
- Salary band histogram
- Dynamic tables for salary averages by gender, department, and region
- Bonus allocation and total compensation per employee and region


 Business Impact

 Provided Palmoria’s management team with *clear evidence of gender imbalance* and compensation inequality.

 Helped identify *non-compliant salary clusters*, allowing for proactive regulatory adjustments.

 Delivered a *clean, interactive dashboard* to aid HR in real-time decision making.

 ![Dashboard Overview]
![Palmora Group Hr Analysis](https://github.com/user-attachments/assets/378fad91-eff1-41a1-a287-340af03c9a27)
![Palmora Group Hr Analysis_Gender Salary Structure by Region](https://github.com/user-attachments/assets/67b84bc5-de22-4624-b30a-dc240b4ead1e)
![Palmora Group HR Analysis_Rating by Gender](https://github.com/user-attachments/assets/31760885-93f4-472e-956b-3749ea230843)
![Palmora Group HR Analysis_Gender Distribution by Region](https://github.com/user-attachments/assets/83fb212f-43b5-431b-9b52-9558cf4744eb)

Author
*David Reality Elegbe*  

Contact
Feel free to reach out for questions, collaboration, or feedback.

*David Reality Elegbe* 
 [davidelegbereality@gmail.com](mailto:davidelegbereality@gmail.com)
