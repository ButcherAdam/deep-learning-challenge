# deep-learning-challenge
Module 22 Challenge for UT Austin Data Visualization Bootcamp involving Deep Learning on data about funds from Alphabet Soup business.

<h3>Data Preprocessing</h3>

<b>What variable(s) are the target(s) for your model?</b>

IS_SUCCESSFUL

<b>What variable(s) are the features for your model?</b>

APPLICATION_TYPE,
AFFILIATION,
CLASSIFICATION,
USE_CASE,
ORGANIZATION,
STATUS,
INCOME_AMT,
SPECIAL_CONSIDERATIONS,
ASK_AMT

<b>What variable(s) should be removed from the input data because they are neither targets nor features?</b>

EIN,
NAME

<h3>Compiling, Training, and Evaluating the Model</h3>

<b>How many neurons, layers, and activation functions did you select for your neural network model, and why?</b>

Initially, the ReLU model was used for the Hidden Layers and the Sigmoid was used for the Output Layer. There were 80 features and 30 features for the 2 respective hidden layers. They were chosen as the sample code had that as the output.

<b>Were you able to achieve the target model performance?</b>

The model's target performance couldn't go to at least 75%.

<b>What steps did you take in your attempts to increase model performance?</b>

The steps that were taken were to drop the ask amount column since the values vary along with focusing on 4 top application counts before going to other to reduce outliers. Also, the hidden layers were ELU, Tanh, and SELU for the activation functions.
