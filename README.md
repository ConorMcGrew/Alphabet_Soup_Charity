# Alphabet_Soup_Charity

## Overview of the analysis: 
Using the Keras Machine Learning Model, we are attempting to determine the outcome of applicants based on whether they were funded by Alphabet Soup.

## Results: 

Data Preprocessing

<img width="543" alt="Screen Shot 2021-07-25 at 11 22 02 PM" src="https://user-images.githubusercontent.com/80495710/126928842-3a8ad647-102c-43a9-bc8a-05200f74103e.png">

What variable(s) are considered the target(s) for your model?

- The target variable is the IS_SUCCESSFUL column (success or failure indicated by 0 or 1)

What variable(s) are considered to be the features for your model?

- APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are all features, because they could potentially influcence the outcome. 

<img width="465" alt="Screen Shot 2021-07-25 at 11 22 17 PM" src="https://user-images.githubusercontent.com/80495710/126928857-83169892-b18f-414a-92c2-62af49a7a5cc.png">

What variable(s) are neither targets nor features, and should be removed from the input data?
-The EIN and NAME columns have no obvious effect on the outcome and are mostly just identifiers, so they were dropped. 

Compiling, Training, and Evaluating the Model

<img width="542" alt="Screen Shot 2021-07-25 at 11 30 33 PM" src="https://user-images.githubusercontent.com/80495710/126929370-daf6b1a2-5915-4510-b8ba-33e878d3c27a.png">

How many neurons, layers, and activation functions did you select for your neural network model, and why?
-

<img width="552" alt="Screen Shot 2021-07-25 at 11 35 39 PM" src="https://user-images.githubusercontent.com/80495710/126929730-e8db2f46-6b7a-437b-b3b5-4b6e34315fb0.png">
<img width="558" alt="Screen Shot 2021-07-25 at 11 35 49 PM" src="https://user-images.githubusercontent.com/80495710/126929732-398540fa-1bd2-4829-a16f-652ef2de3a33.png">

Were you able to achieve the target model performance?
-

What steps did you take to try and increase model performance?
-The sigmoid function seemed the most effective function for improving model performance, because the data we were looking for as our target was a binary classifier. 

## Summary: 

Overall, the most effective model was only 72.70% accurate. 
