# cs81_Final_Project

Idea Title
-----------
Detecting Potential Bad Loans

Idea Description
-----------------
Bad Loans are a big problem for Banks. Many banks have closed due to bad loan/credit approvals resulting in nonpayment and bank failure.  Our project idea is to use one or more machine learning algorithms to assist the bank in making prudent loan decisions based on previous customer data.

Data Source 
-----------
We will use open data source of real world data from www.lendingClub.com

General Plan of Attack
-----------------------
1. Wrangle the data set creating a training set of useful parameters.
2. Do some data exploration and visualization.
3. Train a machine learning model to determine the interest rate that the bank should charge based on an applicant’s application data.  Experiment with different modeling techniques and use the model that provides the highest accuracy.
4. Train a machine learning model to classify good (repays loans) vs bad (defaults on loans) using available customer attributes.  This model uses interest rate as a feature.
5. Wrap the 2 models in a web based application which allows the customer to enter a loan application.  Shiny or Javascript are 2 leading options we were thinking of to build the web interface.  
6. Using the loan application data from item 5 above, compute the interest rate using the model in item 3 above, then make a default prediction using the model in item 4 above.  Some features for this aspect of our project will have to be synthesized.  For example, we have no way of checking how many derogatory public records are associated with an application when computing if a loan is good or bad so derogatory public records must be synthesized.
7. Stretch Option 1: If the loan was denied, provide feedback to the customer about the most likely reason why the loan was denied.  We are not sure how to do this yet and may seek help from the teaching staff for ideas.
8. Stretch Option 2: If a loan is denied, present the user with a screen where they can adjust critical loan determination sliders to see what parameter changes would change the loan from denied to approved.

Notes:
------
1. Neither of the project partners has any experience with shiny or Javascript and one of the main goals of the project is to gain experience in one of these technologies.  We expect to try shiny first and only switch to something else if we find a technical reason why we can’t make it work.
