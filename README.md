# Operationalizing Machine Learning in Azure ML Studio

## Overview

* This project is a part Machine Learning Engineer with Microsoft Azure Nanodegree program.

* In this project we implemented end-to-end machine learning project cycle in Azure ML studio. We used Azure ML to create and train the model with AutoML functionality and deploy it. 

* We also created a pipeline to create the model, deploy the model and consumed the model.

* Also the end-point URL of the deployed model is exposed to end-user which they can consume it with sample data.


## Architectural Diagram

* The dataset contains data about phone calls to the customer from a marketing campaigns organised by a bank. So the task to predict if the user will suscribe(1) or not(0).

* So this is a classification problem that we will be solving by Azure ML.

* First we will start the AutoML experiment by uploading the given dataset.

* Then the AutoML will choose best model with optimum parameters, then we will deploy the best model.

* We will enable logging through Application Insights service by updating the service.

* After deployment, we will download the swagger.json file in order to get information about end-points URL.

* Then we will comsume the end-point by http request with authentication key.

* Finally we will implement all these steps using Python SDK.

---

* Following is the architecture of the project :

![](images/arc.png)

---

## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screenshots required to demonstrate key steps. 

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
