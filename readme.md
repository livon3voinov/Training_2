# обучение с учителем 

## The project aimed to create a model to predict the probability of a decrease in consumer activity based on data.
The main stages: 
- Data preparation: correction of category names, replacement of outliers in the data with medians, elimination of multicollinearity. 
- Modeling: logistic regression, decision tree, kNN and support vector machine models were used. MinMaxScaler and Standard Scale r, feature encoding (OHE, OrdinalEncoder) were used for preprocessing. The selection of features was performed using Select K Best. The main metric is Recall, to minimize the skipping of buyers with the risk of reduced activity. 
- Result: the best model was Logistic Regression(C=1, penalty='l1', random_state=42, solver='liblinear') it showed 88.5% correct answers in the training sample and 83.6% in the test sample%
