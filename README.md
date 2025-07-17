The Task

Your objective is to understand and parepare the dataset for analysis, train a predictive model for classifiying ( distinguishing ) diseased patient (metabolic disorder) from a healthy individual and evaluate the model.

A complete list of analysis can be found below.

1.Load the data set.

2.Exploratory analysis to better understand the data.

    2.1 Example : Properties of features, outliers, missingness, correlation bwtween features
    2.2 How will you divide training and test data.

3.How will you deal with missing data. Clearly explain your approach.

4.Unsupervised analysis. Investigate trends and patters in data through some unsupervised learning approaches. 
    4.1 Please also look for inherent sub group of patients

5.Train a supervised predictive model (also known as classifier ). 
    5.1 Train classifiers. You can train multiple classifiers and see which one works best.
    5.2 Evaluate your model training performance.
    5.3 Use and compare different performance evaluation metrics 
    5.4 Use cross validation to evaluate variation in training perforamnce 
    5.5 Is your model overfitting ?

6.Result interpretation 
    6.1 Which is the most important feature ? 
    6.2 What happens to your classification performance if you exclude the best feature and retrain your classifier ?

7.Prepare a presentation with your analysis summary and result



The Data

We have created four (4) different datasets: 

    patients_01.csv 
    patients_02.csv 
    patients_03.csv 
    patients_04.csv

 

Each file contains a different set of samples. The clinical features however remain identical across the data sets.  A description of the features can be found here :  Feature_Data_Description.txt 

Each member of the group will work on different data sets. Among the group members, you can discuss analytical approaches, challenges and result interpretation. But it is important to remember that no two team members should work on the same dataset.

The data has one target column, which indicates whether a sample (patient) has the disease or not. The feature data is a mixture of continuous numerical values and categorical values.



Target Column

Target column : dissease It has two labels :

TRUE
FALSE



Feature Columns

age gender bmi alcohol_misuse high_bp high_col chol_check history_smoking history_stroke history_heart_disease amount_activity fruits vegetables health_gen health_men health_phys walking_diff

For a detailed description of each column can be found in the following file : Feature_Data_Description.txt

