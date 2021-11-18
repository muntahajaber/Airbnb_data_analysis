# Airbnb-prices

This project aims to build a regression model to predict Airbnb room prices in Saudi Arabia.

## Data

We scraped the data from Airbnb website and the final data can be found in this link

## EDA

This is [the link](https://public.tableau.com/app/profile/elaf1539/viz/AirbnbPricesinSaudiArabia/Dashboard1?publish=yes) to the Dashboard we made for EDA

## Model

Our best model was achived following this steps:<br>
1- Remove Outliers<br>
2- Gridsearch with ElasticNet<br>
3- Select kbest features (62 features)<br>
4- Apply Random Forest<br>
5- Apply linear regression<br>

## Web app
We also developed a web application using streamlit, where the user enters the room details and it presict the price of the room.
![alt text](https://raw.githubusercontent.com/elafsalem/Airbnb-prices/main/Web%20app/Pics/screenshot1.png) <br>
![alt text](https://raw.githubusercontent.com/elafsalem/Airbnb-prices/main/Web%20app/Pics/screenshot2.png)
