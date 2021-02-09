
# 1st MLSecOps Project (C2)

##### 1st MLSecOps [Microsoft Azure Nanodegree ML Engineer] Operationalization Project (ND00333-AZMLND-C2)


## Project Overview

This is a Machine Learning 'operationalization' project [showcasing the know-how by determining deployments targets, enabling foresights, baselining performance metrics, scaning logs and benchmarking], as part of the ML Engineer for Microsoft Azure Nanodegree Program [ND00333-AZMLND-C2] from Udacit (in order to prepare for Microsoft [Designing and Implementing a Data Science Solution on Azure] Exam DP-100).


### The Problem Statement:
The business goal/objective was binary classification inferencing [for decision intel foresights] on product sales (predicting if the product (term deposit) could be subscribed to (or not), when a bank client is contacted?). [... more on the Bank [Direct] Marketing dataset whitepaper](https://core.ac.uk/download/pdf/55631291.pdf)


### The Solution:
Rather than the usual "VotingEnsemble", the best performing model was an Azure AutoML [MaxAbsScaler & LightGBM] algorithm having had scored a %95.09 AUC weighted (in contrast to the other run type which was a pipeline same algorithm's best model having scored a %94.5 AUC weighted); using such AutoML to train the best ML model before its OpenAPI endpoint gets deployed for production-ready consumption by the other ecosystem microservices (including azure automation and/or logic apps) for optimal 'Decision Intelligence MLSecOps' synergy.



## Architectural Diagram

Below is the formal diagram related to the visualization of the project's main steps (as listed in the next section):

![Project-key-steps](images/Project-key-steps.png?raw=true)


## Key Steps

Below are breif desribtions along with the required screenshots to demonstrate the completed project [overall end-to-end workflow's] critical stages and/or various main steps:


### MLSecOps Prepping & Authentication:



### Automating an ML Experiment:



### Deploying the Best Model:



### Logs Enabling:



### Documenting Swagger:



### Consuming Model Endpoints:



### Pipeline Creating and Publishing:



### Documentation [& Screencast Recording]:

Below screen recording's link is for the MLSecOps demo of the actionable [production ready] project:

- 1st MLSecOps Project (C2) Screencast Demo in 5 mins: https://vimeo.com/510089284

- 1st MLSecOps Project (C2) Screencast Demo in 10 mins: https://vimeo.com/510089644




## Areas of Improvement

Potential future improvements could be identified as:

- Retraining Hyperparameter Tuning with HyperDrive using Bayesian and/or 'Entire Grid' sampling, and AUC as the primary metric (rather than accuracy).
- Extending AutoML config to include more parameters.
- Documenting XAI and [operationalizing] model [explanation] as a web service, using the [interpretability package] to explain ML models & predictions.
- Exporting Models with ONNX to be deployed to a DLT connected Dapp device.
- Integrating App Insights with Sentinel and/or CASB.



## [Optional] Standout Suggestions

Pending standout suggestions that were attempted include:

- Completing the optional items about load-testing the endpoint.
- Using a [Parallel Run Step](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-use-parallel-run-step) in a pipeline. - Testing a [local container](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-package-models) with a downloaded model.
- Exporting the model for [supportting ONNX](https://docs.microsoft.com/en-us/azure/machine-learning/concept-onnx).


