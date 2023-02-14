# Kaggle-Stay-Alert-Dataset
Machine Learning Project on one of the Kaggle Challenges - Stay Alert the ford challenge

Link to the Data used:-

https://www.kaggle.com/competitions/stayalert/data


Dataset Description :-

The data for this project shows the results of a number of "trials", each one representing about 2 minutes of sequential data that are recorded every 100 ms during a driving session on the road or in a driving simulator.
The trials are samples from some 100 drivers of both genders, and of different ages and ethnic backgrounds. The files are structured as follows:
         
The first column is the Trial ID - each period of around 2 minutes of sequential data has a unique trial ID.
For instance, the first 1210 observations represent sequential observations every 100ms,and therefore all have the same trial ID.
       
The second column is the observation number - this is a sequentially increasing number within one trial ID  
The third column has a value X for each row where

         X = 1     if the driver is alert  
         X = 0     if the driver is not alert   
        The next 8 columns with headers P1, P2 , …….., P8 represent physiological data;  
        The next 11 columns with headers E1, E2, …….., E11 represent environmental data;  
        The next 11 columns with headers V1, V2, …….., V11 represent vehicular data; 

 

Problem Statement:-


QUESTION : Driving while distracted, fatigued or drowsy may lead to accidents.Activities that divert the driver's attention from the road ahead,
such as engaging in a conversation with other passengers in the car, making or receiving phone calls sending or receiving text messages,
eating while driving or events outside the car may cause driver distraction. Fatigue and drowsiness can result from driving long hours or from lack of sleep.    
        
The objective of this challenge is to design a detector/classifier that will detect whether the driver is alert or not alert employing any combination of vehicular,
environmental and driver physiological data that are acquired while driving.


In this project we performed the following steps :-  

* Reading in the real world Data.  
* Impoerting the required libraries for basic EDA.  
* Checking for the null values.  
* Performing appropriate feature selection techniques.  
* Splitting the data into training and validation.  
* Building and evaluating different models on the data.  
* Tuning the huper parameters of the model to improve the accuracy of the predictions.  
* Performed Dimensionality reduction techniques to reduce the complexity of the model.  
* Making predictions on the unseen data using the best model that we built. 
