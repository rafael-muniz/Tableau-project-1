**<h1>Tableau Project</h1>**

<br>

**Date: August 17<sup>th</sup>, 2023**

<br>
<br>

**Group members:**

Ali Mirza ()

Andres Ramirez ()

Gizelle Lao ()

Rafael Muniz ()

Trung Le ()

<br><br>


<h2>I. Business Problem Definition and Dataset Overview 
</h2>


**Business Problem**

The objective of this analysis is to provide insightful information from the data explored, using our data analytics habilities to **understand more about the demographics and characteristics of the customers, through descriptive analytics**. The insights taken could be used to better target the marketing campaigns, increasing customer volumes with controlled risk.

**Dataset Overview**

The data analyzed in this report is taken from the ‘Finance Loan approval Prediction Data’ dataset on Kaggle (Raj, 2023). The raw dataset comprises 614 records and 13 variables, which consist of 8 categorical and 5 numeric variables. The independent predictor variables are based on customer details, such as, gender, marital status, education, income level, credit history, existing loan amount etc. The dependent variable is ‘LoanStatus’, which indicates ‘Yes’ if the home loan was approved and ‘No’ otherwise. The data cleaning process involved removing 124 missing values that reduced the dataset to 490 records. These records will be analyzed through various visualizations for answering the analytics questions that follow in this report. \

<br>
<h2>II. Analytics Questions for Loan Approval Optimization
</h2>


**Q1.  What is the distribution of Applicant Income and how does credit history affect loan approval?**

Understanding the distribution of applicant income and credit history will help in identifying the income range of most applicants. This information can be used to set appropriate income thresholds for loan eligibility, ensuring that applicants with sufficient income are considered for approval. In addition, comparing credit history to loan approvals will allow us to assess its influence on loan application decisions. \
 \
**Q2. What is the relationship between Applicant Income and Loan Amount?**

Analyzing the relationship between applicant income and loan amount will help in determining how much loan amount applicants typically request based on their income. This insight can be used to set appropriate loan-to-income ratios, which are crucial for assessing an applicant's repayment capacity.

 \
**Q3. Does marital status impact the loan approval rate?**

Investigating the impact of marital status on the loan approval rate can reveal whether married applicants tend to have a higher likelihood of loan approval. If there is a significant difference in approval rates between married and unmarried applicants, the business can tailor its loan products or eligibility criteria accordingly. \


**Q4. What is the proportion of loan approval based on education level?**

Examining the proportion of loan approvals based on education level will provide insights into whether education plays a significant role in the loan approval process. This information can help in determining if there is a bias towards certain educational backgrounds and assist in designing fair and inclusive loan approval policies.

<br>

<h2>III. Data Visualizations for Deriving Key Insights</h2>


**Q1.  What is the distribution of Applicant Income and how does credit history affect loan approval?**

