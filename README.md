# RandomForest_DecisionTree_Classifier_Model

Provided with data from a lending company with roughly 10,000 entries. Completed some initial data exploration to see if I could find any standout correlations. Some features I looked closely at were the FICO score of an individual as well as how that correlates to interest rates given to prospective loanees. Additionally, seeing how strong of a correlation there was between the amount of people who full paid back loans and what the purpose of the loan was. The dataset was relatively straightforward and the only processing to be done was converting the categorical feature of 'Purpose' to dummy variables so our models could better understand them. 

I initially constructed the Decision Tree Classifier to see how it would perform in classifying if an individual would pay back a loan. It performed with approximately 74% accuracy which is not bad but we could do better. After that I tested out using a Random Forest Classifier. I made four different models with various estimators ranging from 25,50,75,100. While they are performed in the same ballpark of 84% accuracy I decided the 100 estimators would suffice.

Programming Languages: Python

Tools/Libraries: Pandas, NumPy, SciKit-Learn(SKLearn), Matplotlib, Seaborn, Jupyter Notebook
