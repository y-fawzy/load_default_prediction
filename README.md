# load_default_prediction

#objective
The aim of this project is to find the best model that predicts which loans are most likely to be late.

#Who will benefit?
The major clients to benefit from this project would be mostly financial institutions.

#function of final model
By being able to flag loans that will most likely be late, institutions can properly budget for those losses or even provide an early warning to the consumer.

#models tested
1. Logistic Regression
2. Random Forest
3. XGB Classifier

#results
Logistic regression was the best model found with the current data. A precision of 1 and a recall of 0.88.

#drawbacks and steps forward
Random forest and XGB used a smaller amount of data compared to Logisitc regression due to RAM restrictions.

To get better results, a stronger RAM may be used to test.


#folders in repo
1. data - contains the datasets(raw) used as well as wrangled data (processed)
2. notebooks - contains separate notebooks for each step eda, wrangling, statistical analysis, modelling as well pickled files of the models tested)
3. presentation - summarizes the data in an easy to read manner
4. proposal - contains the project proposal which was the first input to this project
4. reports - goes into more details regarding the project outcomes