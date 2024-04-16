# HBFC_Personal_Loan_Analysis_Excel-Project
Delve into my Excel project where I dissected HBFC personal loan data to unveil game-changing insights for marketing optimization. Explore how strategic recommendations and advanced analytical techniques were wielded to unearth actionable solutions. Dive in and discover the keys to unlocking success!
## Tech Stack used
<img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/c69248d4-f54b-42af-9fd9-3b1d346ac291" alt="Picture1" width="350" height="350">



## Objective
To analyze the personal loan data of HBFC Bank, identifying key customer profiles and behaviors from previous campaigns to inform targeted marketing strategies for future loan offerings.

## Data Description
| Column Name        | Description                                                             |
|--------------------|-------------------------------------------------------------------------|
| ID                 | Customer ID                                                             |
| Age                | Customer's age in years                                                 |
| Experience         | Years of professional experience                                        |
| Income             | Annual income of the customer ($000)                                     |
| ZIPCode            | Home Address ZIP code.                                                  |
| Family             | Family size of the customer                                             |
| CCAvg              | Avg. spending on credit cards per month ($000)                           |
| Education          | Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional    |
| Mortgage           | Value of house mortgage if any. ($000)                                   |
| Personal Loan      | Did this customer accept the personal loan offered in the last campaign? |
| Securities Account | Does the customer have a securities account with the bank?               |
| TD Account         | Does the customer have a Term deposit (Including Fixed and Recurring Deposits) account with the bank? |
| Online             | Does the customer use internet banking facilities?                       |
| CreditCard         | Does the customer use a credit card issued by the bank?                  |


# Getting Started

## Data Analysis

## Questions and Tasks

**1. Percentange of the customers who have availed personal loans compared to the ones who didn't avail personal loans?**
   
   I created a pie chart to visualize the proportion of customers who have availed personal loans compared to those who haven't. This chart provides a straightforward view of the distribution between the two groups.
   
   <img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/ab462e41-85dd-4246-a321-6f8b70f2884b" alt="1a" width="400" height="300">

**2. A Table with minimum, Maximum, Average, Median for the numeric variables like Age, Experience, Income, Family Members, CCAvg, Mortgage.**
   
   I created a multi-chart featuring bar graphs to visualize multiple variables simultaneously and it allows for easy comparison between different aspects of the dataset, providing insights into various trends and relationships within the data with numeric variables including age, experience, income, family members, CCAvg, and mortgage.
   
   <img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/2aedb4ff-648f-4390-8c4f-0b3e951cb017" alt="1b" width="550" height="350">

**3. A new categorical variable for Experience named Experience Category is done.**
   
   <img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/431b6a39-d43d-468b-a08f-c7b02b731d87" alt="1c" width="550" height="350">

**4. Scatter Plot Between Age and Experience.**
   
   Scatter plot between Age and Experience clearly follows a linear trend as Age increases experience also increase
   
   <img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/47df6fc2-aefe-4634-9ef5-fd303ec7596a" alt="1d" width="400" height="250">

**5. The top 3 areas (ZIP Codes) where the bank’s customers are located.**
   
   Generated a pie chart from a pivot table to visualize the top 3 areas (ZIP Codes) where the bank’s customers are located.
   
   <img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/6931a31b-e9e1-49b0-a316-21a073282b13" alt="1e" width="450" height="350">

**6. Count of customers who have a combination of Fixed Deposits and Credit Cards but not Personal Loan.**
   
   <img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/4ac91615-0110-47ef-8d01-781d12e0f895" alt="1f" width="400" height="300">

**7. Median income of customers Who have Availed Personal Loan vs median of those who haven't.**
   
   I've created a bar plot to compare the median income of customers who have availed a personal loan against the median income of those who haven't. This visualization offers a clear comparison between the two groups, highlighting any differences in income distribution and providing insights into the relationship between income and personal loan acceptance.
   
   <img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/58a0860d-8b33-41bb-b8ca-2200437840a0" alt="1g" width="400" height="300">




## Pivot Tables
Four pivot tables were created to analyze various relationships within the dataset:

1. **Education vs. Personal Loan:** Examining the percentage of customers with different education levels who availed personal loans.

2. **TD Account vs. Personal Loan:** Investigating the percentage of customers with Term Deposit accounts who also availed personal loans.

3. **Online vs. Personal Loan:** Evaluating the percentage of customers who use online banking facilities and availed personal loans.

4. **Income Category vs. Personal Loan:** Analyzing the percentage of customers falling into different income categories who availed personal loans.

These pivot tables provide valuable insights into how different factors correlate with the likelihood of customers availing personal loans.

<img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/4bbb8fb0-9349-4c7c-90e4-6365a1399c8b" alt="1h1" width="700" height="450">

<img src="https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/512366a3-2931-4f4b-a5d7-7f6e34070e41" alt="1h2" width="700" height="450">


# Dashboard
![1dashboard](https://github.com/Abdulmalik25/HBFC_Personal_Loan_Analysis_Excel-Project/assets/153974173/0bcec0fb-1025-4775-97ff-d5fdd8c07df2)

## Key Insights:

- **Personal Loan Acceptance Rate:** Approximately 9.60% of the bank's customers have availed personal loans, indicating the current acceptance rate.
  
- **Key Numeric Variables:** Analysis suggests that targeting customers with annual incomes over $100,000 could yield higher acceptance rates.
  
- **Experience Category:** Majority of customers fall into the Experienced category, followed by Entry Level. Targeting these customers could be cost-effective.
  
- **Scatterplot:** Age and Experience show a linearly increasing trend, indicating customer experience tends to increase with age.
  
- **Cross-selling Opportunities:** Only 3% of total customers have fixed deposits and credit cards but not personal loans, suggesting potential cross-selling opportunities.
  
- **Income vs Personal Loan:** Customers with higher incomes are associated with a higher likelihood of taking out personal loans.
  
- **Education vs Personal Loan:** Professionals and graduates show higher loan acceptance rates compared to undergraduates.
  
- **TD Account vs Personal Loan:** Customers without TD accounts are more likely to accept personal loans.
  
- **Income Category vs Personal Loan:** Customers with annual incomes above $100,000 have a higher likelihood of availing personal loans.

## Recommendations for Optimizing Marketing Campaign:

- Target marketing strategies on customers with annual incomes exceeding $100,000.
  
- Focus marketing campaigns towards professionals, graduates, and experienced individuals.
  
- Explore cross-selling opportunities for customers with fixed deposits and credit cards but no personal loans.


# Conclusion
This project aimed to analyze the personal loan data of HBFC Bank, identifying key customer profiles and behaviors from previous campaigns to inform targeted marketing strategies for future loan offerings. Through comprehensive analysis, we uncovered valuable insights regarding the acceptance rate, key numeric variables, customer experience categories, and cross-selling opportunities.

The findings suggest that targeting customers with higher incomes, focusing on professionals and graduates, and exploring cross-selling opportunities for specific customer segments could significantly enhance the effectiveness of marketing campaigns. By leveraging these insights, HBFC Bank can optimize its marketing strategies to better serve its customers and achieve higher loan acceptance rates.

Overall, this project has provided valuable insights into customer behavior and preferences, offering a solid foundation for informed decision-making in future marketing endeavors. It has been a rewarding experience, allowing for the development of knowledge and skills in data analysis and strategic planning within the banking sector.




