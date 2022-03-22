# PySpark_Prediction_User_Churn
In this project I analysed a dataset of user interactions with a fictional music streaming service names Sparkify and predicted the user churn with Machine Learning.
The first part (01_Sparkify_Data_Exploration) takes a look at exploring and understanding the dataset.
In the second part (02_Sparkify_Feature_Engineering) features are created and in the third part (03_Sparkify_Modelling) several ML models are trained and evaluated.
The full description of the project can be fount in a blog post on [Medium](Link to article).

### Table of Content
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

The project was created with Python 3.6.3. The exact versions of each package used can be found in the requirements.txt
The packages imported can be found in the first section of each jupyter notebook.

## Project Motivation<a name="motivation"></a>

This project is my final and capstone project in the Udacity Nanodegree Data Scientist.

The goal of this project is to use a ML-based approach to predict the churn of users based on their past recorded activities.
Predicting customer churn is indeed an important topic for many businesses. A company needs strategies so make new users join but equally important to make them stay. No matter how good these strategies may be, the timing play an important role. If a company knew that a user thinks about churning soon they could offer him special discounts and make staying more likely. The company can't offer everyone a discount as that would not be profitable. Therefore predicting if a user is likely to churn is a very real and important problem to solve in many industries.

This is one of the reasons why I chose this project as my capstone project. Furthermore I wanted to work with the Apache Spark framework as it is often used in Big Data context.

## File Descriptions <a name="files"></a>


```
PySpark_Prediction_User_Churn/
│
├── README.md
├── requirements.txt
├── Sparkify.ipynb --> jupyter notebook with code for small local data subset
├── Sparkify.html
├── Sparkify_aws.ipynb --> jupyter notebook with code for aws cluster
├── Sparkify_aws.html
├── img/ --> png's created in jupyter notebook
├── models/ --> trained ML models
├── data/ --> input data JSON file

```


## Results<a name="results"></a>



## Licensing, Authors, Acknowledgements<a name="licensing"></a>

