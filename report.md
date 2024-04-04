### Overview: 
1. What variable(s) are the target(s) for your model?
The challenge outlined the is_successful column in the data as the target for the model. 
2. What variable(s) are the features for your model?
By dropping the is_successful column from the dataframe, all the other coulmns were used as features. 
3. What variable(s) should be removed from the input data because they are neither targets nor features?
The challenge outlined to drop the columns EIN and NAME
4. How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used two layers given the classification feature and the application feature to the model, I udes the values 10 and 4 for this. 
5. Were you able to achieve the target model performance?
The highest accuracy I was able to achieve with this model was 72.9 %, which is not optimal.
6. What steps did you take in your attempts to increase model performance?
I attempted to increase the number of bins that are used and decreasing the number of epochs both resulting in similar numbers. 