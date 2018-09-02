# Airbnb_Data_Viz

#### Authors: Aashka Aradhya and Rico Rey Holganza

Airbnb is a company based in San Francisco that operates an online marketplace and hospitality service for people to lease or rent short-term lodging. I love travelling and have used Airbnb whenever I have the option to and would love to work for them. That's why I decided to analyze data scraped from their website to present interesting insights and visualizations.

#### **This project has used San Francisco Airbnb data scraped from their website on Aug 16th 2018. I used the following datasets available on the link  :** http://insideairbnb.com/get-the-data.html

* **listings_summary.csv:** Detailed information about each listing such as description, host name, geo-coordinates and so on
* **listngs.csv:** The datasets contains 6,663 listings in the city of San Francisco with details such as: Property Type, Neighbourhood, Price, Number of Reviews, Availability for the next year as seen on their website on August 16th, 2018
* **calendar.csv:** Daily prices of each property in San Francisco from Aug'18 to Aug '19

## **Metric I defined to structure my analysis:**

* **Property Density:** This defines the density level of each property type (Entire Home, Private Room and Shared Room) for each neighbourhood in San Francisco

* **Occupancy Rate:** (Days Occupied in between Aug 16 '18 to Nov 16 '18 (90 days) / 90 Days) * 100

* **Availability Rate:** 1 - Occupancy Rate

## **The questions my analysis aims to answer:**

### **1. Which combination of property type and density level has highest occupancy?**
![](Images/1_Occupancy_Rate_PropertyType_Property_Density.png)
#### **Insights:**

* As can be seen in the visualization above, if one wants to start their Airbnb lisitng a Private Room in a Highly Dense neighbourhood for Private Rooms has the highest occupancy rate, suggesting that visitors who prefer to stay in those neighbourhoods tend to go for Private Rooms. This is followed by Entire Homes in High, Medium and Low Density neighbourhoods (in that order) for Entire Homes. 
* The above visualization also suggests that Entire Homes generally have a higher occupancy rate v/s Shared Rooms. So as someone who's considering listing their property on Airbnb  would find these insights useful to decide where and what kind of property to list

### **2. As a budget traveller booking their future trip in August 2018, which month is the best for me to book?**
![](Images/2_Best_time_to_book_on_a_budget.png)
#### **Insights:**

* As a budget traveller I would most likely book for the month of November 2018 if I am looking at their website on August 16th 2018 since irrespective of property type, the prices see a dip



