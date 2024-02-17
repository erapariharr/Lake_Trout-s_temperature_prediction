# Lake_Trout-s_temperature_prediction

Problem context
Lake monitoring provides important information for environment protection and pollution identification, such as temperature/thermal monitoring. In this Kaggle task, using thermal sensor data for Late Trout, we are asked to predict/estimate the temperature at a certain depth.

Dataset
 Lake Trout’s temperature data during the period of Apr 20th, 2012 - Apr 19th, 2018. The lake has multiple sensors at different depths, and these sensors measure temperatures multiple times a day. the dataset has date-time, depth and the corresponding temperature at this depth and time point. Therefore, you will see the following columns:
Date_time representing the time stamp 
Depth_m representing the depth in meters
Water_Temp_C representing the temperature in Celsius

In addition, we also have the lake’s temperature data at all depths except 10.5m during Apr 20th, 2018 - Apr 19th, 2019.

Task
We need to predict the temperature of Trout Lake at depth 10.5 m during Apr 20th, 2018 - Apr 19th, 2019, at 1 hour intervals starting from 00:00:00. 

Files for task
For this task, we have two files:
Trout_training.csv which contains the lake temperature data during the period of Apr 20th, 2012 - Apr 19th, 2018. 
Trout_testing_features.csv which contains the lake temperature data during the period of Apr 20th, 2018 - Apr 19th, 2019 at all depths except 10.5m. 
