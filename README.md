# Bike-Sharing Service Viability

**Tableau Public Visualizations Deployment Link**: https://public.tableau.com/views/NYCCitiBike_16648740238590/NYCCitiBike?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## Overview of the Analysis

### Purpose
The purpose of this analysis was to determine whether or not a bike-sharing service should be launched in Des Moines, Iowa. Specifically, bike-sharing data from New York City's bike-sharing service was analyzed to determine if fungible demographics-related insights could be discovered to increase the probability of success of a similar prospective service in Des Moines.

## Results
The results of this analysis can be viewed below.

### Checkout Times
_____

<img width="1008" alt="2_checkout_times_for_all_users" src="https://user-images.githubusercontent.com/80941606/193877076-69b43696-6e60-4c76-97a5-3a8e319908f3.png">

<img width="1008" alt="3_checkout_times_by_gender" src="https://user-images.githubusercontent.com/80941606/193877103-b771d1a2-e576-44e8-b086-7f64aec04f36.png">

**Figure 1**: This is the distribution of the number of bikes used in a period of time versus the duration of a bike ride.

_____

As can be seen in the figure above, most bike riders use the bike-sharing service for less than one hour; this is mostly independent of one's gender. Moreover, most of the bikes are rented by men. Consequently, this graph informs us of an upper limit of how many bikes may be required to operate in Des Moines given that it has a smaller population and population density of that of New York City. Additionally, as seen in this Figure and Figure 4, marketing efforts may be best targeted towards males since males use the bike-sharing services more than females do.

### Trips by Weekday per Hour
_____

<img width="578" alt="4_heatmap_by_minute_by_hr" src="https://user-images.githubusercontent.com/80941606/193877165-bf833564-dce1-487d-93db-ebd9757f44b7.png">

**Figure 2**: This heatmap showcases the density of bike rides by weekday per hour.

_____

As can be seen in the figure above, the bike-sharing service's ridership is highest during the rush hours of the day when people are going to or coming back from work. Consequently, the bike-sharing service is best targeted towards working-age people in Des Moines who use a bike to commute to and from work.

### Trips by Gender (by Weekday per Hour)
_____

<img width="1171" alt="5_heatmap_time_by_gender" src="https://user-images.githubusercontent.com/80941606/193877734-07e6e2dd-649a-412e-be04-ad2bdbecd8cb.png">

**Figure 3**: This heatmap showcases the density of bike rides by weekday per hour, categorized by gender.

_____

As can be seen in the figure above, the bike-sharing service's ridership is highest amongst males during the rush hours of the day when people are going to or coming back from work. Consequently, the bike-sharing service is best targeted towards working-age males in Des Moines who use a bike to commute to and from work. Female ridership is also at its highest during rush hours but is significantly lower than male ridership during those time periods.

### User Trips by Gender by Weekday
_____

<img width="1147" alt="6_heatmap_user_gender" src="https://user-images.githubusercontent.com/80941606/193877779-93979457-cd12-4a55-ac12-688191ee8537.png">

**Figure 4**: This heatmap showcases the user trips throughout the week categorized by gender.

_____

As can be seen in the figure above, bike ridership is highest amongst subscribing males mostly during the weekdays in New York City. This means that males in cities may be more likley to use the ride-sharing service as compared to females. Additionally, the bike ride-sharing service seems to be most popular amongst subscribers during the weekdays which may be a consequence of riders commuting to and from work. Consequently, the ride-sharing service's marketing efforts can be concentrated on selling their services to working-age males in densely populated areas of cities.

### Rider Distribution
_____

<img width="897" alt="1_rider_distribution" src="https://user-images.githubusercontent.com/80941606/193761639-394e1198-d303-4981-b313-31b25992514b.png">

**Figure 5**: This is the rider distribution in New York City.

_____

As can be seen in the figure above, most riders use the bike-sharing service within Manhattan. This means that resources are best allocated in that area of New York City. Consequently, Des Moines may have prospective riders concentrated within a particular area of the city; this is where the most bike-sharing resources can be allocated.


### Bike Repairs
_____

<img width="1053" alt="7_bike_repairs" src="https://user-images.githubusercontent.com/80941606/193761599-943d518a-07c8-4716-be41-b71c39381ddf.png">

**Figure 6**: This heatmap showcases each bike's repair status.

_____

As can be seen in the figure above, there is a gradual gradient of bikes requiring servicing. Consequently, the bike-servicing schedule is predictable so that most bikes can be serviced on a cyclic schedule without causing major disruptions to the bike-sharing service.

## Summary
### Recommendation
In summary, it seems that the prospective bike-sharing service in Des Moines would be best targeted towards working-age males in densely-populated areas, Additionally, since demand for the bike-sharing service is highest during rush hours (i.e. right before and after the work day), most bikes will need to be available for use around these time periods; this means that bikes can be serviced a few hours outside of normal business hours.

### Additional Visualizations
To extract more nuanced information from the dataset to better understand the duration of rides and the ridership demographics, we can create the following vizualizations:
* Trip duration based on the day and gender, and
* Trip duration based on the age and gender.
