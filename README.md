# adult
In this project, all experiments were done using Google Colab with CPU runtime around 2GB of RAM. The software versions used in Google Colab were Python3.12.12, Scikit-learn 1.6.1, Pandas 2.2.2, and NumPy 2.0.2. 

Using these versions allows others to run the code in Colab or install the same versions on their local machine.

The project tackles a binary classification problem on an adult dataset predicting whether annual income of an individual exceeds $50K/yr based on demographic and economic attributes. 

The Adult dataset obtained from UC Irvine Machine Learning Repository is from the 1994 Census database. The dataset consists of 48842 instances across 14 features of both categorical and integer feature types. The key properties of the dataset is that there are missing values and are denoted as “?” and the dataset is also imbalanced with 24720 instances belonging to <=50K and 7841 instances belonging to >50k.

FT9_Adult.ipynb is the baseline models that we have implemented, however due to the imbalance dataset we decided to implement oversampling on the dataset with an attempt to improve the model accuracy.
Two methods were chosen:
1) Random Over Sampling (ROS)
2) Synthetic Minority Over-sampling Technique (SMOTE)

The two methods were done seperatedly and saved in two additional files. 
1) FT9_Adult_Random_Over_Sampler
2) FT9_Adult_Improvement_MLP_SMOTE
