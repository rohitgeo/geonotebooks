### 01 Utah Motor Vehicle Collisions - exploratory data analysis

Exploratory data analysis of the crash data

### 02 Dataset survey and exploration

Survering available datasets and their properties for selecting the right datasets to combine for analysis.

### 03 Assign crashes to road segments

Combine the crash data with the safety index layer which has the road segment information. It also provides several attributes like safety index that can be useful as features.

### 04 Get Active MesoWest Weather stations

Gets the list of active weather stations in Utah

### 05 Fetch Hourly Weather

Fetch the hourly weather from active Mesowest stations


### 06 Combine Annual Weather

Combines the fetched hourly weather for the different stations into hourly weather for each year


### 07 Find nearest weather station to crash locations

Finds the nearest weather station to crash locations and merges the nearest weather Station ID

### 08 Class balancing - create negative samples

For each crash incident, creates 3 negative samples. In one,  the hour is different, in another the day, and in the third the road segment.


### 09 Merge weather and create yearly samples

Joins and shuffles the positive and negative samples, merges the weather data, and writes out samples for each year.

### 10 Fit classification models

Fit deep neural network and random forest classifiers on data.
