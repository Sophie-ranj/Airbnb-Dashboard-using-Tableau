
# Seattle Airbnb Listings Dashboard

This is a data cleaning and visualization project created entirely in Tableau from a Kaggle dataset about Airbnb listings in the Seattle area of the US from 2016

![main](https://github.com/Sophie-ranj/Airbnb-Dashboard-using-Tableau/blob/54a137391ae8729c60f2084bc467d5c78c99669f/Resources/main.jpg)


## Live Dashboard

The live dashboard can be viewed at the following link: 
(https://public.tableau.com/app/profile/sophie.ranj/viz/AirBBVisuallization/Dashboard1?publish=yes)


## Key metrics observed:

### Average price of an Airbnb listing

This is shown as a bar graph and depicts the prices in USD for property listings ranging from those with just a single bedroom to those with six bedrooms at max.

![avg](https://github.com/Sophie-ranj/Airbnb-Dashboard-using-Tableau/blob/665b310a0152368c2c5fb3ca08b8b23d0ee381e0/Resources/Avgprice.jpg)

#### Insights

The prices can be seen to increase with the number of bedrooms steadily. Larger properties with more bedrooms generally can accommodate more guests. Hosts often charge higher prices for properties that can house larger groups of people.

Properties with multiple bedrooms may cater to a different target audience, such as families or larger groups of travellers. Hosts may set prices based on the willingness of these groups to pay more for a larger and more accommodating space as well as additional offered facilities.

### Prices by Zipcodes

This is represented with both a bar graph format and a more visually appealing map visual.

![zipcode](https://github.com/Sophie-ranj/Airbnb-Dashboard-using-Tableau/blob/665b310a0152368c2c5fb3ca08b8b23d0ee381e0/Resources/Zipcodeprice.jpg)

The map visual segments all of the property listings based on their zip codes. Hovering over any segment on the map will display the zip code of that particular locality as well as the average price of an Airbnb located within that vicinity.

### Revenue for the year

This line chart shows the variation in the total price for all the available Airbnb listings as per the 'Calendar' table throughout 2016.

![revenue](https://github.com/Sophie-ranj/Airbnb-Dashboard-using-Tableau/blob/665b310a0152368c2c5fb3ca08b8b23d0ee381e0/Resources/revenue.jpg)

#### Insight

The prices saw a steady rise from months 'January' to 'March' and again after 'November'. This could be due to the general perception of favourable weather conditions for tourists coming to Seattle from January to March or due to a higher frequency of leisure activities or events occurring between these months leading to increased demands and thus higher prices.

Also, the period after November might coincide with winter vacations, Christmas and a general holiday season again leading to an increased demand and thus higher Airbnb prices overall.

### Total number of distinct bedroom listings

The distribution of the Airbnb listings ranging from a single bedroom up to six bedrooms are represented as a table within the dashboard.

![bedroom](https://github.com/Sophie-ranj/Airbnb-Dashboard-using-Tableau/blob/665b310a0152368c2c5fb3ca08b8b23d0ee381e0/Resources/bedno.jpg)

#### Insights

The properties with just a single bedroom are the greatest in number as shown by the table reaching close to 2000 listings in total while the total number of properties offering two to six bedrooms is approximately 1000 in total, far less than those that offer just a single bedroom.

This implies that there might be a higher demand or preference for smaller accommodations with just a single bedroom within Seattle. It could also suggest that the market might be more oriented toward catering to individual travellers, couples, or small groups.

The data may also reflect the competitive landscape in the area. If there are more one-bedroom listings, hosts with larger properties may face less competition within their category.

## Dataset

The dataset pertains to Airbnb property listings in Seattle from 2016. It is publically available on Kaggle at the following link: (https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset/data?select=Tableau+Full+Project.xlsx)

The dataset as a whole comprises three tables 'Calendar', 'Listings' and 'Reviews'.

The 'Calendar' table comprises 4 columns and about 1.05 million rows.

It gives details about certain properties such as their unique ID (lisitng_id), the date on which it was listed on Airbnb, a flag to indicate whether it's still available or not and finally its price.

![calendar](https://github.com/Sophie-ranj/Airbnb-Dashboard-using-Tableau/blob/665b310a0152368c2c5fb3ca08b8b23d0ee381e0/Resources/calender1.jpg)

The 'Listings' table is quite extensive comprising 3818 rows and about 92 columns.

It details the unique ID, URL, description, zip code and a whole bunch of different attributes regarding a particular property.

![listing](https://github.com/Sophie-ranj/Airbnb-Dashboard-using-Tableau/blob/665b310a0152368c2c5fb3ca08b8b23d0ee381e0/Resources/calendar2.jpg)

Finally, the 'Reviews' table consists of about 84,800 rows and 6 columns.

As the name suggests, it provides details regarding a review given by a past occupant of a particular property. So, the table includes the unique ID of a particular property, the reviewer's ID, name as well as a description of the remark that they gave regarding the property.

![review](https://github.com/Sophie-ranj/Airbnb-Dashboard-using-Tableau/blob/665b310a0152368c2c5fb3ca08b8b23d0ee381e0/Resources/calendar3.jpg)


## The data analysis process

The initial step in the process pertained to cleaning the tables in the dataset by removing missing values and column attributes which were irrelevant to the analysis.

Different joins such as 'left joins' were performed between the tables to prepare the dataset for visualization.

Finally, the cleaned dataset was observed using different visuals and a fully-fledged dashboard was then created within Tableau.

## Conclusion

The dataset used for this project dates back to 2016 and thus might not provide an accurate representation of the Airbnb market trends within Seattle.

The dashboard can be updated to include data from more recent years to give a more detailed insight into how the market for Airbnb listings within Seattle has shifted within recent years owing to different economic factors as well as the outbreak of COVID-19 in late 2019 and 2020.






