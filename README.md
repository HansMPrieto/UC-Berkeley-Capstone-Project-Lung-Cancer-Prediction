### Using Health Indicators to Predict Level of Lung Cancer

**Hans Prieto**

#### Executive summary

**Project overview and goals:** The goal of this project is to identify how accurately lung cancer can be predicted based on certain health indicators. Several classification models have been trained to predict the level of lung cancer for a patient. The classification models that were used in this project include Logistic Regression, KNN, Decision Trees, and SVC).

**Findings:** In terms of the results after training each of these models, although the KNN and Support Vector Machine models had a test accuracy of 100%, this wouldn't be ideal for a real life situation. Thus, there was some overfitting for the KNN and Support Vector Machine Models. The Logistic Regression Model had a testing accuracy of 91%, while the Decision Tree Model had a testing accuracy of 94%. In terms of Recall Score, the Decision Tree model had a recall score of 93.7%, while the Logistic Regression model had a recall score of 90.7%. The Decision Tree Model was our best model at predicting the level of lung cancer for a patient, as it had a higher testing accuracy and a higher recall score than the Logistic Regression Model.

#### Rationale
Accurately predicting lung cancer is important, as lung cancer is a leading cause of cancer-related deaths worldwide. Early detection is crucial for improving survival rates, and if we can develop accurate prediction models, we can help save lives by identifying at-risk individuals for a timely intervention.

#### Research Question
The question this project aims to answer is how accurately can lung cancer be predicted using certain health indicators? In order to answer this question, as mentioned before, several classification models were trained to predict the level of lung cancer.

#### Data Sources

**Dataset:** The dataset used in this project is sourced from Kaggle and can be accessed at: https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link

This dataset contains information on patients with lung cancer, along with several health indicators. Such health indicators that were included in this dataset were age, gender, air pollution exposure, alcohol use, dust allergy, occupational hazards, genetic risk, chronic lung disease, balanced diet, obesity, smoking, passive smoker, chest pain, coughing of blood, fatigue, weight loss, shortness of breath, wheezing, swallowing difficulty, clubbing of finger nails, and snoring.

1000 Patients were included in the dataset.

#### Methodology
GridSearchCV was implemented. Models were trained on the training set, and validated with the test set. GridSearchCV was used to fine tune each of the model's hyperparameters. Afterwards, the Accuracy Score, Precision Score, Recall Score, and F1 score were computed for each of the models.

#### Results
The KNN and Support Vector Machine models had a test accuracy of 100%, which indicates that there was some overfitting for these models. Thus, the Precision Score, the Recall Score, and the F1 Score for the KNN and Support Vector Machine models were 100%. The Logistic Regression Model had a testing accuracy of 91%, while the Decision Tree Model had a testing accuracy of 94%. In terms of Precision Score, the Decision Tree model had a Precision Score of 93.7%, while the Logistic Regression model had a Precision Score of 90.8%. In terms of Recall Score, the Decision Tree model had a Recall Score of 93.7%, while the Logistic Regression model had a Recall Score of 90.7%. In terms of F1 Score, the Decision Tree model had a F1 Score of 93.7%, while the Logistic Regression model had a F1 score of 90.5%. According to these results, the Decision Tree Model was our best model at predicting the level of lung cancer for a patient, as it had a higher testing accuracy and a higher recall score than the Logistic Regression Model.


#### Outline of project

- [Link to notebook 1](http://localhost:8888/notebooks/OneDrive/Documents/UC%20Berkeley%20AI%20and%20ML%20Bootcamp/Detecting%20Lung%20Cancer/Lung%20Cancer%20Detection.ipynb)


##### Contact and Further Information

Hans Prieto

Email: hansmiguelpprieto@gmail.com

[LinkedIn](https://www.linkedin.com/in/hans-prieto-b77124195/)
