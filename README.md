# Bank_Personal_Loan_Prediction
Campaign for selling personal loans.

This case is about a bank (Thera Bank) which has a growing customer base. Majority of these customers are liability customers (depositors) with varying size of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget.

The department wants to build a model that will help them identify the potential customers who have higher probability of purchasing the loan. This will increase the success ratio while at the same time reduce the cost of the campaign.

The file Bank.xls contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

# Column descriptions
<ul>
<li>ID:	Customer ID							
<li>Age:	Customer's age in completed years							
<li>Experience:	#years of professional experience							
<li>Income:	Annual income of the customer ($000)							
<li>ZIPCode:	Home Address ZIP code.							
<li>Family:	Family size of the customer							
<li>CCAvg	Avg.: spending on credit cards per month ($000)							
<li>Education:	Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional							
<li>Mortgage:	Value of house mortgage if any. ($000)							
<li>Personal Loan:	Did this customer accept the personal loan offered in the last campaign?							
<li>Securities Account:	Does the customer have a securities account with the bank?							
<li>CD Account:	Does the customer have a certificate of deposit (CD) account with the bank?							
<li>Online:	Does the customer use internet banking facilities?							
<li>CreditCard:	Does the customer use a credit card issued by UniversalBank?	
</ul>

<b>Objective:</b> The classification goal is to predict the likelihood of a liability customer buying personal loans.

<b>Task</b>

1. Read the column description and ensure you understand each attribute well
2. Study the data distribution in each attribute, share your findings.
3. Get the target column distribution.
4. Split the data into training and test set in the ratio of 70:30 respectively
5. Use different classification models to predict the likelihood of a liability customer buying personal loans 
6. Print the confusion matrix for all the above models
7. Give your reasoning on which is the best model in this case and why it performs better?

<b>Algorithms Used:</b>
1.LogisticRegression,
2.Support Vector Classifier,
3.Gaussian NB,
4.KNN,
5.Ramdom Forest Classifier,
6.Gradient Boosting,
7.Ada Boosting,
8.Bagging,
9.Decision Tree

<b>Libraries Used:</b>
Pandas, NumPy, Matplotlib, SeaBorn, SKLearn,matplotlib
