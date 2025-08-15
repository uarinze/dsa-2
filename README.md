# dsa-2
Second data analysis project for Incubator hub

# Palmora Group HR Analysis
## Case Study: Palmora Group HR Analysis   
The Palmoria Group, a manufacturing company based in Nigeria, is embroiled in issues 
bordering on gender inequality in its 3 regions. Unfortunately, the media recently 
published the news with the headline “Palmoria, the Manufacturing Patriarchy”. This 
doesn’t look good for the owners of the business, based on their ambition to scale the 
business to other regions and even overseas. Cases like this can only spiral downwards, 
revealing other issues like the gender pay gap, amongst other possible issues. 
The CEO of Palmoria, Mr Ayodeji Chukwuma, is keen to address these issues before they 
get out of hand. The CHRO, Mr Yunus Shofoluwe, has been assigned the task to identify 
key areas within the business that could give rise to issues and address them immediately. 
Mr Shofoluwe decided to recruit you as an HR Analytics expert to analyse the company’s 
HR data and come up with recommendations for management’s attention. “Now, the 
future of gender equality in Palmoria lies in your hands” – the exact words of Mr 
Shofoluwe before he handed the data to you. 
CASE SCENARIO 
●  Analyse the company data and generate insights that the Palmoria management 
team would need to address 
● Your analysis should be visualised using appropriate charts 
● Your focus should be on gender-related issues within the organization and its 
regions 
● The insights required are based on your discretion. However, Mr Gamma, as an 
insider, has offered to give you pointers on areas you need to pay attention to  
Required: 
● Generally, there are two genders in the organization. However, some employees 
refused to disclose their gender. You would need to assign a generic gender status 
to these employees 
● Some employees are without a salary because they are no longer with the company. 
You will need to take those employees out 
● Lastly, some departments are indicated as “NULL”. These departments would also 
need to be taken out. 
Pointers from Mr Gamma 
1. What is the gender distribution in the organization? Distil to regions and 
departments 
2. Show insights on ratings based on gender 
3. Analyse the company’s salary structure. Identify if there is a gender pay gap. If 
there is, identify the department and regions that should be the focus of 
management 
4. A recent regulation was adopted which requires manufacturing companies to pay 
employees a minimum of $90,000 
● Does Palmoria meet this requirement? 
● Show the pay distribution of employees grouped by a band of $10,000. For example: 
● How many employees fall into a band of $10,000 – $20,000, $20,000 – $30,000, 
etc.? 
● Also visualize this by regions 
Case Questions 
5. Mr Gamma thought to himself that since you were already working on the employee 
data, you could help out with allocating the annual bonus pay to employees based on the 
performance rating. He handed you another data set that contains rules for making bonus 
payments and asked you to: 
●  Calculate the amount to be paid as a bonus to individual employees 
●  Calculate the total amount to be paid to individual employees (salary inclusive of 
bonus) 
● Total amount to be paid out per region and company-wide

#############################################################################################

# ANALYSIS REPORT
## Executive Summary
Palmoria Group, a manufacturing company based in Nigeria, is facing public scrutiny over gender inequality across its three operational regions. This report presents a detailed analysis of the company’s HR data, focusing on gender distribution, performance ratings, salary structure, and compliance with regulatory pay standards. It also includes bonus allocation based on performance ratings.

## Data Cleaning & Preparation using PowerBI
Before analysis, the following data adjustments were made:
Employees with undisclosed gender were assigned a generic label: "Undisclosed".
Employees with missing salary data (no longer with the company) were excluded.
Records with "NULL" departments were removed from the dataset.

## Analysis & Insights
### 1. Gender Distribution
A total of 38 employees did not disclose their gender, while 406 and 430 identified as female and male respectively.
Please see the tables below for a distribution of gender across the 3 locations of Palmoria company and accross the various departments in the company.

<img width="2205" height="1344" alt="1-gender_distribution" src="https://github.com/user-attachments/assets/a3a59dca-3ce8-4e71-b9ce-03a4aacbec48" />


**Insight:**  From the tables we see a difference of 24 in the numbers, with males being higher than females in the company-wide analysis of Palmoria Company. However a total of 38 persons have refused to disclose their genders and this number may have an effect in the total gender distribution as it is greater than the difference among those that disclosed their gender. 
According to the gender distribution by location, there seem to be a fairly equal number of both Male and Females, in two locations apart from Kaduna where there is a higher number of males than females.
Accounting, Legal, Sales, and Support departments have a higher number of males than females, while Business Development and Services department have a slightly higher number of female staff. 

