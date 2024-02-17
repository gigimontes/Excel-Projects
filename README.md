# Project #1: Bike Sales Project 🚲💰

## Project Overview
I analyzed sales data about Bikes 

## Data Source
I retrieved the data from AlexTheAnalyst Github's "Excel_tutorial" respitory. To go to the respitory click here: [Excel Tutorial Respitory](https://github.com/AlexTheAnalyst/Excel-Tutorial/tree/main)

## Tools used in Project
**Excel** 
    - To download the Excel spreadsheer click [here](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)

## Data Cleaning/Data Preparation
  - Removed Duplicates 
  - Find and Replace
        - I changed the M and F from the Gender column to 'Male' and 'Female' along with changing the M and F from the Marital Status Status to ' Married' and 'Single' so it is easier to interpret.
  - Nested IF
  - The data shows the Age range under the Age column as a single option (ex. 23, 24, 25), and want to show it as a range so it can be easier to read when building the data visualization. Therefore I used a Nested IF to put the ages in ranges.
Formula Used: =IF(L15>54,"Old",IF(L15>=31,"Middle Age",IF(L15<31,"Adolescent","Invaild")))

## Exploratory Data Analysis 
The questions that were asked to help me with my analysis is: 
- What age bracket bought the most bikes?
- What is the average income of the consumer?
- What commute distance are people more willing to purchase a bike?

## Data Analysis

I analyzed the data through several Pivot tables

## **Dashboard**

![image](https://github.com/gigimontes/Excel-projects/assets/143570053/d4251f66-358b-4ead-80cf-61ef91659b84)

## Results
The results found in the data are:

  - The age bracket with the highest bike purchases is middle aged people who are in the age range between 31-54. People in the middle aged bracket were also the highest in not purchasing a bike.
  - The average income for female bike purchasers is 53,440 a year while for males it's 60,124 a year. Overall the higher the salary, the higher the chance of a purchase.
  - Consumers were more likely to purchase a bike if the commute travel was between 0-2 miles. On the contrary, consumers were more likely to not go through with the purchase if the commute was between 5 miles or more. 

## Recommendations
  - I would focus on marketing towards the age range for people in their Adolescence to middle ages. 
  - I would recommend having a Uni-sex bike section that suits both men and women, men section, and women section that has 3 
    pricing brackets each. The pricer the bike the more features it has. This way we expand our affordability to more 
    consumers. 
  - I would market towards people who live in cities or suburbs due to the space dedicated for bike routes. Destinations are 
    more likely to be closer to each other compared to rural areas.

