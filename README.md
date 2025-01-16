# "Cyclistic" bike share analysis Case Study 
This Case Study was completed as part of the Google Data Analytics Professional Certificate.

The scenario involves analysis of the trip data of Cyclistic bike share company.

The company has two models for availing service: individual passes which are called "casual" riders and annual subscriptions called "member" riders.
The company operates in Chicago with around 6000 bicycles at 700 stations.

Maximizing the number of annual members will be key to future growth as it ensures financial sustainability and customer retention. The insights can help devise effective marketing strategies aimed to convert more casual riders into annual members.

### 1. Objective (Ask Phase)
To analyse how annual members and casual riders use Cyclistic bikes differently in order to determine the best marketing strategy to convert casual riders into annual members. 

### 2. Prepare Phase

For this case study I chose 12 data files containing trip data gathered during each month of 2022 (January to December 2022). Data has been downloaded from Motivate International Inc. Local copies have been stored securely on Google Drive and here on Github. Data can be found here https://divvy-tripdata.s3.amazonaws.com/index.html.
It was organised by month, and assumed to be credible since it was compiled and published by the organisation. 

### 3. Process Phase
To organise, process and analyze data R studio was chosen as the main tool. After regularising and importing the data, the first step was to inspect each attribute for anomalies. A new column for trip length (in minutes) was created. Any data that was unnecessary was removed. Each step of the process can be found here: docs/Bike data.Rmd

### 4. Analyse Phase
In this phase, queries were created to uncover trends that were highlighted in the data visualisations.

### 5. Share Phase
Visualisations were created using R studio. You can find them by downloading PowerPoint - "Cyclistic visualizations .pptx"

### 6. Act Phase
Recommendations for the marketing team based on analysis and data visualizations can be found by downloading PowerPoint - "Cyclistic visualizations .pptx"

### Key Findings 

1. In general, 59.7% of riders are members, and 40.3% of riders are casual users.
2. On average, casual riders ride a bike twice longer than member riders (24.07 min and 12.67 min, respectively)
3. For both user types the majority of rides fall into first two categories: "<12 min" and "12-20 min"
4. Ride length for casual riders peaks mid morning through afternoon, especially between 10AM - 2PM, while for members its more consistent
5. Members take more rides during morning (7-8am) and evening (4-6 pm) , casual total number of rides also peak from 4pm to 6pm
6. Both users take longer rides on weekend
7. For both user types rides peak in summer and decline in winter
8. The most popular starting station for casual riders is Streeter Dr & Grand Ave, which is located near the park in Chicago.
9. The top starting and ending station for member riders is Ellis Ave & 60th St which is situated within the University of Chicago

