# Analysing-and-Classifing-PAMAP-Dataset
##  Problem Statement
To develop a software which can determine the amount and type of physical activity carried out by an individual we need to analyse the dataset to answer these questions:

For the same person can we distinguish the difference between the activities?
Do people have similar measurements while doing the same activity ?
In case different people have different behaviour for the same activity, do we have enough data to build a model for every person based on their history?
Are there more insightful features that needs to be created?
The results can help making a software that distiguish the intensitiy and duration of the activities an individual is doing, send daily/weekly remminders to do more of a specific category, send motivation and encouragement in case of exceeding the goals.

## Data Description
The dataset contains data of 18 different physical activities (such as walking, cycling, playing soccer etc) performed by 9 subjects wearing 3 inertial measurement units (IMU) and a heart rate monitor. This data is stored in individual text files per subject. Each row in each file represents one reading and contains 54 attributes (including timestamp, activity ID, heart rate and IMU sensory data).. Synchronized and labeled raw data from all the sensors (3 IMUs and the HR-monitor) is merged into 1 data file per subject per session (protocol or optional), available as text-files (.dat).

## Actionable Plan
For different ages, there are recommended physical activity guidelines including duration and intensity for different ages to achieve optimal health. They can be divided into 5 categories: Sedentary, Light, Moderate, Vigorous, and Very vigorous.
There is a possibility of building a software solution that accurately distinguishes between the different activities without any need of a large history for the specific customer.
Body parts temperatures are correlated which means, we don't need all of these sensors to reach an accurate model.
The same conclusion for every sensor’s different orientation, we can use one axis and it's a good representation of the remaining two.
