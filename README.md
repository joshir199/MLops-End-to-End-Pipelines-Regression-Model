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

Monitoring is very important aspects of ML lifecycle management. When dealing with data and models which is variable in nature, continuous monitoring system is a must.
Evidently AI provides very efficient monitoring farmework which can be included in ML pipeline. 

It will provide the monitoring in form of Comparing models, data shift, model shift, prediction shift and model performance all together in a ML production system.

Reports of the monitoring are generated and can be saved in various file formats and also in interactive UI for further analysis.

![](https://github.com/joshir199/MLops-Using-MLFlow-End-to-End-Pipelines-Regression-Model/blob/main/metrics%20comparison%20for%20different%20datas.png)

---------------> Model comaprison with data at different time intervals 

![](https://github.com/joshir199/MLops-Using-MLFlow-End-to-End-Pipelines-Regression-Model/blob/main/Data%20drift%20analysis.png)

---------------->  Data drift analysis based on features


For more details understanding and use cases, ![read here](https://docs.evidentlyai.com/user-guide/monitoring/monitoring_overview).


************************************************
# MLFlow Models 



