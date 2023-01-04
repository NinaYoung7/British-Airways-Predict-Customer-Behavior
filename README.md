# British Airways Data Science Project - Predic customer behavior

Submitted by: **NING YANG**

Time spent: **10** hours spent in total

Tools Used: Python


This project is British Airways' data science virtual experience program on Forage.


## Task 1 - Web scraping to gain company insights

Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA. This first task is focused on scraping and collecting customer feedback and reviewing data from a third-party source and analysing this data to present any insights.

I scraped data from https://www.airlinequality.com/.  The reviews data are as below:

<img width="307" alt="image" src="https://user-images.githubusercontent.com/103723722/210658483-83808d4e-bb43-4c1b-8cdd-f38558d9fad8.png">


After data cleaning and tokenization, I performed sentiment analysis, and developed word cloud visuals 


<img width="514" alt="image" src="https://user-images.githubusercontent.com/103723722/210657287-2c9d37e0-b476-4555-a2a6-dac986b96b52.png">


## Task 2 - Predicting customer buying behaviour

This task is to figure out the factors that influence buying behaviour by building predictive models.

I explored the data set and checked the correlations between variables.
I implemented XGBoost & Random Forest classification algorithms  to the customer bookings data set and evaluated the model's performance and output how each variable contributes to the predictive model's power.

<img width="451" alt="image" src="https://user-images.githubusercontent.com/103723722/210661501-5427b3a2-bccb-418f-b6c7-2d1aacf7e34b.png">


![image](https://user-images.githubusercontent.com/103723722/210660924-6259809d-ffc9-4143-bcea-b5bf7dbe04e5.png)

I implemented XGBoost & Random Forest classification algorithms  to the customer bookings data set and evaluated the model's performance and output how each variable contributes to the predictive model's power.


![image](https://user-images.githubusercontent.com/103723722/210663344-e2c7fe4d-c8e5-4f34-90c4-164fb61ff02d.png)

As a result, the 'Purchase_lead' and 'Length_of_stay' are the top 2 reasons. 'Purchase_lead' is the number of days between travel date and booking date.
Based on that, we can create new promotion startegy like proving discount if people book the flights 60 days prior to departure to increase the bookings. Or we can sent alerts to the passengers haven't completed the booking processes.

Flight hours is the third importance factor, we can also send promotion and an alert to those customers who start booking but don't finished.


    Copyright [2023] [NING YANG]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

