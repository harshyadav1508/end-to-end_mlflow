## What is MLFlow ?

MLflow is an open source platform for managing the end-to-end machine learning lifecycle. 

## Why do we need MLFlow ?
Helps in comparing metrics of different model, allow running our model remotely & provide easy sharing of ml code to others.


## Main Functions of MLFlow

- **Mlflow Tracking:** Record and Compare different parameters and results(metric like accuracy, AUC,F1 score etc)

-  **Mlflow Projects:** Packaging ML code in a reusable form so that other data scientists can easily reuse the model, or we can run the model remotely. It require two extra files named *MLproject* & *conda.yaml*
    
- **MLflow Models:** Provide a standard format for packaging machine learning models that can be used in a variety of downstream tools — for example, real-time serving through a REST API. For deploying a model we need *MLmodel* file & .pkl file of model, which is built by mlflow itself
    
- **MLflow Model Registry:** Providing a central store to manage the full lifecycle of an MLflow Model, including model lineage, model versioning, stage transitions etc.


