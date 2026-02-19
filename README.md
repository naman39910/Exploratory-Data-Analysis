# Exploratory Data Analysis : Hotel Booking
## Problem Statement
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyze the data to discover important factors that govern the bookings.

## Business Objective
Analyse the data on bookings of City Hotel and Resort Hotel to gain insights on the different factors that affect the booking. This is undertaken as an individual project.
## Project Summary
In this project we began to explore the dataset in which Hotel Booking comprises of two types of hotels i.e City Hotel and Resort Hotel.

In this dataset, there are 119390 rows and 32 columns.

All the columns are divided into three dtypes : Object, float64 and int64.

In this dataset, there are both duplicates and missing values available. So, we have to deal with that and as a result i have replaced the null and missing values and also i dropped the duplicate values.

The maximum number of missing values are from 'Company' column then followed by 'Agent','Country' and 'Children' columns. The 'Children' column consists of only 4 null values while 'Company' column consists of 112593 null values.

In this project, i divided the data manipulation workflow into three categories i.e. Data Collection, Data cleaning & manipulation and EDA(Exploratory Data Analysis).

In moving further, i have used various basic functions and attributes i.e Data collections first step to find different columns which is done by various methods like Head(), tail(), info(), describe(), columns() and some others method used for data collections.

As i further moved, i check the number of unique values of each columns and generate a list of those values and then also find the unique values of each columns later on.

Then further i converted the datatypes of columns into appropriate datatype. I added some of the columns name here, one is 'total_people' and other is 'total_stay'.

Find some columns are not in accurate data types which correct it later, done in Data cleaning part and as well as duplicates data items must be removed as i find duplicate items equal to 31994 which is dropped from dataset later.

I found that there were some rows in which the combining values of adults, babies and childrens was 0, so this simply means there were no guests as 0 indicates presence of none. So, there were no bookings made. As a result, i simply dropped the rows where combining values of adults, babies and children columns was 0.

The data type of 'reservation_status_date' column was object type, so it was changed to date type format for better use.

Before visualizing any data from the data set we have to do data wrangling. For that, i have checked the null value of all the columns. After checking, when i find minimal number of null values, filling these null values with necessary values as per requirement by using fillna().

So, after completing the process of data wrangling, i moved to the data visualization part.

In the data visualization process, i have used various charts and have dived deep understanding the graphs to catch the proper insights from the data. That gives the business outcomes which will ultimately boost the businesses.

So, i explored and analyzed the data to discover important factors that govern the bookings.

## Solution to Business Objective
To attain high growth and more success, hotel business need to flourish and for that few things which we need to consider is high revenue generation, customers satisfaction and employeee retention.

We are able achieve the same by showing the client which are the months which are high in revenue generation by using various charts and graphs distribution.

Enhancing the revenue adopted by bar chart distribution of which type room are most preferred and reserved and which are the months suitable for visitors.

We also have founded the various preferences in different categories like most liked meal type, optimal stay length, facilities required by customers like car parking spaces, etc. So, all these insights ultimately add to have a better planning for growth and higher revenue.

So, preparing well by using and understanding these useful outcomes, the client can be well prepare in advance so that minimum grievances would be faced by clients in long run and would help in further enhancement of their hospitality and service.

Ask for feedback often from the guests visiting the hotels so that the quality can be upgraded to the next level to increase more guests.

Periodically throw offers to attract the old customers so as to increase the number of repeated guests.

## Conclusion
City hotels are the most preferred hotel type by the guests. So, we can say that City hotels are the busiest hotel in comparison to the resort hotel.

The average ADR of city hotels is higher as compared to the resort hotels. So, it can be said that these City hotels are generating more revenue than the resort hotels.

The total stay of guests is directly proportional to the adr. So, higher the days of stay, the higher will be ADR and revenue as well.

The percentage of repeated guests is very low. Only 3.9% people had revisited the hotels. Rest 96.1% were new guests. So, retention rate is much low.

The percentage of required car parking spaces is very low. This means less car parking spaces don't affect the business much. Most of the customers (91.6%) do not require car parking spaces.

Among different types of meals, BB (Bed & Breakfast) is the most preferred type of meal by the guests. So, guests love to opt for this meal type.

'Direct' and 'TA/TO' have almost equally contribution in ADR in both type of hotels i.e. 'City Hotel' and 'Resort Hotel'. While, GDS has highly contributed in ADR in 'City Hotel' type.

Optimal stay length in both the hotel types (City and Resort Hotel) is less than 7 days. Usually people stay for a week. So, after 1 week, the optimal stay length declined drastically.

Most number of bookings have taken place in the month of July and August. July and August are the favourite months of guests to visit different places.

The mostly used distribution channel for booking is 'TA/TO'. 79.1% bookings were made through TA/TO (travel agents/ tour operators).

While calculating ADR across different month, it is found that for Resort hotel, ADR is high in the months of June, July, August as compared to City Hotels.

Almost 1/4th of the total bookings is canceled. Approx, 27.5% bookings have got canceled out of all the bookings.

Majority of the guests have shown interest in the room type 'A'. Room type 'A' is the most preferred room type.
