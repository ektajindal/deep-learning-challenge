# deep-learning-challenge
Module21 Challenge
1) What variable(s) are considered the target for your model? 

The Target for the model is the "Is-Successful" column; It signifies if the money was use effectively

2) What variable(s) are considered to be the features for your model? 

The Features of this Model are the Name, Application Type, Affiliation, Classification, Use_case, Organization, Income Amount, and Ask Amount

3) What variable(s) are neither and should be removed from the input data? 

EIN (Employer identificaiton) was dropped because the numbers could confuse the system into thinking its significant Special Considerations was dropped because there was only a small percentage of cases that had any special consideration, and special considerations cannot be quantified. Status was dropped because all rows were the same (1)

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

After testing multiple configurations, I achieved success with 3 Hidden layers; with various Neurons. After trying multiple configurations with only two hidden layers, adding a third layer using the sigmoid activation was able to achieve the desired result of over 75% accuracy

Were you able to achieve the target model performance?
In order to achieve the desired results, I had to manipluate the data in different ways. Added a third hidden layer, which ultimately allowed me to get past my 73% accuracy barrier.

What steps did you take in your attempts to increase model performance?
I added more neurons

 Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation
 A random forest can be used alongside this deep learning model in order to measure which features played the strongest role in determining the target variable