# E2E MLOPS Implementation Using MLFLOW, DVC and Heroku


 This is an initial attempt to create an end to end MLOps pipeline leveraging the likes of OpenSource Tools  like DVC, MLFLOW and Heroku

A) DVC is used for Data Versioning Control and establishing the overall Pipeline 

B) MLFLOW is used for Model Registry and Experiment and Metrics Tracking 
   
C) Heroku is Paas that enables us to build,run and operate the application entirely on the cloud

   End to End Integration has been done across various components Git,DVC,MLFlow and Heroku and there is seamless integration and automation across

---

### Table of Contents


- [Prerequisites](#Prerequisites)
- [Experiments](#Experiments)
- [Applications](#Applications)
- [Testing](#Testing)
- [Serving](#Serving)

---

## Prerequisites

A) Run and install requirements initially 

B) pip install -r requirements.txt 

C) Have a Heroku Login
D) Download the data from https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

## Experiments

To run and track experiments 

A) Data to be added to data_given folders 

B) Change parameters in params.yaml file 

C) Run MLPipe Line dvc repro


## Applications

A) Application : python app.py 

B) MLFlow : mlflow server --default-artifact-root ./artifacts --backend-store-uri sqlite:///mlflow.sqlite


## Testing 
To test the code,logic build and dependencies 

A) Add/Modify test cases test_config.py 

B) Run Pytest -V


## Serving

A) Web App @ https://winequality-hk.herokuapp.com/

B) MLflow server @ 127.0.0.1.5000

[Back To The Top](#read-me-template)
