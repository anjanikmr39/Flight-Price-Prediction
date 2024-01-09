# **Flight Price Prediction**
-----------------------------

## **Business Case-Study**

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. That’s why we will try to use machine learning algorithms including: Linear Regression, Decision Tree, Random Forest, Gradient Boosting and XG-Boosting to solve this problem. This can help airlines by predicting what prices they can maintain.

-------------
## **Dataset Description**

This Dataset consists Total of 10 Features and 1 Target(Price).

1) Airline: All types of airlines like Indigo, Jet Airways, Air India, and many more.

2) Date_of_Journey: Date on which the passenger journey will start.

3) Source: Name of the place from where the passenger journey will start.

4) Destination: Name of the place to where passenger wanted to travel.

5) Route: Route through which passengers have opted to travel from the source
to their destination.

6) Dep_Time: When the passenger will depart from source.

7) Arrival_Time: When the passenger will arrive to destination.

8) Duration: Whole period that a flight will take to complete its
journey from source to destination.

9) Total_Stops: In how many places flights will stop.

10) Additional_Info: Information about food and other amenities.

11) Price: Price of the flight for a complete journey including all the expenses
before onboarding.

---------

### **Analysis from Graphs**

![image](https://github.com/anjanikmr39/Flight-Price-Prediction/assets/67219753/689bba65-829e-49e7-876e-8d0b77c9825f)

![image](https://github.com/anjanikmr39/Flight-Price-Prediction/assets/67219753/2c432bd8-460e-4350-ab7d-b0af18136c53)

![image](https://github.com/anjanikmr39/Flight-Price-Prediction/assets/67219753/30bda133-d109-4b3e-b000-822c7c00e73c)

1) From the Airline, Source and Destination graphs we analyse that we cannot compare these with respect to price that which airline is best or which city is best for source and destination. So we need to perform One-hot encoding for these. Apart from this we can just say that that Jet Airways Business Airlines have more price and Trujet Airline have very less Price.

2) From Dept_Time vs Price graph we analyse that Mornings flights are low as compare to others, and From Arrival_Time vs Price graph we analyse that Afternoon flights are low price compared to others.

3) From Total_Stops we analyse that if number of stops increases then Price also increases. From Day and Month graph we analyse that, 3rd day of the month have highest price, and April month have the lowest price while January month have the highest price.

4) From the Duration_Mins, we analyse that before 500 min price increase with respect to Duration, but after 500 min only slight increase in price can be seen with respect to Duration.

-------
## **Model Comparison Report**:

![image](https://github.com/anjanikmr39/Flight-Price-Prediction/assets/67219753/c4085398-5c61-4b22-a7fc-8613b75fef24)

**For XG-Boosting**

From the below graph we analyse that below 20000 we are very much accurate on Flight price prediction.

![image](https://github.com/anjanikmr39/Flight-Price-Prediction/assets/67219753/2be53ff0-2efe-4712-82af-487f37e5f6fb)

--------
## **Challenges faced**:

We have to work in EDA part for features like Date_of_Journey, Duration, Dep_Time, Arrival_Time.

From Date_of_Journey we generate two columns Day and Month.

From Duration we converted it into minutes as Duration_Mins.

From Dep_Time and Arrival_time we have to convert time-zones into Morning,
Afternoon, Evening and Night slots accordingly.

Logic of these conversions is little bit tricky.

## **More information**
Visit this python file for more detailed analysis [EquakeDamagePred.ipynb](https://github.com/anjanikmr39/EarthQuake-Damage-Prediction/blob/master/EquakeDamagePred.ipynb).








## **More information**
Visit this python file for more detailed analysis [EquakeDamagePred.ipynb](https://github.com/anjanikmr39/EarthQuake-Damage-Prediction/blob/master/EquakeDamagePred.ipynb).
