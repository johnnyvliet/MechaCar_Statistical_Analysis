# MechaCar_Statistical_Analysis

## Linear Regression to predict MPG
![MPG Summary (2)](https://user-images.githubusercontent.com/85916216/136069512-55d9c396-7769-42fd-9e40-fe59455dafbe.png)
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  1. Vehicle Length, Vehicle Weight and Ground Clearance. These three have the lowest values in the Pr(>|t|) column
- Is the slope of the linear model considered to be zero? Why or why not?
  1. The slope is not considered to be zero since the multiple R-Squared value is not zero
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  1. It does to a certain degree. The closer the multiple R-Squared value is to 1 or negative 1 the better. In this case, the multiple R-squared value is 0.7 showing that there is a strong amount of correlation

## Summary Statistics on Sunspension Coils

![Total_summary](https://user-images.githubusercontent.com/85916216/136072078-9656b217-69ef-458e-9737-309b4009cc2e.png)
![Lot_summary](https://user-images.githubusercontent.com/85916216/136072094-967769e1-b091-4085-af88-54238b4b20df.png)
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  1. Yes and no. Looking at the Total Summary, the overall variance is about 62 lbs/square inch. Looking at each lot specifically, the variance for Lot 3 is 170 lbs/square inch
