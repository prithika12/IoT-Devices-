# IoT Devices - Time Series Plots


## Context

#### **IoT devices have been around for quite a while now. They are used to collect data through different kinds of sensors such as Motion sensors: These use a visual sensor to detect a change in apparent temperature of surroundings or when someone comes in the field of view of a camera. Heat sensors: These are used in trucks which carry perishable goods like fish and milk where changes in a temperature lower the shelf life of the produce. These are also used to detect forest fires.**

#### Vibration sensors: These are used in car crash tests and detecting if someone is trying to cut a tree.

#### A lot of people are using smartwatches and fitness watches to track their daily physical activities, calories burnt, average resting heart rates, sleep cycle so that they lead a fit life. Such wearables are equipped with laser sensors to collect data.

#### Heat Index (temperature + humidity) is one common data recorded on these IoT readers. The frequency of the upcoming data is very fast. The sensor reads hundreds to millions of data per second. There is a huge and versatile application of this data in real-world like agriculture, weather forecasting, soil monitoring and treatment, enterprise maintenance etc.

#### Heat stress index of India

![image](https://user-images.githubusercontent.com/78560363/230477120-90c85909-04e9-4c31-8342-9879789bdc32.png)

Problem Statement
Put yourself in the shoes of a quality analyst whose task is to test the efficacy of new IoT devices. You need to create time-series plots for daily temperature variation for the given duration and find any inconsistencies in the temperature readings (if there are any).

In case the data collected through the device is correct, find the percentages of the yellow, orange and red zones.

Data Description
This dataset contains the temperature readings from an IoT device installed outside and inside of an anonymous room (labelled as admin room) to test the device. The readings were taken between 11 January 2018 and 10 December 2018. Additionally, it was uninstalled or taken down quite frequently during the entire reading period. There are 5 columns and 97,605 rows in the dataset.

id - unique IDs for each reading

room_id/id - room id in which device was installed (inside and/or outside). In this dataset, only Room Admin label is used as a room_id for example purpose.

noted_date - date and time of reading

temp - temperature readings

out/in - whether the reading was taken from a device installed inside or outside of the room?

Here's the dataset link:

https://student-datasets-bucket.s3.ap-south-1.amazonaws.com/whitehat-ds-datasets/iot-devices/IoT-device.csv

Things To Do
What is the trend in the variation in daily indoor and outdoor temperatures?

What is the trend in the variation in monthly median indoor and outdoor temperatures?

Find out the hottest and coldest month(s).

Find the maximum and minimum temperatures recorded for each month.

Find the hottest and coldest days for each month along with the temperatures.
