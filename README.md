# Project: University Student Admission Prediction
> The goal of this project is to predict the admission of a student in an University.

> Dataset: https://www.kaggle.com/adityadeshpande23/admissionpredictioncsv

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Deployment](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
The goal of this project is to predict the admission of a student in an University taking into account the following points:
- General test score (GRE).
- Test of English as a Foreign Language score (TOEFL).
- University rating.
- Statement of Purpose (SOP).
- Letter of Recommendation (LOR). 
- Cumulative Grade Point Average (CGPA).
- Whether the student has experience in research or not.

Purpose: Practice the implementation of different Regression Machine Learning models till deployment (Heroku).

## Technologies Used
- Python 3.8.12
- Flask 2.0.2
- Werkzeug 2.0.2
- Heroku 7.59.1

Machine Learning algorithms used: Linear Regression, Lasso, Ridge, ElasticNet, Decision Tree, Random Forest, KNN, SVM.


## Setup
requirements.txt:
- app==0.0.1
- certifi==2021.10.8
- chardet==4.0.0
- click==8.0.3
- Flask==2.0.2
- Flask-Cors==3.0.10
- gunicorn==20.1.0
- heroku==0.1.4
- idna==2.10
- itsdangerous==2.0.1
- Jinja2==3.0.3
- joblib==1.1.0
- MarkupSafe==2.0.1
- numpy==1.22.1
- requests==2.25.1
- scikit-learn==1.0.2
- scipy==1.7.3
- six==1.16.0
- threadpoolctl==3.0.0
- urllib3==1.26.6
- Werkzeug==2.0.2

To install the requirements.txt file in your environment:
1. cd to the directory where requirements.txt is located.
2. activate your virtualenv.
3. run the command "pip install -r requirements.txt".

To deploy the files into Heroku:
1. Create an account on  https://heroku.com/.
2. Create a new project on the console (IAM & admin).
3. Once the project gets created, select Deploy option.
4. Follow the instructions depending on the deployment method used: Heroku Got, GitHub or using the Heroku CLI

## Deployment
Project deployed on Heroku: https://university-admission-2022.herokuapp.com

## Project Status
Project is: _complete_ 


## Room for Improvement
The implementation of the detailed models has been done one by one. One can try to use lazypredict library to quickly compute and compare the performance of all regression models for our dataset (https://lazypredict.readthedocs.io/en/latest/)  

## Contact
Created by [Xavier Nuel Gavaldà](xaviernuelgav@gmail.com) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
