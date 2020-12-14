# Welcome to My Capstone Project for the Data Science Immersive course from MISK Academy
## Author Name: Fahad Reda
## Problem Statement: Flight Price Prediction ( Regression Problem)
## Problem Overview: 
**One of the main thing to consider while traveling is calculating the cost of the trip, where the price of the flights ticket plays an important role, so this project is going to help the traveler to Predict the flight ticket,as buying tickets is a very hectic process, the output (Y) will be the Price of the Flight**
## Features Available in the Dataset:
[dataset](https://flic.kr/p/2kh1r8f)
These are the Features in our dataset:
    1.Airline: The name of the airline.
    2.Date_of_Journey: The date of the Trip
    3.Source: The source from which the service begins.
    4.Destination: The destination where the service ends. 
    5.Route: The route taken by the flight to reach the destination.   
    6.Dep_Time: The time when the journey starts from the source.  
    7.Arrival_Time: Time of arrival at the destination.  
    8.Duration: Total duration of the flight. 
    9.Total_Stops: Total stops between the source and destination(if there is any!).  
    10.Additional_Info: Additional information about the flight Price
    11. Price: the Price of the flight (in Rupes) (Dependent Variable) AKA the Target
## Data Collection and Cleaning
[Source of the dataset](https://www.machinehack.com/)
There are 10683 rows and 11 Columns (Features) in the Train dataset and  2671 rows and 10 Features (Minus the Price feature)
## Feature Extraction and Engineering
1-A lot of Data Preprocessing needed to be done for e.g, like converting object data type to datatime data type by using pandas to_datetime
2-Extracting the 'Journey_Day' and 'Journey_Month','Weekday' Features  from Date of Journey Feature
3- Extracting the Hours and Minutes from Arrival Time Feature
4- Extracting the Day and Month from Date of Journey Feature
and many more....
## Challenges I Faced 
1- This is a Regression Problem so I tried to use other Algorithms instead of Linear Regression, so this was a little bit challenging
2- Tried to Improve the models , some of them was able to increase 1% , but other's the improvement was very low
3-Faced some issues with creating charts using seaborn, but was able to finally done it (check the high Quality charts folder)

## Models used with their Accuracies
**1- Random Forest = 90.03%
  2-KNN= 77.05%
  3-XGBoost = 87.48%
  4-Gradient Boost= 87.59%
## Conclusion:
It was very challenging project used almost everything I Learned from the DSI Course .
## Future Work:
In Future I would love to use Deep Learning ,and try to build an App ( Deploying the model)
Thanks for Reading