![image](https://github.com/rafael-muniz/tableau1/assets/58666861/b581a063-cba4-4d6b-a30f-5f910af50006)




**Figure 1**: Applicant Income based on Loan Status and Credit History

<br>

**Insights**

The histograms in Figure 1 were developed to describe the distribution of applicant income and explore how credit history influences the outcome of loan approval. Examining the two histograms, representing approved and rejected loans, we observe a similarity in the shape of the distribution for these two scenarios, with peak income in the $4,000-$4,999 range. The chart on the left clearly shows that most applicants have a credit history and also most of their applications get approved. On the other hand, the chart on the right depicts that there are very few applicants without credit history and most of their applications are rejected. In this context, the introduction of credit history as a factor is noteworthy. This demonstrates that credit history has a critical impact over loan approval decisions.

**Recommendations**

Based on these findings, it is recommended for financial institutions to streamline the loan approval process for individuals by assigning higher weightage to credit history. However, it's important to note that the dataset lacks information regarding individuals' credit scores, making it difficult to determine how specific credit scores correlated with loan approval. Consequently, further investigating additional borrower factors, such as demographics and geographic location, becomes important for refining loan recommendations.

<br><br>

**Q2. What is the relationship between Applicant Income and Loan Amount?**


![image](https://github.com/rafael-muniz/tableau1/assets/58666861/60dba006-1eb2-4f2d-9b95-70347d532e03)



**Figure 2**: Scatter plot of Loan Amount vs. Applicant Income

<br>

**Insights**

This scatter plot above (Figure 2) was plotted to demonstrate the relationship between two numeric variables (measures), to understand better if they have any relationship with each other. After plotting the mentioned graph and drawing the correlation line, we notice that there is a positive correlation between applicant income and loan amount, which means that the greater the applicant’s income is the higher the loan amount.

Another insight from this graph is the market concentration among people with monthly income between approximately $2K and $5K.

**Recommendations**

Once the company decides the customer’s income range it wants to target, the correlation line should be used as one of the parameters to analyze the loan’s acceptance, knowing if the applicant’s proposed loan amount deviates significantly from the correlation line then the application can be denied or need stronger support for approval.

This type of analysis will give the company an advantage when doing the risk assessment for the application, lowering the default risk of a loan in the future, when combining with other analysis. \

<br><br>

**Q3. Does marital status impact the loan approval rate?**


![image](https://github.com/rafael-muniz/tableau1/assets/58666861/13280548-f243-4b24-9229-62e9d8b5feb2)



**Figure 3**: Loan Status by Marital Status

<br>

**Insights**

Loan acceptance rates according to applicants' marital status are shown in Figure 3. The goal is to identify how marital status affects loan approval rates and offer suggestions for enhancing these rates at the lending institution. This information demonstrates a distinct correlation between loan approval rates and marital status. The approval percentage for loans of non-married applicants is 21.88% (105 approvals out of 480 applications). In turn, the loan approval percentage for applicants who are married is 47.29% (227 approvals out of 480 applicants). This shows that being in a marital relationship increases the chances of getting a loan approved.

Married people also had a greater percentage of loan approval, which suggests that their financial conditions may be more stable or that they pose a reduced risk to lenders. This might be the result of joint financial obligations, increased combined incomes, or other aspects of marriage.

Additionally, even though married candidates already have a better loan acceptance percentage, there are far more married applicants overall than single applicants. This offers the lending company the chance to concentrate on marketing and customizing loan products exclusively for married people to grow their clients and loan portfolio.

**Recommendations**

First, the lending organization needs to create special loan packages for married applicants based on the information it has gathered. These items may provide special advantages or special terms that cater to the special requirements and preferences of married people. This strategy can increase the number of married borrowers who apply and raise loan approval rates.

Secondly, the lending institution should concentrate on enhancing data collection in order to streamline the loan approval procedure. Data-driven decision-making can be made possible by collecting more applicant data, such as the applicant’s age, educational history, and the reason for the loan.

<br><br>

**Q4. What is the proportion of loan approval based on education level?** \


![image](https://github.com/rafael-muniz/tableau1/assets/58666861/71769da0-276a-4b9a-ac10-a4ed0616bb67)




**Figure 4:** Loan Status by Education Level

<br>

**Insights**

The pie chart in Figure 4 depicts the distribution of loan approval status by education level. The goal is to assess how the level of education affects the loan approvals. As previously mentioned, Figure 4 shows that the pie for graduates is much bigger than that of non-graduates. This is because the number of graduate loan applicants is much higher than the number of non-graduate applicants, which suggests that graduates are more likely to apply for home loans than non-graduates.

Besides, graduates have a higher approval rate of 71% compared to non-graduates with a rate of 63%. This suggests that education plays a role in influencing the likelihood of loan approval. The approval rate for non-graduates is slightly lower, indicating that education could influence the risk assessment process. This might be due to non-graduates being perceived as having potentially lower income or stability, impacting their loan eligibility.

Lenders might lean towards granting loans to graduates due to their higher approval rates. This could be because graduates are often associated with more stable income sources and a better ability to manage financial commitments.

**Recommendations**

Considering the insights, the business can tailor its marketing strategies according to education levels. For example, by focusing on graduates with targeted messaging that emphasizes their higher approval rates, the company can potentially attract more applicants from this segment. 

Conversely, the company can provide educational content and resources to non-graduates to enhance their financial literacy and stability, improving their eligibility and approval chances. This could include budgeting or credit management workshops.

<br><br><br>

<h2>IV. References</h2>


Raj, K. (2023). _Finance Loan approval Prediction Data_. Kaggle. Retrieved August 12, 2023, from https://www.kaggle.com/datasets/krishnaraj30/finance-loan-approval-prediction-data

