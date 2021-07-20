# Neural_Network_Charity_Analysis

## Overview of the analysis

Th project purpose is  by using the knowledge from machine learning and neural networks I create a binary classifier that will tell the customer whether or not the applicants will be successful using alphabet soup. The dataset contains over 34,000 organizations that have been funded by alphabet soup. There are a number of columns that capture the metadata of each organization such as:

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

    . Deliverable 1: Preprocessing Data for a Neural Network Model
    
    . Deliverable 2: Compile, Train, and Evaluate the Model
    
    . Deliverable 3: Optimize the Model
    
    . Deliverable 4: A Written Report on the Neural Network Model (README.md)
    
  ## Resources
  
  . Data Source: charity_data.csv
  
  . Software: Python , Jupyter Notebook 
  
## Results

  ### Data Preprocessing
  
  ##### **.**** What variable(s) are considered the target(s) for your model?
   
   The variable that targeting in this module is the IS_SUCCESSFUL column.
   
  ##### . What variable(s) are considered to be the features for your model?
  
  In futures, all variable are consider expect the drop variables(the column application cat)
  
  ##### . What variable(s) are neither targets nor features, and should be removed from the input data?
  
  The variables, 'EIN' & 'NAME',have little to do with our outcome so that should be removed from the input data.
  
  
