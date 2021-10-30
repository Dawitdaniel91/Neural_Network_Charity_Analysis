# Neural_Network_Charity_Analysis

## Overview of the analysis

The project’s purpose is by using the knowledge from machine learning and neural networks I create a binary classifier that will tell the customer whether or not the applicants will be successful using alphabet soup. The dataset contains over 34,000 organizations that have been funded by alphabet soup. There are a number of columns that capture the metadata of each organization such as:

              EIN and NAME—Identification columns
              
              APPLICATION_TYPE—Alphabet Soup application type
              
              AFFILIATION—Affiliated sector of industry
              
              CLASSIFICATION—Government organization classification
              
              USE_CASE—Use case for funding
              
              ORGANIZATION—Organization type
              
              STATUS—Active status
              
              INCOME_AMT—Income classification
              
              SPECIAL_CONSIDERATIONS—Special consideration for application
              
              ASK_AMT—Funding amount requested
              
              IS_SUCCESSFUL—Was the money used effectively. 


#### The outline of the project

    . Preprocessing Data for a Neural Network Model
    
    . Compile, Train, and Evaluate the Model
    
    . Optimize the Model
    
    . A Written Report on the Neural Network Model (README.md)
    
  ## Resources
  
  . Data Source: charity_data.csv, AlphabetSoupCharity_starter_code.ipynb
  
  . Software: Python , Jupyter Notebook 
  
## Results

  ### Data Preprocessing
  
 ###### What variable(s) are considered the target(s) for your model?
   
   . The variable that targeting in this module is the IS_SUCCESSFUL column.
   
   ![image](https://user-images.githubusercontent.com/80365882/126390460-cdb2dd74-4177-4fe9-ba10-f4bbed81ed70.png)

   
 ###### What variable(s) are considered to be the features for your model?
  
   . In futures, all variable are consider expect the drop variables
     
 ####### What variable(s) are neither targets nor features, and should be removed from the input data?
  
  . The variables, 'EIN' & 'NAME',have little to do with our outcome so that should be removed from the input data.
  
  ![image](https://user-images.githubusercontent.com/80365882/126390600-c6a17894-96ac-40d8-bca6-c46f3fff17be.png)
  
    
  ### Compiling, Training, and Evaluating the Model
  
  ###### How many neurons, layers, and activation functions did you select for your neural network model, and why?
  The model has input and two hidden layers. The first and second hidden layer has 80 and 30 neurons respectively. Both layers have an activation function "relu" & the output layer is "sigmoid".
  
  ![image](https://user-images.githubusercontent.com/80365882/126390703-41c7db72-5c9f-426d-ac78-90d9f3b82f84.png)

  ###### Were you able to achieve the target model performance?
  
  Not active the target model performance because the model accuracy is under 75%. This is not a satisfying performance to help predict the outcome of the charity donations.
  
  ![image](https://user-images.githubusercontent.com/80365882/126390876-e539b8e7-165a-4e2a-aae7-9f033e1d5f36.png)
  
  ###### What steps did you take to try and increase model performance?
  
  THe following steps did taken but not improve the modele peformance beyond 75%
  
    . increased the number of neurons on one of the hidden layers, 
    
    . used a model with three hidden layers.
    
    . tried a different activation function (tanh) 
  
  ## Summary
  
 The model’s accuracy is 72.9% the result is not enough for the prediction of the feature even though I tried changing the hidden layers and dropping two features that were figured to be irrelevant. So that to get the better accuracy performance in the model, I recommend having more data or dropping more additional variables If the variable does not have significant effects on the output.
  
