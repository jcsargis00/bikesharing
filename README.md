# NYC Citibike Bikesharing Study
#
## Analysis
#
Two entrepreneurs are looking into using the NYC Citibike bikesharing business model to open a similar operation 
in Des Moines.  Data can be analyzed on bike usage by time of day, day of week, gender, user type, start and end
points for usage, time period for usage and bike maintenance times.
Data from the NYC Citibike bikesharing company has been analyzed and put together with Tableau Visualization software.
To get started, trip duration data was converted from an integer to a datetime in seconds.  The new format was saved
into a csv file to be used for the visualization examples.
### Overview of the statistical analysis
Initial visualizations are graphs depicting checkout time for all users and checkout time by gender
#
Checkout times for all riders are shown below:
#
![checkout time](https://github.com/jcsargis00/bikesharing/blob/main/images/checkouttimesusers.PNG)
#
To determine if bikesharing is preferred by one gender over another, checkout times by gender with length of time bike is used is displayed below:
#
![gender checkout time](https://github.com/jcsargis00/bikesharing/blob/main/images/checkoutbygender.PNG)
#
These graphs show many more males use the service than females, or riders who did not identify their gender.
#
Do more bike trips take place by weekday at certain hours?  A graph of the number of bike trips by weekday for each hour of the day as a heatmap is shown below:
#
![heatmap](https://github.com/jcsargis00/bikesharing/blob/main/images/tripsweekdayhour.PNG)
#
Bikes were most popular between 8am and 9am, and 5pm and 7pm during the week, possibly being used for commuting to a 9 to 5 job.  On the weekend, bikes were most popular between 10am and 7pm, likely daylight hours after sleeping in for the weekend.
#
Is gender a factor during certain hours or on certain days? A graph of the number of bike trips by gender for each hour of each day of the week as a heatmap below.
![heatmap by gender](https://github.com/jcsargis00/bikesharing/blob/main/images/tripsbygenderweekdayperhour.PNG)
#
According to the heatmap, more males used the service during the week during commuting hours.  More males and females used the service on weekends between 10am and 7pm, with more riders being male.  From midnight to 6am, usage was low in general.
#
Finally, a heatmap that shows the number of bike trips broken down by gender for each day of the week by each Usertype (customer or subscriber)
#
![trips by gender by weekday](https://github.com/jcsargis00/bikesharing/blob/main/images/usertripsbygenderbyweekday.PNG)
#
Usage was highest by subscriber males, with Thursday as the peak day, followed by Friday for males.  Thursday was also a peak day for females that were subscribers.  Usage by customers was lower across all days and genders.  Usage was higher 
by customers who did not indicate gender than subscribers who did not indicate gender on all days.
#
## Results
# 
Deliverable #1 
#
Data in trip duration column is converted to a datetime datatype with correct time format
#
![convert datatype](https://github.com/jcsargis00/bikesharing/blob/main/images/datatypes.PNG)
#
### The correct time format for trip duration is shown below
#
![trip new format](https://github.com/jcsargis00/bikesharing/blob/main/images/tripdurationconvert.PNG)
### The dataframe was exported as a new file without the index column using the command below:
#
![new csv export file](https://github.com/jcsargis00/bikesharing/blob/main/images/newexportfile.PNG)
#
Deliverable #2
#
See line graphs and heatmaps above.
#
Deliverable #3
#
Story board screen shots, also stored in Tableau Public, see link to dashboard below:
#
[link to dashboard] (https://public.tableau.com/app/profile/joy.sargis/viz/NYCCitibikeAnalysisforDesMoines/NYCCitibikeAnalysis?publish=yes)
#
Story 1
![story1](https://github.com/jcsargis00/bikesharing/blob/main/images/story1.PNG)
#
Story 2
![story2](https://github.com/jcsargis00/bikesharing/blob/main/images/story2.PNG)
#
Story 3
![story3](https://github.com/jcsargis00/bikesharing/blob/main/images/story3.PNG)
#
Story 4
![story4](https://github.com/jcsargis00/bikesharing/blob/main/images/story4.PNG)
#
Story 5
![story5](https://github.com/jcsargis00/bikesharing/blob/main/images/story5.PNG)
#
### Summary
#
* The data shows high activity of the bike sharing service in New York during the month of August 2019.
* The majority of the rides were in Manhattan, taken by male users during morning and evening rush hours. 
* The ratio of male to female riders was approximately 3 to 1

The highest usage was by male subscribers during weekdays at commuting hours (8am to 9am and 5pm to 7pm).  Usage was high by both male and female users on the weekends between the hours of 10am and 7pm, with usage higher among subscribers than users.  The exception was customers on Satuday and Sunday that did not indicate their gender, there was moderate useage by this goup as a customer, but not as a subscriber.

Observations:
* It is possible Citi Bike services are used as transportation by commuting workers.
* The optimum time for bike maintenance is between midnight and 5am
#
Suggestions for creating other visualizations for future analysis:

Analyzing data for different months to determine trends across the year
* Including weather data for usage
* Looking at months where NYC weather data is similar to weather data in Des Moines
* Analyzing demographics of Des Moines potential customers