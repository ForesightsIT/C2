
# 1st MLSecOps Project (C2)

##### 1st MLSecOps [Microsoft Azure Nanodegree ML Engineer] Operationalization Project (ND00333-AZMLND-C2)


## Project Overview

This is a Machine Learning 'operationalization' project, part of the ML Engineer for Microsoft Azure Nanodegree Program [ND00333-AZMLND-C2] from Udacit (in order to prepare for Microsoft [Designing and Implementing a Data Science Solution on Azure] Exam DP-100).

Though showcasing the know-how by determining deployments targets, enabling foresights, baselining performance metrics, scaning logs and benchmarking; the business goal was inferencing foresights for a binary classification of the Bank [Direct] Marketing dataset [predicting if the product (term deposit) would be (or not) subscribed]; by using Azure AutoML to train an ML model before its best model's OpenAPI endpoint gets deployed for production-ready consumption by the other ecosystem microservices (including azure automation and/or logic apps) for optimal 'Decision Intelligence MLSecOps' synergy.


## Architectural Diagram

Below is a formal visualization of the key steps [end-to-end workflow] diagram:

![Project-key-steps](images/Project-key-steps.png?raw=true)

*TODO*: Provide an architectual diagram of the project and give an introduction of each step. An architectural diagram is an image that helps visualize the flow of operations from start to finish. In this case, it has to be related to the completed project, with its various stages that are critical to the overall flow. For example, one stage for managing models could be "using Automated ML to determine the best model". 

## Areas of Improvement

Potential future improvements could be identified as:

Retraining Hyperparameter Tuning with HyperDrive using Bayesian and/or 'Entire Grid' sampling, and AUC as the primary metric (rather than accuracy).

Extending AutoML config to include more parameters.

Documenting XAI and [operationalizing] model [explanation] as a web service, using the [interpretability package] to explain ML models & predictions.

Exporting Models with ONNX to be deployed to a DLT connected Dapp device.

Integrating App Insights with Sentinel and/or CASB.


## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps. 


## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:


## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
