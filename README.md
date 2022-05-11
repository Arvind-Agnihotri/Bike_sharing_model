# Bike_sharing_model
> To understand the factors influencing the sales of the bike sharing model by analysing the existing data with multiple parameters and building a model for future predictions


## Table of Contents
* General Info
* Technologies Used
* Conclusions



## General Information
- A dataset is available with multi-variables displaying the sales of the bike sharing business
- We are attempting to derive the influencing factors that affect the sales of the business basis the available dataset
- A multivariate MLR model is developed in this project to derive the driving factors



## Conclusions
- The trained model fits well agaisnt the test dataset with a satisfactory predictive value
- The driving factors that affect the sales of the bike sharing are as below
   'yr', 'holiday', 'atemp', 'windspeed', '2:mist', '3:light_snow_rain','2:summer', '4:winter', 'Aug', 'Sep'
   The best fit line of the model is 
   cnt = 0.125 + 0.2334 x yr - 0.0934 x holiday + 0.5370 x atemp - 0.1319 x windspeed -0.0822 x 2:mist - 0.2760  x 3:lightsnowrain + 0.0990 x 2:summer +0.1311 x 4:winter + 0.0679 x Aug + 0.1209 x Sep




## Technologies Used
- Pandas, Numpy, Seaborn, Matplotlib, Sklearn, Statsmodel




## Contact
Created by [ @githubusername- Arvind-Agnihotri] - 

