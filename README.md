# Neural Network Model Analysis Report

## Overview:
The purpose of this analysis is to develop a model that can predict the successfulness of applicants and their ventures if provided funding by Alphabet Soup (nonprofit foundation), by using data from thousands of organisations who have received funding by Alphabet Soup and if they were successful.

## Results:
- **What variable(s) are the target(s) for your model?** The target variable is the 'IS SUCCESSFUL' column which provides a binary value whereby 1 is the applicant was successful, and 0 represents not successful.
- **What variable(s) are the features for your model?** The feature variables can be shown in image below and include variables such as: application type, affiliation, classification, organisation and income.
<img width="1029" alt="image" src="https://github.com/rachj14/deep-learning-challenge/assets/151903302/917678eb-0563-411a-a2b5-062bae1def0b">

- **What variable(s) should be removed from the input data because they are neither targets nor features?** The variables that were removed were the EIN (applicant identifier number) and the Name of the organisation, as these are irrelevant in determining the successfulness of the organisation.
- **How many neurons, layers, and activation functions did you select for your neural network model, and why?** The original model contained two layers: first layer contained 8 neurons and the second layer contained 5 neurons. The activation functions used were relu and sigmoid. The optimisation model contained three layers: first layer contained 20 neurons, second layer contained 12 layers, and third layer contained 8 layers. The activation functions used were relu and sigmoid.
<img width="824" alt="image" src="https://github.com/rachj14/deep-learning-challenge/assets/151903302/fd236e7b-a553-4122-86c7-0e9c75cb8a62">
<img width="782" alt="image" src="https://github.com/rachj14/deep-learning-challenge/assets/151903302/f14461fe-a01f-46d5-88a1-d9ac6753e151">

- **Were you able to achieve the target model performance?** The final model performance accuracy was 73% so did not reach target of 75%. 
- **What steps did you take in your attempts to increase model performance?** The steps taken to attempt to increase model performance were:
  - Increase number of hidden layers from 2 to 3.
  - Increase number of neurons per layer.
  - Increase number of epochs from 20 to 100.

## Summary:
Overall, the the performance accuracy of the optimisation model stayed roughly the same from the original model despite implementing the optimisation methods. A different model could be used to solve the same problem, such as one that contains more hyperparameters and therefore the model can be tuned to improve performance. Another model could also be less prone to overfitting, and therefore also improve performance of the model to better predict the successfulness of organisations if provided with funding.
