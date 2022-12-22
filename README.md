# covid-deaths-model
Analyzing a huge covid 19 dataset and creating a Logistic Regression Model to predict death situations.

The Dataset: The dataset contains ~ 1,000,000 instances with 21 columns containing information about patients such as sex, date died, age, diabetes etc. In  Boolean features of the dataset, 1 means "yes" and 2 means "no". Values such as 98 and 99 signify missing data.

Model Methods: Several python libraries were used to pre-process the data, as well as program and visualize the solution (pandas, numpy, seaborn, matplotlib, imblearn and scikit). I created a new column 'DEATH' to act as our target column, and analyzed the 'DATE_DIED' feature to see whether patient died or not. Used RandomUnderSampler to deal with the imbalanced data, as well as StandardScaler and get_dummies for data pre-processing. Made use of the Logistic Regression algorithm for my model. The model predicts the likelihood of a death from covid with 90% accuracy.
