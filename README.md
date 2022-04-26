# MechaCar_Statistical_Analysis

## Project Overview
Jeremy´s upper management gave him a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.  
For this project we made the following insights/ data summary:
- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes  
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots  
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population  
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.  


# DELIVERABLE 1

## Linear Regression to Predict MPG  

### Results
![DEL1.1](https://github.com/ManuelRuizF/MechaCar_Statistical_Analysis/blob/main/resources/Del1.PNG)  
------------------------------------------------------  

![Del1.2](https://github.com/ManuelRuizF/MechaCar_Statistical_Analysis/blob/main/resources/Del1.1.PNG)  

-----------------------------------------------------  
### Summary  
The results showed us some important insights to understand the data. There were 2 variables that provided non-random amounts of variance to the model. According to the best p-values these are the 3 variables that provide non-random amounts to the model: The vehicle weight, spoiler angle, and All Wheel Drive (AWD).  
There is sufficient evidence to reject our null hypothesis, which further indcates that the slope of this linear model is not zero, since the p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%.  
This linear model does predict mpg of MechaCar prototypes effectively, since it has an r-squared value of 0.7149. 

# DELIVERABLE 2 

## Summary Statistics on Suspension Coils

![Del2](https://github.com/ManuelRuizF/MechaCar_Statistical_Analysis/blob/main/resources/del2.PNG)  

----------------------------------------------------  

![Del2.2](https://github.com/ManuelRuizF/MechaCar_Statistical_Analysis/blob/main/resources/del2.2.PNG)  

-----------------------------------------------------   
### Summary
The entire population of the production lot, the variance of the coils is 62.29 PSI, so the answer is that the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually. The only one that doesn´t meet the standarts is the lot 3 with a PSI of 170.  
  
# DELIVERABLE 3  

### Summary  
The mean of the sample is 1498.78, and a p-Value of 0.06, which is higher than the common significance level of 0.05. This means that there isn´t enough evidence to support rejecting the null hypothesis.

Individual lots:

Lot 1 & 2 sample actually has the true sample mean of 1500, again as we saw in the summary statistics above. With a p-Value of 1, clearly we cannot reject (i.e. accept) the null hypothesis that there is no statistical difference between the observed sample mean and the presumed population mean (1500).
The Lot 3 has a sample mean of 1496.14 and the p-Value is 0.04, which is lower than the common significance level of 0.05. All indicating to reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.
## T-Tests on Suspension Coils  
![Del3](https://github.com/ManuelRuizF/MechaCar_Statistical_Analysis/blob/main/resources/Del3.PNG)  
-----------------------------------------------------  
![Del3.1](https://github.com/ManuelRuizF/MechaCar_Statistical_Analysis/blob/main/resources/DEL3.2.PNG) 
----------------------------------------------------  
  
# DELIVERABLE 4  
## Study Design: MechaCar vs Competition  
You will earn a perfect score for Deliverable 4 by completing all requirements below:

The statistical study design has the following:
A metric to be tested is mentioned (5 pt)
A null hypothesis or an alternative hypothesis is described (5 pt)
A statistical test is described to test the hypothesis (5 pt)
The data for the statistical test is described (5 pt)

### Metric  
Current Price (Selling): Dependent Variable

### Tools
- R language
- R Studio

### Hypothesis  
Null Hypothesis: MechaCar is priced correctly based on its performance of key factors for its genre per year according to data.

### Test and description
We applied the multiple linear regression to describe how realted are the prices according to the impact it has historically made.


