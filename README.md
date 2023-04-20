Parameter Optimization of SVM
Assignment for UCS654

About SVM and Parameter Optimization
Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.


Dataset
The dataset for the project has been downloaded from Kaggle
https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

The Diabetes prediction dataset is a collection of medical and demographic data from patients, along with their diabetes status (positive or negative). The data includes features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level. This dataset can be used to build machine learning models to predict diabetes in patients based on their medical history and demographic information. This can be useful for healthcare professionals in identifying patients who may be at risk of developing diabetes and in developing personalized treatment plans. Additionally, the dataset can be used by researchers to explore the relationships between various medical and demographic factors and the likelihood of developing diabetes.

Number of Instances: 55046
Number of Attributes: 9

Final Result Table
![image](https://user-images.githubusercontent.com/90766447/233329508-6f256d53-b5cf-43d4-b513-7c4e820e15e3.png)

Convergence Graph
![image](https://user-images.githubusercontent.com/90766447/233329695-62b74291-f4af-4632-832d-b93e61bcff4a.png)

Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.
The graph is made for the sample which has best accuracy. Sample 7 has the best accuracy of 0.93 having kernel = linear, Nu =7.91	 and Epsilon = 3.70.

Written By
Name : Diya Malhotra
Roll No. : 102003427
Sub-Group: 3Coe15
