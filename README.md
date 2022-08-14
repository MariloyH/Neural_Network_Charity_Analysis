# Neural Networks and Deep Learning Models

# Overview
 in this project we will help Alphabet Soup, a nonprofit organization that recauda fondos para organizaciones beneficas, to analyze which organizations are worth for donating, i.e., they were successful in the past.  We started from a CSV database with all the organizations that received funds  from Alphabet soup over the yaers. We will design a Deep Learning Neural Network Model using Python TensorFlow library.

 # Results
 From the dataset, I considered the variable *IS_SUCCESSFULL* as the target for the purposed model, as well as  the variables *APPLICATION_TYPE*, *AFFILIATION*, *CLASSIFICATION*, *USE_CASE*, *ORGANIZATION*, *STATUS*,  *INCOME_ANT* and *ASK_MT*  as the features of the model. As suggested in Canvas, we dropped the EIN and NAME columns, even there were another no significant columns.

 # Compiling, Training and Evaluating the Model.
 For the first Neural Network Model, I selected 2 hidden layers with "relu" activation function for training because its because it is the , first one with 80 neurons and the sencond one with 30 neurons. I chose as the activated layer function a "sigmoid", due it our model has one binary output, "IS_SUCCESFUL".

 This model reached an accuracy of  72.42%, not bad, but not the 75% requested, and a lost of 58.45%

 For optimizing the model 









