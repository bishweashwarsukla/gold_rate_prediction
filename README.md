# Gold_Rate_prediction
## **Applying regression algorithm to predict the Gold Rate** 

## Overview
To predict the rate of gold we studied the change the of rate of gold over a given period of time
with respect to other commodities. Predicting the nature of change that will happen on the change of rate of other commodities we trained our algorithm.

Here we have trained our algorithm by plotting a map between gold rate vs other commodities rate with the help of matplotlib and seaborn librabries.


### **IN OUR CODE:**
 	- We first imported the numpy (for linear algebra) and panda (data processing for 2D data) libraries in our code.
	- Then we read the input data set(csv) and drew the graph of rate of gold vs other commodity and heatmap for gold rate.
	- Now we fit the given data set's parameters in our model and train it.
	- Then we will try to predict the rate of gold when all other parameters are given using random forest regression model.
	- Then we find out the errors and accuracy between our predicted value and actual value.
	- Finally we draw a graph showing the faults in between the actual and predicted values.
						
						
						
### **NOTE:**
    - PLEASE SEE THAT THE CSV FILE AND THE PROGRAM ARE IN THE SAME DIRECTORY OR IT WILL NOT FUNCTION AS EXPECTED.
	- ALSO NOTE THAT AS WE ARE ONLY DEMONSTRATING HOW A PREDICTION ALGORITHM WILL WORK SO WE USED THE SAME DATA SET BY SPLITTING IT, IN REAL LIFE MODELS THE DATA SET MAY OR  MAY NOT CONTAON ALL THE PARAMETERS REQUIRED FOR THE MODEL TO BE ACCURATE AND ALGORITHM ARE TO BE USED TO COMPLETE THAT GAP BY PROVIDING OPTIMAL PARAMETERS AND ERROR TROUBLESHOOTING.


##### *ALSO NOTE THAT:*
    - THE MODEL WE HAVE MADE IS ILLUSTRATED FOR SPX,GOLD,USO,SLV,EUR/USD VARIABLES AS PARAMETERS. FOR THE CHANGES IN PARAMETERS IN DATA SET WE HAVE TO ADD OR SUBTRACT CODE FOR FINDING RELATIONSHIP OF GOLD RATE WITH THE PARAMETER.
						
						
						
### **WHAT WE CAN ADD:**
    - WE CAN MAKE THE ALGORITHM SUCH THAT IT IS CAN BE APPLIED ON REAL VALUES.(by optimal use of parameters and error handling.)
	- TO MAKE IT POSSIBLE TO IMPORT DATA SET FROM ANY LOCATION AND ALSO GIVING THE CONTROL TO DO THAT TO THE USER BY GIVING IT IN THE PROGRAM.
	- WE CAN ADD GRAPHICAL USER INTERFACE IN THE APPLICATION SO IT IS EASY FOR THE USER TO OPERATE IT.
					                         
