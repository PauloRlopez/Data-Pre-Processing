# Data-Pre-Processing
---


![alt images](https://github.com/PauloRlopez/Data-Pre-Processing/blob/master/images/analysis-1841158_1920.jpg)


# Data Overview
---

Description:

- A driver uses an app to track GPS coordinates as he drives to work and back each day. The app collects the location and elevation data. Data for about 200 trips are summarized in this data set.

Data source:

- Date of travel
- StartTime: when getting into the car
- DayOfWeek: the day name
- GoingTo: direction of travel
- Distance travelled in kilometers
- MaxSpeed: fastest speed recorded (all trips are on the 407 highway for some portion)
- AvgSpeed: the average speed for the entire trip
- AvgMovingSpeed: the average speed recorded only while the car is moving
- FuelEconomy: a rough estimate of fuel economy (it is inaccurate)
- TotalTime: duration of the entire trip, in minutes
- MovingTime: duration when the car was considered to be moving (i.e. not counting traffic delays, accidents, or time while the car is stationary)
- Take407All: is Yes if the 407 toll highway was taken for the entire trip. I try to avoid taking the 407, taking slower back routes to save costs. But some days I'm running late, or just lazy, and take it all the way.
- Comments

Data Shape: 

- 205 rows and 13 columns

# Steps for Pre-Processing 
---

1. Get the Dataset
2. Importing Libraries
3. Importing the Dataset
4. Dealing with data types
  
5. Deal with Missing Data or other issues
6. Deal with Categorical Data
7. Save the file

# Credits

Kevin Dunn uploaded the original data @ [OpenMV.net](https://openmv.net/info/travel-times) Datasets.

**Thanks**
