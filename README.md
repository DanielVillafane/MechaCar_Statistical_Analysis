# MechaCar_Statistical_Analysis

## Overview
AutosRUs’ required specific data to assist the with manufacturing of the Mechacar. We provided multiple analysis below:

## Linear Regression to Predict MPG
- The variables below provide variance to the MPG values in the MechaCar_mpg dataset:
	- vehicle_length
	- vehicle_weight
	- ground clearance
	
	
- The p-value of this multiple linear regression analysis is 5.35 x 10(-11). There is enough here to reject the null hypothesis.

![Deliverable_1](/Resources/1_lin.png)

- This linear model shows that 71.49% of MPG predictions of MechaCar prototypes will be correct. It also suggests there is a correlation between MPG and vehicle specs / features (weight, length, All wheel drive, etc).

## Summary Statistics on Suspension Coils
Mechacar design specs for suspension coils dictates the variance must not exceed 100 pounds per square inch (PSI).

The variance of the suspension coils for all three lots was 62.29.  
![Deliverable_2_TotalSum](/Resources/2_suscoil.png)

Lots 1, 2, and 3 were examined individually. Lots 1 & 2 were below the 100 PSI variance. Lot 3 was not (170.28).

![Deliverable_2_LotSum](/Resources/3_lot.png)


## T-Tests on Suspension Coils
We used t-test to determine if PSI across all lots was different from the population mean of 1500 PSI. We visualized this with a density plot: 

![Deliverable 2_DensityPlot](/Resources/4_ttest.png)


In all t-tests conducted, the mean remained extremly close the 1500 population mean.

Suspension coil t-test  had a p-value of 0.06  

![Deliverable_3_All_T-test](/Resources/5_suspv0602.png)

Lot 1 had a p-value of 1

![Deliverable_3_Lot1_T-test](/Resources/6_suspv1.png)

Lot 2 had a p-value of 0.6072 

![Deliverable_3_Lot2_T-test](/Resources/7_suspv06.PNG)

Lot 3 had a p-value of 0.4168

![Deliverable_3_Lot3_T-test](/Resources/8_suspv04.png)

## Study Design: MechaCar vs. Competition
### Description of Statistical Study
Fuel efficiency. How would Mechacar fare verse the competition.

### Metric
- Miles Per Gallon (MPG)

### Hypothesis
- Null hypothesis: MPG for MechaCars is equal to their competitors
- Alternative hypothesis: MPGfor MechaCars is not equal to their competitors

### Data needed
We would need multiple data points when analyzing MPG (Engine Size, Wheel Base, Horse Power, Vehicle Size/ Weight, Tire Size)
