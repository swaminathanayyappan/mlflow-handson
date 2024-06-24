# mlflow-handson
This repository contains of the hands on practice code that gives an idea about mlflow

## Mlflow server startup in command line
![Mlflow server startup](image.png)

## Mlflow Ui
![Mlflow Ui](image-1.png)

## Packaging the experiment as mlflow conda env package
Ensure whether the MLProject is created before running the below command, along with this the conda.yaml file should be created in the root directory
![mlflow project packaging](image-3.png)


This command will creates a conda environment and installs all the dependencies with the required packages that is specified on the conda.yaml file. Also one important thing is specify the mlflow.remote_uri on the train.py code and make sure the mlflow server is running before doing the build

Once every criteria is met, the build will be succeded and it will show a message like this

![Sucess mlflow build message](image-4.png)