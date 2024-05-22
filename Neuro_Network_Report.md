## Overview
This project helps the nonprofit foundation Alphabet Soup to select the best applicants for funding with a high chance of success rate by using a binary classifier. This project utilizes and employ diverse machine learning methods to train and assess the model's performance. By doing so, the objective is to optimize the model in order to attain an accuracy surpassing 75%. 

## Results
### Data Preprocessing 
What variable(s) are the target(s) for your model?
- The target variable of the model is the `IS_SUCCESSFUL` column in the dataset. 

What variable(s) are the features for your model?
- The variables for the features of the model are every column excluding the `IS_SUCCESSFUL` column. 

What variable(s) should be removed from the input data because they are neither targets nor features?
- The columns that should be removed because they are neither the target or features are `EIN` and `names`. 

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I selected 3 layers for my initial model: first layer with an input of 80 neurons, a second layer with 30 neurons, and an output layer with 1 neuron. I selected this model because the total number of neurons would be between 2-3 times the number of input feactures. For the activation function, I used `relu` for the first and second layers, while `sigmoid` was used for the output layer since we are acheiving binary classification.

Were you able to achieve the target model performance?
- Unfortnately, I was not able to achieve 75% but rather close with 72%. 

What steps did you take in your attempts to increase model performance?
- I switched up the activation functions and decreased the amount of neurons. 

## Summary 
Although I was not able to attain the target accuracy of 75%, the deep learning model was 73% accurate. With given additional time, I would incorporate hyperparameter tuning or random forest classifier. In addition, by adding more layers or using different activation functions, the model could reach 75% accuracy. 