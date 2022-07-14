# R_Analysis
## Purpose 
The purpose of this analysis are as follows:
- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, then write a summary of the findings.

## Deliverable 1: Linear Regression to Predict MPG
Using the provided CSV file (MechaCar_mpg.csv), I designed a linear model that predicts the mpg of MechaCar prototypes using several variables (vehicle length, weight, AWD, mpg, spolier angle and ground clearance).
- The variables that provide a non-random amount of variance of the mpg values are vehicle_lenth and gound_clearance. 
- Based on the data gathered, the slaope of the linear model cannot be zero. The p-value I received is 5.35e-11 which is significantlly smaller than the 0.05% significance level. Because of this, we can reject the null hypothesis.
- This linear model predicts mpg efficiently because the r-squared value is around 71% which indicates that 71% of the predictions can be determined by this model created.
