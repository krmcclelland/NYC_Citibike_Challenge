NYC Citibike Challenge

# Purpose: 
* Import data into Tableau.
* Create and style worksheets, dashboards, and stories in Tableau.
* Use Tableau worksheets to display data in a professional way.
* Portray data accurately using Tableau dashboards.

# Overview of the statistical analysis:
A potential investor for a bike riding startup in Des Moines requested data for a business plan on future revenue streams using a similar Citibike business model in New York City.  We were able to use August 2019 Citibike data from NYC was reviewed by looking at geographical data as well as data disaggregated by user types and genders to determine if it would be a good investment for a new startup in Des Moines.  Other data points include usage durations, peak usage times, and the key target market. 

## Link to CitiBike Analysis Dashboard

![PIC0](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/CitiBike%20Analysis%20Dashboard.png)

## Link to Tableau Story: 
[Tableau Story]()

## Cleaning the Data:
Jupyter Notebook was used to change the trip duration data to a datetime field.
![Pic1](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/before_transformation.png)

![Pic2](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/after_transformation.png)

## Results of the NYC Citibikes Analysis:
For NYC, there were some interesting geographical areas of interest.  Some trips were outside the main city center.  Other areas followed the along the river. Future analysis would need to include a geographical review.

### 1. Checkout Times for All Users
[Checkout Times for All Users]()
The Citibikes usage reaches a top of 3000 minutes per user.
![Pic3](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/3_Checkout%20Times%20for%20All%20Users.png)

### 2. Checkout Times by Gender
[Checkout Times by Gender]()
Males are significantly higher users than others. 
![Pic4](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/4_Checkout%20Time%20By%20Gender.png)

### 3. Trips (Weekday per Hour)
[Trips (Weekday per Hour)]()
6-10 am and 5-8 PM are peak riding hours during the weekday and 5 am to 10 pm on the weekends.
![Pic5](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/5_Trips%20(Weekday%20By%20Hour).png)

### 4. Trips by Gender (Weekday per Hour)
[Trips by Gender (Weekday per Hour)]()
Males are high users during the peak hours. 
![Pic6](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/6_Trip%20By%20Gender%20-%20Weekday%20By%20Hour.png).png)

### 5. Trips by Gender and User Type (Weekday per Hour)
[Trips by Gender and User Type ()
Males subscribers are the highest users followed by female subscribers. 
![Pic7](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/7_Trips%20by%20Gender%20and%20User%20Type%20By%20Weekday.png)

### 6. Number of Rides per Hour
[Number of Rides per Hour]()
Non-peak hours are 1-5 am.  
![Pic8](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/8_Number%20of%20Rides%20Per%20Hour.png)

### 7. Number of Rides with Bike ID
[Number of Rides with Bike ID]()
The divergence line shows that there are high use on 1/3 of the bikes.
![Pic9](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/9_Number%20of%20Rides%20By%20Bike%20ID.png)

## Summary:

1. Bike Repairs for 1/3 of the Citibikes need to be done during non-peak hours around 1-5 am. 
2. Male subscribers are the highest users and follow the traditional high use times of travel to and from work.  
3. Target market should be males needing transportation to work and weekend activities and push for subscribing to the services. 

## Additional Analysis: 

For NYC, there were some interesting geographical areas of interest.  Some trips were outside the main city center.  Other areas followed the along the river. Future analysis would need to include a geographical review.

### 1. Ride Starting Locations by Gender
[Ride Starting Locations by Gender]()
Males are more likely to start a trip farther than the main city center of NYC than others. 
![Pic10](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/10_Ride%20Starting%20Location%20By%20Gender.png)

### 2. Ride Ending Locations by Gender
[Ride Ending Locations by Gender]()
Males are more likely end a trip across the river in the southwest area of NYC than others. 
![Pic11](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/11_Ride%20Ending%20Location%20By%20Gender.png)

### 3. User Type Starting Location
[User Type Starting Location]()
Subscribers are more likely to start trip farther than the main city center of NYC than others. 
![Pic12](https://github.com/krmcclelland/NYC_Citibike_Challenge/blob/main/images/12_Subscriber%20Starting%20Loacations.png)
