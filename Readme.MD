# MechaCar Statistical Analysis

## Overview of the analysis:

A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, you’ll help Jeremy and the data analytics team do the following:

Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
Run t-tests to determine if the manufacturing lots are statistically different from the mean population
Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

- UFO Results Objective:
Deliverable 1: Linear Regression to Predict MPG
Deliverable 2: Summary Statistics on Suspension Coils
Deliverable 3: T-Test on Suspension Coils
Deliverable 4: Design a Study Comparing the MechaCar to the Competition


# Deliverable 1: Linear Regression to Predict MPG

<img width="578" alt="Delivery1" src="https://user-images.githubusercontent.com/39811614/173270593-23a04fcb-6983-4cce-9799-3f8cbcb94067.png">

## Deliverable 1 Observation summary:

- The P-Value for this tested dataset gives a P-value: 5.35 which it surpass the assumed significal level of .05 of the dataset. Therefore, This indicates there is sufficient evidence to <br> reject the null hypothesis </br>, this tells us that the slope does not end on zero. 

# Delivery 2 - Summary Statistics on Suspension Coils

## Total Summary
<img width="315" alt="Total_summary" src="https://user-images.githubusercontent.com/39811614/173272129-3e2aa74c-10c2-4f8b-b2cb-68e773698bf6.png">

## Lot Summary

<img width="477" alt="Lot_summary" src="https://user-images.githubusercontent.com/39811614/173272184-f878e80c-9dfb-4975-a3d8-15b770a10a33.png">

## Deliverable 2 Observation summary:

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 

Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

- Total summary dataset:
Based on the total summary dataframe. The data shows that the current manufacturing data meethis the design specifications for all manufacturing lots as we can see in the total variance of the suspencion coils that is 62.29 which is with in in the limit parameters not to exceed 100.

- Summary dataset per lot: 

The data shows for the the each individual lot that lot 1 and 2 meet the requirements guidelines from the design specification. However, lot 3 does not meet the requirement therefore it will need a modification or a removal from production. 


# Delivery 3 - T-Test on Suspension Coils

## All lots T-Test
<img width="413" alt="All_lot_T-test" src="https://user-images.githubusercontent.com/39811614/173277857-a499b8f4-d0c6-4b54-a18d-e81a6023c5e3.png">

## Lots 1 T-Test

<img width="536" alt="lot_1_Ttest" src="https://user-images.githubusercontent.com/39811614/173277973-19d570a5-dbda-4b61-8e6f-bdd5298524b4.png">

## Lots 2 T-Test

<img width="525" alt="lot_2_Ttest" src="https://user-images.githubusercontent.com/39811614/173278064-29e13ce1-825b-4e09-8e76-011b051a0385.png">

## Lots 3 T-Test

<img width="533" alt="lot_3_Ttest" src="https://user-images.githubusercontent.com/39811614/173278135-adbce3c5-ade4-4bac-a5e6-3158617d11bf.png">



## Resources

- Data Source: MechaCar_mpg.csv and Suspension_coil.csv
- Data Tools: tidyverse, dplyr, ggplot2 and MechaCarChallenge.RScript
- Software: Python 3.9.7., Visual Studio Code, R Studio 
## Results:

## Implications




