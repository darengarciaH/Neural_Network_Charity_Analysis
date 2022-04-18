# Neural_Network_Charity_Analysis
## Overview
The purpose of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
## Results
### Data Preprocessing
The IS_SUCCESSFUL variable is the target for the model. The features for the model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS,INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT. EIN and NAME variables are neither targets or features.
### Compiling, Training, and Evaluating the Model
I added three hidden layers with eight, four, and two neurons respectively for the first attempt. For the second attempt, I added four hidden layers with 130, 40, 20, and 10 neurons. For my third attempt, I added three hidden layers with 80, 30, and 10 neurons. I was not able to reach the 75% target performance.
## Summary
The best optimized model had a 61% accuracy and a loss of 67%. Perhaps using the percentage of the INC_AMT relative to the ASK_AMT and using that ratio in the model may have been an important feature which could help boost the accuracy of this model.
