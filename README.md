# Covid-Drug-Discovery
Machine Learning Model for Covid Drug Discovery for Covid19 using SARS Model




Assumptions:
1) Path taken is relative in Google Colab

2) Environment : Google colab

3) Smiles are handled through mol2vec library which is installed through https://www.kaggle.com/vladislavkisin/tutorial-ml-in-chemistry-research-rdkit-mol2vec.

4) What it does in simple words is seeing the patterns in the smiles and seeing the pattern of covalent bonds with c and H molecule assigns a number through which the prediction can be made. 

5) As we know this is a regression problem so we train after preprocessing the smiles and then using svm SVR I.e the regressor to train and then predict on the test data.

6) We split the data into training and validation for hyperparamaters prediction and then again train the svm model with entire training data without any split and then predict the output on the given test data and then fill the predictions on the second column of the data frame for test.
