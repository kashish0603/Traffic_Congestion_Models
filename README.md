# Traffic_Congestion_Models

The Dataset includes measurements of traffic congestion across 65 roadways from April to September of 1991.<br>
- row_id - a unique identifier for this instance<br>
- time - the 20-minute period in which each measurement was taken<br>
- x - the east-west midpoint coordinate of the roadway<br>
- y - the north-south midpoint coordinate of the roadway<br>
- direction - the direction of travel of the roadway. EB indicates "eastbound" travel, for example, while SW indicates a "southwest" direction of travel.<br>
- congestion - congestion levels for the roadway during each hour; the target. The congestion measurements have been normalized to the range 0 to 100.<br>

   ![giphy](https://user-images.githubusercontent.com/96779634/158398946-f2521c41-53eb-406f-b330-7d5da94eb5c8.gif)


# Objective
- Exploratory Data Analysis (EDA) to analyzing data sets to summarize their main characteristics, often with visual methods.
- Extensive feature engineering and modeling.

# Overview

We’ve all been there: Stuck at a traffic light, only to be given mere seconds to pass through an intersection, behind a parade of other commuters. Imagine if you could help city planners and governments anticipate traffic hot spots ahead of time and reduce the stop-and-go stress of millions of commuters like you.<br>
This is a traffic congestion prediction model that compares the accuracy among 3 different models:
- Support Vector Machine Regressor
- Decision Tree Regressor
- Random Forest Regressor
