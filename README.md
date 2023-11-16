# Deep-Learning

#Overview

The purpose of this analysis was to predict whether applicants will be succesful if funded by Alphabet Soup.

Data Preprocessing:
  -What variable(s) are the target(s) for your model?
  APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS
  -What variable(s) are the features for your model?
  AFFILIATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS
  -What variable(s) should be removed from the input data because they are neither targets nor features?
  APPLICATION_TYPE, CLASSIFICATION

  Compiling, Training, and Evaluating the Model
  -How many neurons, layers, and activation functions did you select for your neural network model, and why?
  2 layers, 2 activationfunctions, 5 units
  -Were you able to achieve the target model performance?
  No, was not able to achieve 75%
  -What steps did you take in your attempts to increase model performance?
  Producing larger number of epochs

  #Summary
  Overall accuracy was about 72%, the potential of more layers and units could have resulted in higher level of accuracy.
