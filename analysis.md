## Bike Sharing Case Study – Excel

*Exploratory analysis and business insights using Microsoft Excel.*

### Introduction

#### * Context of the problem
This case study analyzes bike-sharing usage patterns to identify trends and opportunities for business improvement.

Cyclistic is a bike-share company in Chicago, with 2 pricing plans: "Casual riders" and "Annual members". Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

The goal of the company is to convert casual riders into annual members due to Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders.

#### * Objective of the analysis
The objective of the analysis is to identify trends and patterns in order to understand the needs of the cyclistc riders and design strategies to convert casual riders into annual members.

#### * Key questions
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships? 
3. How can Cyclistic use digital media to influence casual riders to become members?

### Data set description
* **Data Provider:** Motivate International Inc.  
* **License:** Public open data (as provided in the Google Data Analytics Certificate)  
* **Usage:** Educational and analytical purposes only
* **Number of records:** 426,887 records
* **Main columns:** ride_id, started_at, ended_at, member_casual.
* **Time period:** 2020

The datasets used in this case study were provided as part of the **Google Data Analytics Professional Certificate** for educational purposes.

The data is derived from public bike-sharing trip data made available by **Motivate International Inc.**, under an open data license.  
The company name *Cyclistic* is fictional and was used solely for the purposes of this case study.

Due to data privacy considerations, all personally identifiable information (PII) has been removed from the dataset.  
As a result, individual riders cannot be identified, and certain analyses are outside the scope of this study.

### Data Cleaning & Processing

A "ride_length" column was created, which calculated the duration of every ride by substracting the column started_at from the column ended_at, and formated as [hh]:mm:ss This format allow us to see the time accumulated for rides with more than 24 hours.

![](images/calculo_ride_length.png)
