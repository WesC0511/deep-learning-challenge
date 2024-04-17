# deep-learning-challenge
hw 21 deep-learning-challenge
Overview of the analysis: 
Explain the purpose of this analysis.
The purpose of this analysis is to develop a deep learning model to predict the success of charitable donations for Alphabet Soup, 
analyzing historical data on charitable organizations, create a model that can accurately classify whether a donation will be successful based on various input features.


Results: 
Using bulleted lists and images to support your answers, address the following questions:


Data Preprocessing
What variable(s) are the target(s) for your model?
-- Target Variable: The target variable for our model is IS_SUCCESSFUL, which indicates whether a charitable donation was successful (1) or not (0).
What variable(s) are the features for your model?
-- Feature Variables: The feature variables for our model include various input features such as APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, etc.
What variable(s) should be removed from the input data because they are neither targets nor features?
Removed Variable: Variables such as EIN and NAME are neither targets nor features and should be removed from the input data.


Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Selected a neural network model with two hidden layers. 
The first hidden layer has 128 neurons with ReLU activation, followed by a dropout layer to prevent overfitting. 
The second hidden layer has 64 neurons with ReLU activation and another dropout layer. The output layer has a single neuron with a sigmoid activation function.

Were you able to achieve the target model performance?
The model achieved an accuracy of approximately 73%, which was an increase from the original 50%


What steps did you take in your attempts to increase model performance?
Attempted to increase model performance by increasing model complexity, 
using dropout regularization, 
optimizing the learning rate, 
implementing early stopping, 
and experimenting with different hyperparameters. However, these efforts were not sufficient to achieve the target accuracy.


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
The deep learning model developed in this analysis shows promising results but falls short to expectation. 
To address this classification problem more effectively, 
a different model such as a gradient boosting classifier could be considered. 
Gradient boosting algorithms like XGBoost or LightGBM are known for their effectiveness in handling tabular data and often outperform deep learning models in such scenarios. 
Additionally, ensemble methods like random forests or stacking could be explored to combine the strengths of multiple models and improve overall performance.
These approaches may offer better interpretability and performance for this classification problem compared to deep learning models.




