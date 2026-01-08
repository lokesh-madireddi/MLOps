Machine Learning ops
----------------------------------

1. Machine Learning is a process of training a computer or machine with huge amount of data so that it identify the patten and predict the output. 
2. Data scientist identifies an algorithm and trains it with data set. 
3. During the training it will identify the pattern and it start developing mathematical function which we called as model.
4. Model (mathematical function) is a output of a machine learning process.

Steps How Data scientist create a Model: 
1. Start with a data set.
2. split (80%, 20% concept) --> 80% is used to train the algorithm and 20% to test the model. 
3. Algorithm --> (Logistic regression, Decission tree, random forest, K nearest Neighbour)
4. Train the model.  Now it will develop a mathematical function by it self and create a model.
5. Testing - 
6. Retraining if the result is not accurate.
7. Save it in .pkl, .joblib, .onnx format.
8. API creation --> ML engg will package the model into software applications to deploy. 

Machine Learning Life Cycle. 
---
1. Problem defenition --> understand a problem as detail as possible.
2. Data collection --> gather info from various platforms
3. Cleaning of data --> remove duplicates, wrong fields
4. Feature Engineering --> DS add new features to the existing data sets if they feel that will help to create a good model.
5. Model Selection --> Algorithm selection.
6. Model Training (80%)--> Algorithm will develop a mathematical function - model.
7. Model Evaluation (20%)-->
8. HyperParameter -->
9. Deploying
10. Model Monitoring/maintenance -->

In the above life cycle, 
Data Scientists --> till Model evaluation Data Scientist will take care 
Machine Learning Engineers --> rest will be taken care by machine learning engineers by making it production deploy ready. 
MLOps Engineers --> Identify the gaps between all the steps and fix those.

Daily activities of MLOps Engg 
1. Build Reprodusable Training pipelines (CT Pipelines)
2. Automating CD to deploy models to Prod
3. Observability
4. Configure Model Registry to save the models
5. Setting up Infra (IAC - Terraform)
6. Setting up K8s, GPO, also for cost optimization.
