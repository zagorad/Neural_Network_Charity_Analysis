# Neural_Network_Charity_Analysis

## Purpose
The purpose of the project was to use machine learning to create a neural network to determine if applicants applying for the Alphabet Soup funding will be successful. 

# Results 

## Data Preprocessing

 **What variable(s) are considered the target(s) for your model?**
 
•	The “IS_SUCCESSFUL” variable was the chosen target for the model

**What variable(s) are considered to be the features for your model?**

•	The features of the model were: "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT".

**What variable(s) are neither targets nor features, and should be removed from the input data?**

•	The “EIN” and the “NAME” variables were removed from the input data.

## Compiling, Training, and Evaluating the Model

**How many neurons, layers, and activation functions did you select for your neural network model, and why?**

•	The first hidden layer contained 80 neurons, the second hidden layer contained 30 neurons, both layers were using “relu” as activation and the hidden layers were using “sigmoid” as activation.

![Original_Model](https://user-images.githubusercontent.com/118132063/231339721-2e00a35e-1515-4733-a85e-75e93518250d.png)

**Were you able to achieve the target model performance?**

•	I could not reach the target performance of 75% for either of the models. The original model had a 73% accuracy and the optimized had 72.8% accuracy.

![Original_Model_Test_Data](https://user-images.githubusercontent.com/118132063/231340076-c9f6c358-d04a-45c3-aa3a-af0dbd308812.png)

![Optimization_Model_Test_Data](https://user-images.githubusercontent.com/118132063/231340693-997b0098-5ea7-4651-aff9-293f747d8b46.png)

**What steps did you take to try and increase model performance?**

![Optimization_Model](https://user-images.githubusercontent.com/118132063/231341012-13e4fa69-d612-42ff-89b6-e8724adcbe73.png)

## Summary
Overall, even with the optimization I still couldn’t reach a 75% accuracy rate, the highest accuracy rate I got was 73%.  I would recommend using the Random Forest Classifier model to potentially receive similar but faster results with less code to perform.


