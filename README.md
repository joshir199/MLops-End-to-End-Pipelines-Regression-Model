# MLops End-to-End Pipelines for Regression Model using MLFlow
Understanding ML-Ops and implementing end to end ML-Ops pipeline for real production environment.
ML-Ops is Machine Learning lifecycle management procedure. Managing end-to-end ML pipelines using ML flow and other ML tools makes the whole ML development and Serving process great.

These process includes :
1. Composability
2. Portability
3. Scalability

********************************************
# MLflow for Tracking and managing ML experiments :
It contains ML experiment MetaData(mlruns time, id, version etc), Artifacts(data, statistics, trained models, metrics etc) and more.

It uses MLFlowClient() to run experiments within context of mlflow and stores details of training with unique mlrun ID as shown in Image below:

![](https://github.com/joshir199/MLops-Using-MLFlow-End-to-End-Pipelines-Regression-Model/blob/main/ML-flow%20tracking/ML%20Flow%20runs/ml_runs%20continuous%20training%20using%20ml%20flow.png)


********************************************
# Evidently AI for Model validation, Data Validation and Model performance analysis while running experiments:

