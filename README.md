# deep-learning-challenge

## Overview of the Analysis
The purpose of this analysis is to develop a Neural Network Model for Alphabet Soup, a nonprofit organization that funds various ventures. The aim is to build a model that predicts whether the applicants will be successful after being funded by Alphabet Soup. With the funding data containing thousands of organizations provided by Alphabet Soup, the model will use various features to determine the chances of ventures succeeding. This predictive model will help Alphabet Soup make informed decisions about appropriating resources under different impacts.

## Result
- #### Data Preprocessing
  - **Tartget:** The target for the model is `IS_SUCCESSFUL`, which indicates whether the funding was used effectivly
  - **Features:** The features for the model include  `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `STATUS`,  `INCOME_AMT`,`SPECIAL_CONSIDERATIONS`, and `ASK_AMT`.
  - The identification columns `EIN` and `NAME` were because they neither represent targets nor features.

- #### Compiling, Training, and Evaluating the Model
  - During the model development process, I experimented with different configurations for the hidden layers, varying the number of neurons and layers to find an optimal setup. I ultimately chose a  configuration consisting of five hidden layers with a combination of activation functions. While the aim was to achieve a high level of accuracy, the model's performance fell short of the target. The maximum accuracy during the training process was 74%, while the desired level of accuracy was 75%. I explored various strategies to improve the model performance, including the combination of infrequent values and adjustments to the number of epochs. However, these attempts did not yield the desired results.

## Summary
In summary, the deep learning model built for Alphabet Soup aims to predict the success of applicants funded by the organization. While the goal was to optimize the model's development and performance, I was unable to achieve the desired level of accuracy. As a recommendation for future analysis, alternative models such as gradient boosting or random forest classifiers could be beneficial. These models are effective for predicting binary classification problems and may improve the accuracy of the task.
