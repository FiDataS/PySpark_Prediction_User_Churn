# PySpark_Prediction_User_Churn
In this project I analysed a dataset of user interactions with a fictional music streaming service names Sparkify and predicted the user churn with Machine Learning.
The first part (01_Sparkify_Data_Exploration) takes a look at exploring and understanding the dataset.
In the second part (02_Sparkify_Feature_Engineering) features are created and in the third part (03_Sparkify_Modelling) several ML models are trained and evaluated.
The full description of the project can be fount in a blog post on [Medium](https://medium.com/@franziska.braunschneider/prediction-of-user-churn-machine-learning-on-pyspark-14839799a16f).

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
├── 01_Sparkify_Data_Exploration.ipynb --> jupyter notebook with code for data exploration of small local data subset
├── 01_Sparkify_Data_Exploration.html
├── 02_Sparkify_Feature_Engineering.ipynb --> jupyter notebook with code for feature engineering on small local data subset
├── 02_Sparkify_Feature_Engineering.html
├── 03_Sparkify_Modelling.ipynb  --> jupyter notebook with code for modelling on small local data subset
├── 03_Sparkify_Modelling.html
├── best_models_zip.zip --> best models stored in pickle files, result from 03 Modelling
├── data/ --> feature dataframe in json format, result from 02 Feature Engineering notebook

```


## Results<a name="results"></a>

The findings are described in detail on the blog post on [Medium](https://medium.com/@franziska.braunschneider/prediction-of-user-churn-machine-learning-on-pyspark-14839799a16f).

After understanding the Business context and a definition of churn, a smaller subset of the full dataset was explored. Then the Preprocessing steps were described in detail. The dataset was cleaned, churned users were labeled and several feature columns were created. I then proceeded to check the dataset for Multicollinearity and selected the features to train the model on based on the result. Finally the dataframe to model on was created and checked for imbalance. Since the dataset was indeed imbalanced possible risks and measurements were discussed and the chosen steps taken to deal with the topic. The prepared data was then trained on five different classifiers and based on the smaller subset of data the Gradient-boosted Tree Classifier performed the best.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I give credit to Udacity for the dataset.

Feel free to use my code as you please:

Copyright (c) 2022 Franziska Braun

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
