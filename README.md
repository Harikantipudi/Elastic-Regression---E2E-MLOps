#####################################################################
        MLOPS IMPLEMENTATION USING MLFLOW, DVC AND HEROKU
#####################################################################
This is an initial attempt to create an end to end MLOps pipeline leveraging 
the likes of OpenSource Tools  like  DVC, MLFLOW and Heroku

A)DVC is used for Data Versioning Control and establishing the overall Pipeline
B)MLFLOW is used for Model Registry and Experiment and Metrics Tracking 
C)Heroku is Paas that enables us to build,run and operate the application entirely on the cloud

End to End Integration has been done across various components Git,DVC,MLFlow and Heroku 
and there is seamless integration and automation across
#######################################################################


Prerequisite
######################################################################
A)Run and install requirements initially
B)pip install -r requirements.txt
C)Have a Heroku Login
D)Download the data from
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing



Running Experiments
######################################################################
To run and track experiments
 A) Data to be added to data_given folders
 B) Change parameters in params.yaml file
 C) Run MLPipe Line dvc repro
#######################################################################


Testing
######################################################################
To test the code,logic build and dependencies
 A) Add/Modify test cases test_config.py
 B) Run Pytest -V
######################################################################

Serving 
######################################################################
web App @ https://winequality-hk.herokuapp.com/
MLflow server @ 127.0.0.1.5000
######################################################################

Running ML Flow and Apps
######################################################################
A)Application : python app.py
B)MLFlow : mlflow server --default-artifact-root ./artifacts --backend-store-uri sqlite:///mlflow.sqlite 
######################################################################

Contributing
######################################################################
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
######################################################################


License
#######################################################################
MIT
#######################################################################