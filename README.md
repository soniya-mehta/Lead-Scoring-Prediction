# Lead-Scoring-Prediction

Problem Statement -
X Education sells online courses to industry professionals. X Education needs help in selecting the most promising leads, i.e. the leads that are most likely to convert into paying customers.
The company needs a model wherein you a lead score is assigned to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance.
The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%
Approach towards solving lead score case study - 
Step1: Reading and Understanding Data
Step2: Data Cleaning
Step3: Data Analysis
We started with the Exploratory Data Analysis of the data set to get a feel of how the data is oriented. In this step, we did univariate analysis of
 categorical and numerical features to find some patterns. Also, we analyzed heatmap for finding correlation among variables.
Step4: Creating Dummy Variables
Step5: Test Train Split
Step6: Feature Rescaling
Step7: Feature selection using RFE:
Step8: Plotting the ROC Curve
Step10: Computing the Precision and Recall metrics
Step11: Making Predictions on Test Set
 
Final Result
It was found that the variables that mattered the most in the potential buyers are (In descending order) :
- The total time spent on the Website. - Total number of visits.
- When the lead source was:
a) Olark chat
b) Welingak website
- When the last activity was:
a) SMS
b) Olark chat conversation
- When the lead origin is Lead add format.
- When their current occupation is as a working professional.
Keeping these in mind the X Education can flourish as they have a very high chance to get almost all the potential buyers to change their mind and buy their courses.
