# STAT3612 Statistical Machine Learning: Group Project
The theme of the project is interpretable machine learning (IML) with applications to a real data case study in the banking industry. 
For an IML model, both “prediction accuracy” and “model explainability” are equally important.

The data includes about 10,400 anonymized Home Equity Line of Credit (HELOC) loans together with 23 raw features. 
Note that in the second Excel file the monotonicity constraints are included in the data dictionary, 
which are based on the prior knowledge about the input-output relationships.

Our group has built two sets of machine learning models, one without the monotonicity
constraints and the other one with the monotonicity constraints.
Our group ID was used as the random seed for splitting data into training (80%) and testing (20%) sets.
We have built our final IML models based on the training data only. 
We did not restrict the choice of feature engineering techniques or machine learning algorithms.
