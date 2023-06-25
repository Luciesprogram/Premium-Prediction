Insurance Premium Prediction Internship Project
The goal of this project to give people an estimate of how much they need based on their individual health situation. 
After that, customers can work with any health insurance carrier and its plans and perks whilwe keeping the projected 
cost from our study in mind. This can assist a person in concentrating on the health side of an insurance policy 
rather than the ineffective parts.
Table of contents
About project
Technologies
Software and account requirement
Setup
Project Pipeline
Technologies 💙
This project is created with below technologies/tools/resources:

    Flask Jupyter Notebook Visual Studio Code NumPy Pandas scikit-learn GitHub Actions

Python: 3.7
Machine Learning
Jupyter Notebook
HTML/CSS
Docker
Git
CI/CD Pipeline
Heroku/AWS/GCP
Software and account Requirement :-
Github Account
Heroku Account
VS Code IDE
GIT CLI
Setup
Create a conda environment

conda create -p venv python==3.7 -y
activate conda environment

conda activate venv/
To install requirement file

pip install -r requirements.txt
Add files to git git add . or git add <file_name>
To check the git status git status
To check all version maintained by git git log
To create version/commit all changes by git git commit -m "message"
To send version/changes to github git push origin main
Project Pipeline
Data Ingestion
Data Validation
Data Transformation
Model Training
Model Evaluation
Model Deployement
1. Data Ingestion:
Data ingestion is the process in which unstructured data is extracted from one or multiple sources and then prepared for
training machine learning models.
3. Data Validation:
Data validation is an integral part of ML pipeline. It is checking the quality of source data before training a new mode
It focuses on checking that the statistics of the new data are as expected (e.g. feature distribution, number of categories, etc).
4. Data Transformation
Data transformation is the process of converting raw data into a format or structure that would be more suitable for model building.
It is an imperative step in feature engineering that facilitates discovering insights.
5. Model Training
Model training in machine learning is the process in which a machine learning (ML) algorithm is fed with sufficient training data to learn from.
6. Model Evaluation
Model evaluation is the process of using different evaluation metrics to understand a machine learning model’s performance, as well as its strengths and weaknesses.
Model evaluation is important to assess the efficacy of a model during initial research phases, and it also plays a role in model monitoring.
7. Model Deployement
Deployment is the method by which we integrate a machine learning model into production environment to make practical business decisions based on data.
