# MechaCar_Statistical_Analysis
Statistical analysis of MechaCar

## Deliverable 1

### Linear Regression to Predict MPG
![MPG_Linear_Regression](https://user-images.githubusercontent.com/104606589/189550747-525d078f-e87a-47a2-9fdf-e1a3a70eed50.png)
### Summary Statistics for Linear Regression model
![Summary_Linear_Reg_MPG](https://user-images.githubusercontent.com/104606589/189550775-ce4ef373-db45-4e05-b8d0-fa5f3f149bba.png)
- When looking at the summary you can see that ground clearance and vehicle length have the highest  have strong likely hood of impacting the total MPG.  While All Whell Drive, Spoiler Angle, and Vehicle Weight does not seem to be as good of a predictor for the MPG of the vehicle.
- We have an assumed significance of 0.05% which is much higher then the P-Value of 5.35e-11 that is being returned. This would lead us to reject the null hypothesis, which infers that the slope of this linear model in not zero.
- With an r-squared value of 0.7149 we can be comfortable that this model does predict MPG reliably. 
### Summary Statistics on Suspension Coils
- Below is a summary of the total population of coils tested.  This summary is not stratified in any way it shows the values observed when looking at the largest population of samples.  You will notice that the mean and median are very close together, giving us the impression that the data is normally distributed.

![totals_summary](https://user-images.githubusercontent.com/104606589/189551215-8607ec70-bc2f-49fe-b357-584bfa9511ee.png)
- Below is a summary of the same data, broken up by lot.

![Lot_Summary](https://user-images.githubusercontent.com/104606589/189551220-1a30639d-2a1c-4721-861f-cc80c8a01267.png)

-  When looking at the total population the minimum variance of 100 PSI has been met.  When looking deeper into the sample it looks like Lot 3 does not meet the minimum requirement and there would be justification to research what happened with this specific lot. The extreme variance in lot 3 is hidden when only looking at the population as a whole. 
### T-Test on Suspension Coils