### 2. Performance Ratings by Gender
Among people who identified their gender, Females received more "Very good" ratings than male and males, on the other hand, received more "Average", "Poor" and "Very poor" ratings.

<img width="1306" height="443" alt="2-ratings_distribution" src="https://github.com/user-attachments/assets/9b000895-67b6-4f51-b7a1-3e659264173d" />


**Insights:**  It could be infered that females performed better than males.

### 3. Salary Structure & Gender Pay Gap
On the average, males earn higher than females in Palmoria, despite females performaing better as seen by the performance ratings. Perhaps the management have to take steps to address this.

The tables and chart below summarises the data on salary by gender and also distributed by departments.

<img width="1534" height="1340" alt="3-salary_structure" src="https://github.com/user-attachments/assets/9946f6e2-2839-458f-a40a-4e1ebbe9146e" />


**Insights:**  It is seen that males earn slightly higher than females on the average with a difference of about $2,500. Looking at the average salary by gender in the departments, we see that there is a difference of over $5,000 in majority of the departments, with females earning higher in Engineering and Marketing departments, while males earn higher in the Accounting, Business Development, Human Resources, Product Management, Services and Support departments.

### 4. Regulatory Compliance: Minimum Salary of $90,000
Compliance Status: 31%
Employees earning ≥ $90,000: 275
Employees earning < $90,000: 599

Salary Band Distribution:
Salary Band	  Employee Count
$10k–$20k	     0
$20k–$30k	     22
$30k–$40k	     93
$40k–$50k	     83
$50k–$60k	     82
$60k–$70k	     82
$70k–$80k	     105
$80k–$90k	     91
$90k–$100k     84
$100k–$110k    94
$110k–$120k    92
> $120k        0

Region	% Above $90k
Abuja     41.3%
Kaduna    44%
Lagos     50.3%

<img width="1186" height="676" alt="4-90k_compliance" src="https://github.com/user-attachments/assets/07364050-a88c-49ea-ab3a-74bf90b24dd3" />


**Insight:** : 275 out of 874 persons earned $90,000 or more showing a compliance rate of 31%. The % compliance in the different regions are: Abuja 41.3% Kaduna 44% Lagos 50.3% 
Management may want to look into modifying the salary structure to ensure the minimum salary is the recommended legal amount.
The salary structure ranged between $20,000 and $120,000. 
Breaking the salary structure into salary bands of $10,000, we find that 92 staff are in the highest range, while 22 are in the lowest range. In between the number of staff seem to be between 82 and 93 per salary band.
By region, Lagos has the highest proportion of employees earning above the regulatory threshold.

### 5. Bonus Allocation Based on Performance
Bonus pay = rating bonus % * salary

<img width="1074" height="1342" alt="5_1-bonus" src="https://github.com/user-attachments/assets/aa8ad77b-fe88-421f-89c4-9d03586a36f5" />


**Note:** The Bonus rules was used to calculate the bonus earned by each employee. Employees without any rating was assigned a bonus rate of 0, and consequently did not earn any bonus.

Total amount paid = Bonus pay + Salary


<img width="980" height="1330" alt="5_2-salary_and_bonus" src="https://github.com/user-attachments/assets/e6bd5e8b-dd68-4df0-8f02-bc579088e0d9" />


**Note:** This is the total amount earned by each employee (Salary + Bonus).


Total amount to be paid per region:
Abuja: $24,917,424.21
Kaduna: $27,478,731.78
Lagos: $19,526,793.31

<img width="493" height="743" alt="5_3-amount_by_region" src="https://github.com/user-attachments/assets/194643c2-0803-4e28-8f20-a7f288e123da" />


**Note:**  Kaduna region has the highest amount paid to employees at $ 27.5 million. Abuja comes second with Lagos being the least with about $19.5 million.

**Insight:** Bonus allocation aligns with performance ratings, but disparities in base salary still affect total compensation.

## Conclusions
Generally there is no significant difference in the gender makeup of the Primoria company, how ever perhaps more effort should be made to recruit more women. 
It also of note to point out that in majority of the departments males earned higher than females despite performing similar tasks. The management might want to look into this gender pay gap and address it in a timely mannar.

## Recommendations
Address Gender Imbalance:
Launch targeted recruitment for women in technical departments.
Promote mentorship and leadership programs for female employees.

Close the Gender Pay Gap:
Conduct salary audits and adjust pay in departments with significant gaps.
Implement transparent compensation policies.

Ensure Regulatory Compliance:
Review salaries in the North region and adjust to meet the $90,000 minimum.
Enhance Performance-Based Rewards:
Consider additional incentives for top performers in underrepresented groups.
