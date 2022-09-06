# MechaCar Analysis - AutosRUs

## Deliverable 1

![](/resources/linearRegression2.png)

1. Vehicle Length and Vehicle Ground Clearance seem to play the largest roles in determining the MPG on the car. 
2. The p-Value being so small seems to indicate that the slope of the  linear model is not zero.
3. With an r-squared value of 0.7149, it seems to predict the mpg of prototypes relatively effectively.


## Deliverable 2


First looking at all manufacturing lots:

![](/resources/totalSummary.png)

![](/resources/lotSummary.png)

Yes, the variance of the total lots does fit within the required 100psi. On another note, lot 1 and lot 2's variance is significantly lower at 0.97 and 7.46 respectively, whereas lot 3 has a variance of 170.28, skewing the data for the total lots dataframe. 

## Deliverable 3 

## T-Tests on Suspension Coils

![](/resources/t_test_all.png)

As a whole, the mean of all three manufacturing lots is very similar to the expected mean of 1500. 

####Individual Lots

![](/resources/t_test_lot.png)

Lot 1 and Lot 2 have a true mean very close to the expected mean of 1500, with Lot 1 hitting it spot on. However Lot 3 has are significantly different as well as a p-value below 0.05, indicating that they are statistically different. 


## Deliverable 4:  

#### Metrics
Independent Variables
 - Safety Feature Rating
 - Drive Package
 - Engine
 - Resale Value
 - Average Annual Cost
 - MPG

Dependent Variables
 - Current Price

#### Hypothesis

Null Hypothesis (Ho)
 - MechaCar is priced correctly based on its performance of key factors for its genre.

Alternative Hypothesis (Ha)
 - MechaCar is NOT priced correctly based on performance of key factors for its genre.
 
#### Statistical Tests
Multiple Linear Regression would be used to find which factors have the highest correlation with the current selling price. 
