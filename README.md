# Project Name : Bike Sharing Assignment
 
> Problem Statement:
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

> Business Objective:
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

The steps we will follow in the exercise are as follows:

Reading understanding and visualizing the data
Prepairing the data for modelling(train-test split, rescaling etc.)
Training the model
Residual analysis
Prediction and evaluation on test set
#### Project Version : V1
#### Project Status  : Completed
#### Release Data    : 14/09/2022

### Files: 
* .pynb file -- jupyter file containing the code
* .pdf file -- power point  in PDF format
* .csv file --- containing original data (1 csv and 1 xlsx file)

### Libraries Used :
* Pandas : 1.2.3
* numpy : 1.20.3
* matplotlib: 3.5.2
* seaborn : 0.11.2
* sklearn

#### Analysis and Findings :
cnt = 0.199434 + 0.490988 X temp + 0.233570 X yr + 0.081741 X season_Winter + 0.076846 X mnth_Sep + 0.046487 X season_summer - 0.052057 X mnth_Jul - 0.067169 X season_ Spring - 0.080167 X weathersit_Mist & Cloudy - 0.097463 X holiday - 0.147919 X windspeed - 0.284199 X weathersit_Light Snow & Rain

All the positive coefficients like temp,season_Summer indicate that an increase in these values will lead to an increase in the value of cnt.
All the negative coefficients indicate that an increase in these values will lead to an decrease in the value of cnt.
Temp is the most significant with the largest coefficient.
Followed by weathersit_Light Snow & Rain.
Bike rentals is more for the month of september
The rentals reduce during holidays
This indicates that the bike rentals is majorly affected by temperature,season and month.


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements 
 - Upgrad/IITB
 - Online Sources : Stackoverflow, Pandas , seaborn , plotly, numpy , matplotlib,sklearn
