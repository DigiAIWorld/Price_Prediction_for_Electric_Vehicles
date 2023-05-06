# Data Analysis and Price Prediction of Electric Vehicles

## Overview of Electric Vehicle Sector

The supply of fossil fuels is constantly decreasing. The situation is very alarming. It is time for the world to slowly adapt to electric vehicles. A lot of change needs to happen. Major carmakers like Tesla and Porsche manufacture many electric vehicles. The improvement of battery technology in recent years has led to the higher popularity of electric vehicles. Buying an electric vehicle can be a great choice for consumers. The drive quality, low noise levels, and convenience are really great. In the United States, one year of driving a petrol car can cost from 1500 USD to 2500 USD. On the other hand, the driving cost of Electric Vehicles is 500 USD. Electric cars are more preferable. The maintenance cost of electric vehicles is also very low. They are economical to maintain. The energy conversion efficiency of electric vehicles is also high. Electric vehicles use 60-70% of electrical energy. On the other hand, vehicles based on internal combustion engines have an efficiency of 18-22% only.

![image](https://user-images.githubusercontent.com/43418706/236498281-01fa6647-7865-4964-9702-dc85fe3b1620.png)

Electric vehicles are made for the future and will be a big innovation. They are good for the environment and they do not emit any greenhouse gases.

There are, however, many challenges associated with electric vehicles. They have a limited range. Charging the vehicle takes time and can be a hassle sometimes. The availability of charging stations is also a big issue. Incompatibility of charging stations can also be a problem. Despite many challenges and issues, switching to electric vehicles is good for the environment and is more economically viable in the long term. Many have predicted that, by 2040, most of the vehicles will be electric. Rising fossil fuel costs and high maintenance costs of petrol and diesel vehicles coupled with environmental concerns are the main reasons. Many developed countries have given incentives for purchasing electric vehicles. Automobile manufacturers are already manufacturing some impressive electric vehicles.

The energy cost of manufacturing an electric vehicle is also very high, but considering everything and the fact that charging electric vehicles is very cheap, EVs are a great option. Manufacturing batteries is an important task in the production of Electric vehicles.

### Analyzing some data related to various popular electric vehicles available in the European Market.

## Electric Vehicle Data

       1. Vehicle Battery capacity (in KWH)
       2. Acceleration (0-100) in Seconds
       3. Top Speed in Km/hr
       4. Range of Vehicle in km
       5. The efficiency of Vehicle in Wh/km
       6. Fast charge speed in km/hr
       7. Drive Configuration
       8. Number of seats
       9. Price in Germany (Euro)
      10. Price in the UK (Pound)

Data Source on Kaggle: https://www.kaggle.com/kkhandekar/cheapest-electric-cars

The data consists of 180 vehicles and there are some missing values as well. We can conduct various data analytics visualizations to understand the data and information. This gives us an idea about the market as a whole and overall data distribution. Often, this type of data gives insight into the market and lets businesses conduct market research. The electric vehicle market is growing at a fast pace, with proper investment and research, the field can be improved and a higher level of efficiency can be achieved.

### Data Visualization for Electric Vehicles

![image](https://user-images.githubusercontent.com/43418706/236496298-4777bcbd-da59-4391-973d-b96b68dd1377.png)

The lighter the colour, the more the correlation between the two data points. For example, we can see that price in Germany and price in the UK have a correlation of “0.7”, which is a good score. So, the correlation data has many real-life similarities.

For example, Top Speed has a high correlation to price in Germany and price in the UK. So, it makes sense. A car that has a higher top speed will have a higher price. Similarly, vehicle range and KWH has a high correlation of 0.89, it is obvious as the battery capacity, more will be the range of the vehicle. The correlation heatmap is thus, a great way to understand which data columns are related to each other.

Other data visualisations and various types of plots can be made to visualise the data distribution and understand the whole data. Doing proper data exploration can help in the overall data-driven decision-making process.

## The count of each type of drive for the vehicles
![image](https://user-images.githubusercontent.com/43418706/236496705-ad417379-cd06-4c95-842f-7a59d5321d7b.png)

## Vehicle KWH Compared with Number of Seats and Drive Type
![image](https://user-images.githubusercontent.com/43418706/236497097-bc14dd4b-20b1-44de-bf4f-9b901ac28a70.png)

## The various car manufacturers
![image](https://user-images.githubusercontent.com/43418706/236497492-cc460735-af95-41c0-87a3-faac201793c2.png)

We can see that Audi and Tesla have the most types of electric vehicles

### Audi

![image](https://user-images.githubusercontent.com/43418706/236500715-b4ad2071-24cd-4ca8-b476-a140700efe6b.png)

### Tesla

![image](https://user-images.githubusercontent.com/43418706/236500749-ac54f7f2-6614-4908-b060-d69643bd38b1.png)

## With pair plot type

![image](https://user-images.githubusercontent.com/43418706/236497772-b12ba6d5-ee4e-40f5-a7bc-339ea6933ea7.png)

Various factors contribute to the prices of electric vehicles, a lot of parameters are also to be
considered to buy electric vehicles. Let us now work on a Machine Learning model which[
](https://digiaiworld.netlify.app/)
can do the prediction.

## Using Machine Learning Model (Random Forest Regression) For Price Prediction of Electric Vehicles

To predict the price of the vehicle based on all the parameters and data, one thing to
be pointed is that many data points are missing. In, the case of vehicle prices, many vehicles
have prices just in Pounds, and some have prices just in euros. So, for the sake of simplicity,
we take only the prices in UK Pound.

## Follow me: 
* Linkedin: https://www.linkedin.com/in/digiaiworld/
* Portfolio: https://digiaiworld.netlify.app/


