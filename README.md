# Neural Networks and Deep Learning Models

# Overview
In this project we will help Alphabet Soup, a nonprofit organization that raise funds for charities to analyze which organizations are worth for donating, review their history and which of them were successful in the past.  We started from a CSV database with all the organizations that received funds  from Alphabet soup over the years and we will develop a Deep Learning Neural Network Model using Python TensorFlow library.

 # Results
 ## Data Preprocessing 
 
 <img width="660" alt="Organizations Data" src="https://user-images.githubusercontent.com/102195803/188954038-e50a762a-bac0-4fcd-aa0b-2d2c711e1e25.png">

 
 From the dataset, I considered the variable *IS_SUCCESSFULL* as the target for the purposed model, as well as  the variables *APPLICATION_TYPE*, *AFFILIATION*, *CLASSIFICATION*, *USE_CASE*, *ORGANIZATION*, *STATUS*,  *INCOME_ANT* and *ASK_MT*  as the features of the model. As suggested in Canvas. I considered  EIN, SPECIAL_CONSIDERATIONS as no significant columns for this purpose.
 
 <img width="450" alt=" nnnnn" src="https://user-images.githubusercontent.com/102195803/188954164-7dd40da9-f65c-4082-bd66-d54db650fc34.png">


 # Compiling, Training and Evaluating the Model.
 
 <img width="660" alt="Compiling Model" src="https://user-images.githubusercontent.com/102195803/188954272-fd2528cd-16e5-4ef1-a8fa-47c613745934.png">

 For the first model, I selected:
  -  2 hidden layers with "relu" activation function for training because its simple a first approach, and a "sigmoid" as the second.  
  -  80 neurons in the first layer and 30 neurons in the second
  -  A "sigmoid" as a output activate function, due it our model has one binary output, "IS_SUCCESFUL".
 This model reached an accuracy of  **72.45%**, not bad, but not the 75% requested, and a lost of **56.49%**
 
 
<img width="550" alt="C" src="https://user-images.githubusercontent.com/102195803/188955801-87d5679f-20d5-4114-ac66-56fa8d1915e6.png">

 

 For increase the model performance, I made this changes:
  -  In the first intend, I droped 3 columns, EIN, NAME  and SPECIAL CONSIDERATIONS, I added a third layer with 10 neurons and but the accuracy downed to 69%.
  -  So, in the second intend:
     *  I reestablished the NAME column and I kept the other variables the same: 
     *  3 layers with 80, 30, and 10 neurons. 
     *  Layer 1 with relu and Layers 2 and 3 with sigmoid as activate function.  
     
 This model had an accuracy of **78.54 %** and a lost improvement of **44%**.
 
 <img width="660" alt="Optimazed Model" src="https://user-images.githubusercontent.com/102195803/188955119-f9259613-c9a3-45a3-8f07-77005ab71e96.png">

 <img width="550" alt="OM Performance" src="https://user-images.githubusercontent.com/102195803/188955688-265b9fca-07d9-41b1-a287-a5e0966999ee.png">

 

# Summary
Optimizing the model we exceeded the accuracy of 75%! So, this model  has an accuracy of 78.54%  to determine if an applicant orgaization will be successful!

 
