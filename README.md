# Neural Network Charity Analysis

## Overview of the analysis
The purpose of this analysis was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
  - The column IS_SUCCESSFUL

- What variable(s) are considered to be the features for your model?
  - The columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.

- What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN and NAME

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - First hidden layer: 80 neurons
  - Second hidden layer: 30 neurons
  - Both layers have an activation function

- Were you able to achieve the target model performance?
  - No

- What steps did you take to try and increase model performance?
  - Changing activation type and adding hidden layers

## Summary
Although the target model perfomance was not reached, it could be reached if more data was available.
