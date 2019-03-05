# Project 2 - Ames Housing Data and Kaggle Challenge

# README



    
## Aiming for the Right Price 
 
#### Ames Housing Data and Kaggle Challenge
#### Project 2 
    
### Christopher Williams

### DSI 2018
### December 7, 2018



## Contents of project-2 (folder)
AmesHousing.txt
Assets (folder) - with images of graphs, charts, etc.
cw_ames_ridge_model_v1_99f_log.csv
--- final model 
datasets (folder)
--- train.csv
--- test.csv
Project 2 - CW FINAL.jpynb
--- jupyter notebook of code
Project 2 Power Point.pdf
Project 2 Power Point.pptx
README



## Objectives

We were tasked with creating a regression model based on the Ames, Iowa Housing Dataset to predict the price of houses at sale from 2006 to 2010 that were withheld from us in the test dataset. The datasets are found in this Project 2 Folder Titled: test.csv and train.csv


## Set-up of Kaggle Competition

Before you begin working on this project, please do the following:

1. Sign up for an account on [Kaggle](https://www.kaggle.com/)
2. **IMPORTANT**: Click this link ([Regression Challenge Sign Up](https://www.kaggle.com/t/cf68f4a276f44b59a3c6c843dbf9ed1e)) to **join** the competition (otherwise you will not be able to make submissions!)
3. Review the material on the [DSI-US-6 Regression Challenge](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge)
4. Review the [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).


## The Modeling Process & Evaluation

1. I used the train dataset to generate and refine my models to perform on the test dataset, which has all of those columns except for the target that I am trying to predict in my Regression model.

2. I generated the regression model using the training data. I made use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)

3. I predict the values for your target column in the test dataset and submitted my predictions to Kaggle to see how my model did against unknown data.

4. Evaluating my models!
    - considered my evaluation metrics
    - considered my baseline score
    - how can my model be used for inference?
    - why do I believe my model will generalize to new data?


## Covered in Power Presentation and Contained within "Project 2 - CW Final" Jupyter Notebook

### The Data Science Process

**Problem Statement**
Create a regression model based on the Ames Housing Dataset to predict the price of a house at sale.

**Data Cleaning and EDA**

**Preprocessing and Modeling**

**Evaluation and Conceptual Understanding**

**Conclusion and Recommendations**
