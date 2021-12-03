# Neural_Network_Charity_Analysis

## Overview
The purpose of this project is to practice using neural networks to predict whether applicants will be successful if funded by Alphabet Soup using a binary clssifier.

## Results
Data Preprocessing

- What variable(s) are considered the target(s) for your model?
  The target for the model is the IS_SUCCESSFUL column
 
 - What variable(s) are considered to be the features for your model?
  The features for the model are the following columns; APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.

- What variable(s) are neither targets nor features, and should be removed from the input data?
  We removed the EIN and Name column as they were not useful.
  
 Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  For the highest accuracy I reached I used three hidden layers. The first hidden layer had 100 neurons, the second had 40 neurons and the third had 10 neurons.

- Were you able to achieve the target model performance?

![image](https://user-images.githubusercontent.com/85451089/144552936-84231e97-889d-415e-841e-825dca3c5ffd.png)

  The highest accuracy score I was able to receive was .7287.

- What steps did you take to try and increase model performance?
  I attempted to move the neurons around three times. When I received the best results was when adding a third hidden layer and changing the activation to sigmoid rather than relu.
  ![image](https://user-images.githubusercontent.com/85451089/144552850-8960205c-b12d-4ef1-ae1f-e80e4f00fba9.png)
