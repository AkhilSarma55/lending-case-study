Lending Club Case Study Goals of data analysis: Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.
The main objective is to be able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
Perform an analysis to understand the driving factors (or driver variables) behind loan default, i.e.the variables which are strong indicators of default.
The company can utilise this knowledge for its portfolio and risk assessment.
Please find the csv file and excel file which contains the explanation of various columns on data directory. Please run the jupyter notebook script by script to avoid errors.

Step.1 Data Cleaning and Manipulating

Step:2 Univariate Analysis

Insights from above univariate plots: There is a more probability of defaulting when :

A) Year wise Number of Applicants increasing Every year

B)The five major purposes of Loan applications are - ‘debt_consolidation’ , ‘credit_card’ , ‘other’ , ‘home_improvement’ & ‘major_purchase’

c)debt_consolidation’ is the highest loan purpose and renewable_energy is low loan purpose.

D)The distribution of loan amount i.e the amount of loan applied can be visualized from the above plot . It has been observed that the maximum loan range amount is between 5000-10000.

E)The percentage of Defaulters is the highest in Grade G group.

F)The percentage of risk of Defaulters is the largest in the Loan Purpose – ‘small_business’ , followed by ‘renewable_energy’ , ‘educational’ and so on.

G)The percentage of risk of Defaulters is maximum for customer experience - 10+ years & minimum for 9 year’s experience . Rest year of experience is in between

Step 3: Bivariate Analysis:

A)By doing bivariate analysis it has been observed that 10+ years of employee exp. Is having debt to income in maximum range apart from that rest year of employee exp. are more or less in same range.

B)By doing bivariate analysis it has been observed that the employee exp. With 10+ years is taking more amount of loan and those who are less than 1 year is taken less amount of loan.

Step 4:Results

Contributor Akhil Sarma Srushti

Developed as part of the Exploratory Data Analysis Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
