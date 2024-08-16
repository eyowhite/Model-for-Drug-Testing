# Machine Learning Model for Drug Testing

## Table of Content
- [Project Overview](#project-overview)
- [Project Aim](#project-aim)
- [Project Methodology](#project-methodology)
- [Model Scores and Evaluation](#model-scores-and-evaluation)
- [Project Outcomes](#project-outcomes)


### Project Overview

Our client required a [predictive model](https://eyowhite.com/projects/) that accurately categorises individuals into drug groups based on specific input variables. 

### Project Aim
To create a fitting model that predicts the drug group of an individual taking the Age, Gender, BP, BMI as an entry point.

### Project Methodology
- Platform: Azure ML Studio.
- Machine Learning Problem: Multiclass Classification
- Fitting (training) Model adopted: Multiclass decision Forest.
- Dataset Used: Drugtest.csv

### Model Scores and Evaluation

Model score – On testing using 30% of the dataset, the model score indicates an almost even distribution of the target variable, Drug Group as shown:

<img width="199" alt="Model Evaluation" src="https://github.com/eyowhite/Model-for-Drug-Testing/assets/151957176/917ea8f0-2d2f-48c6-9410-39167d9a316b">

![Confusion Matrix](https://github.com/eyowhite/Model-for-Drug-Testing/assets/151957176/44abfc5a-49ef-428d-9346-de3dd01baee4)

<img width="197" alt="ML Metrics" src="https://github.com/eyowhite/Model-for-Drug-Testing/assets/151957176/be057209-b84b-4aa4-902a-8794e5e7b309">

### Project Outcomes
Accurate prediction of drug groups indicated by high accuracy, precision, F1 and recall scores demonstrating the effectiveness of the model.




