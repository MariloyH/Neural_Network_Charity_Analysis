# Neural Networks and Deep Learning Models

# Overview
 in this project we will help Alphabet Soup, a nonprofit organization that recauda fondos para organizaciones beneficas, to analyze which organizations are worth for donating, i.e., they were successful in the past.  We started from a CSV database with all the organizations that received funds  from Alphabet soup over the yaers. We will design a Deep Learning Neural Network Model using Python TensorFlow library.

 # Results
 ## Data Preprocessing 
 From the dataset, I considered the variable *IS_SUCCESSFULL* as the target for the purposed model, as well as  the variables *APPLICATION_TYPE*, *AFFILIATION*, *CLASSIFICATION*, *USE_CASE*, *ORGANIZATION*, *STATUS*,  *INCOME_ANT* and *ASK_MT*  as the features of the model. As suggested in Canvas. I considered  EIN, SPECIAL_CONSIDERATIONS as no significant columns for this purpose.

 # Compiling, Training and Evaluating the Model.
 For the first model, I selected:
  -  2 hidden layers with "relu" activation function for training because its simple a first approach, and a "sigmoid" as the second.  
  -  80 neurons in the first layer and 30 neurons in the second
  -  A "sigmoid" as a output activate function, due it our model has one binary output, "IS_SUCCESFUL".
 This model reached an accuracy of  **72.45%**, not bad, but not the 75% requested, and a lost of **56.49%**

 For increase the model performance, I made this changes:
  -  In the first intend, I droped 3 columns, EIN, NAME  and SPECIAL CONSIDERATIONS, I added a third layer with 10 neurons and but the accuracy downed to 69%.
  -  So, in the second intend:
     *  I reestablished the NAME column and I kept the other variables the same: 
     *  3 layers with 80, 30, and 10 neurons. 
     *  Layer 1 with relu and Layers 2 and 3 with sigmoid as activate function.  
 This model had an accuracy of **78.54 %** and a lost improvement of **44%**.
          

# Summary
Optimizing the model we exceeded the accuracy of 75%! So, this model  has an accuracy of 78.54%  to determine if an applicant orgaization will be successful!

 
