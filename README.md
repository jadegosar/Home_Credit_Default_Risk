# Home Credit Default Risk
	
There is a vast amount of borrowers who experience difficulty getting a loan they have the ability to repay due to a range of factors from insufficient
credit histories to non-existent data in areas that have historically been used to determine default risk. A borrower's inability to provide proof of credit
accountability can lead to these clients being taken advantage of by untrustworthy lenders or being unable to obtain a loan from a trusted institution.
Additionally, without sufficient financial and credit histories for customers, it becomes more difficult for lenders to identify and predict which customers are at
risk of default and what factors are contributing to the risk assessmet. This leads to a mis-identification between both groups, where both customers who are
likely to default are given loans, which immensely costs the business, and customer's who are reliable borrowers are denied the opportunity to obtain a loan and
potential clients are lost.  
	
The project objective is to create a supervised analytical model to help Home Credit predict how capable each applicant is of repaying a possible loan, giving them
the ability to intervene before borrowers default and reach an underserved population. Our group's solution to this business problem was to create a various
predictive models to show important factors of default that Home Credit has data available for as well as improve the firm's ability to capture reliable borrowers
who historically have not been given loans. Our final model was a Random Forest model with tuned hyperparameters that returned important insights into what factors
contribute to default risk as well as an improved performance over the current model of always predicting no default.

My contribution to the project was creating a Decision Tree and Random Forest model with tuned hyperparameters. Additionally, I created visualizations to
illustrate relationships between the variables during our EDA process and compared the customers our model predicted would default to the actual defaulters to
contextualize how much our model would save the business. Lastly, I compared the distributions of various important predictors in both the predicted defaulters and
the actual defaulters to see if our model impacted the current customer base for Home Credit. The business value of the solution is $505,160,164 which is the
estimated greater ROI of random forest model over majority classifier performance in the normalized currency value that the dataset is in. This solution assumes
simple interest rate of 18.912% (based on prior median rate) and the principal is fully recoverable.

The main two difficulties that our group encountered was manipulating many variables that we thought could be important but were missing large amounts of data and
dealing with an imbalanced dataset where less than 10% of the target variable was in the group that we were trying to predict (defaulters). This led us to upsample
the dataset, meaning we could balance out the dataset we were training the models on to a 50/50 split of the target variable. However this does not actually
increase the information that our model is using to predict the target class but rather just takes random samples from the target class of interest to balance the
data meaning that we still ran into limitations due to lack of data that we have available on defaulters.

My biggest takeaway from this project was really just gaining a better knowledge of all the steps of a data analytics project in the real world. From dealing with
imblanced data to applyng a model and tuning it to perform better, this project has taught me how to break down an analytics business problem into steps, that
although have to be repeated many times, break down a problem that may seem very abstract into actionable insights.
