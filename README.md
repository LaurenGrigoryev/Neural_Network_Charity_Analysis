# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of this analysis was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results: 

### Data Preprocessing

* What variable(s) are considered the target(s) for your model?
The target of my model is variable IS_SUCCESSFUL [as pictured here](https://github.com/LaurenSonis/Neural_Network_Charity_Analysis/blob/main/2021-04-18%20(3).png).

* What variable(s) are considered to be the features for your model?
The features of my model are variables APPLICATION_TYPE, AFFILIATION,	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	ASK_AMT,	IS_SUCCESSFUL [as pictured here]().

* What variable(s) are neither targets nor features, and should be removed from the input data?
The variables that are neither targets nor features are EIN, NAME, and SPECIAL_CONSIDERATIONS [as pictured here](https://github.com/LaurenSonis/Neural_Network_Charity_Analysis/blob/main/2021-04-18%20(4).png). 

### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
I selected 8 neurons per layer, three hidden layers, and the relu functions to try to create a more accurate model. Mostly, I thought the addd layers and nuerons would help increase the accuracy.

* Were you able to achieve the target model performance?
No, [as seen here](https://github.com/LaurenSonis/Neural_Network_Charity_Analysis/blob/main/2021-04-18%20(6).png), but I made three attempts.

* What steps did you take to try and increase model performance?
I removed noisy variables from features, added neurons to hidden layers, added hidden layers, and changed the activation function of output layers is changed for optimization [as pictured here](https://github.com/LaurenSonis/Neural_Network_Charity_Analysis/blob/main/2021-04-18%20(5).png).

