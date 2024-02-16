# deep-learning-challenge

## Overview
#### This analysis is being conducted on behalf of the non-profit organization Alphabet Soup. This is to be used as a tool to find applicants with the best chance of being successful in their business ventures. By training this machine learning model with the metadata provided, we are better able to provide insight into which business types have been successful in the past in order to predict what new business models might have similar performance. 

## Results
- ### The target variable for this model:
![Alt text](target_var-1.png)

- ### The feature variables for this model:
![Alt text](features_var.png)

- #### The columns removed from the original dataset include 'EIN', 'NAME', "SPECIAL_CONSIDERATIONS", "STATUS", and "ASK_AMT" as these columns did not provide any value to the machine learning process.

- #### The machine learning model consists of 3 layers. In the first layer "relu" was used. In the second and third layer "sigmoid" was used. The model contained a total of 11,801 neurons. After implementing and testing multiple layers with different activation functions and different numbers of neurons it was found that this was the most effective layout. 

- #### The target performance of the model was 75%; however, after many iterations of adjusting and running the model, the highest achieved accuracy was 74%.

- #### Steps to increase the models performance included dropping feature columns, increasing the number of neurons, changing activation functions, and adding multiple layers. 

## Summary
#### This machine learning model is being trained to recognise succesful business models funded by Alphabet soup in order to predict the success of future business's. After many itterations the highest percentage of accuracy that was achieved was 74%. An alternative recommendation to achieve a higher accuracy score is Random Forest. This machine learning model uses decision trees and the bagging method. This combines the predictions from multiple machine learning algorithms to make more accurate predictions. Random Forest also is able to almost completely mitigate overfitting.


