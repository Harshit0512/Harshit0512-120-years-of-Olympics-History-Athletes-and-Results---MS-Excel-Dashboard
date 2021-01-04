# 120 years of Olympics History Athletes and Results MS Excel Dashboard: Project Overview

## Introduction
* This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
* This data set is from Kaggle site [[Dataset](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)]
* This dataset provides an opportunity to ask questions about how the Olympics have evolved over time, including questions about the participation and performance of women, different nations, and different sports and events.
* Did **Exploratory Data Analysis (EDA)** and **Feature Selection** To get bettter results.
* Did **Data Analysis**
* Built a **Dashboard** for this dataset using **MS Excel**.
* **Note:-** The Winter and Summer Games were held in the same year up until 1992. After that, they staggered them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, and so on. A common mistake people make when analyzing this data is to assume that the Summer and Winter Games have always been staggered.

## Resources Used
* **Ms Excel 2016**
* **pivot table, pivot charts, slicers, hyperlinks**

## Data
*	ID - Unique number for each athlete
*	Name - Athlete's name
*	Sex - M or F
*	Age - Integer
*	Height - In centimeters
*	Weight - In kilograms
*	Team - Team name
*	NOC - National Olympic Committee 3-letter code
*	Games - Year and season
*	Year - Integer
*	Season - Summer or Winter
*	City - Host city
*	Sport - Sport
*	Event - Event
*	Medal - Gold, Silver, Bronze, or NA

## Objectives
*	How Seasons affect the countries performance in Olympics.
*	Which Country shows domination in which sport by winning medal.
*	What are the total number and percentage of female and male won a different medal in an Olympics according to season, year or countries.
*	Does hosting an Olympic in a particular city affect the performance of country.
*	How seasons affect the player’s performance in an Olympics.
*	Does age plays an important role in winning a medal.
*	Which country shows domination in which event by winning a medal.
*	What are the total number and percentage of female and male participated in an Olympics according to season, year or countries.
*	Performance of a country according to year.
*	Top countries and athletes who won medal according to year, sex( female or male), sports, events or seasons.

## Data Cleaning
* Fill the NaN values of Age, Height and Weight with the **Average** of that respective column.
* Remove the **ID** column as it is not that useful to our analysis.
* Made a new column for **country**.
* Gave the proper data format to some columns.

## EDA and Feature Selection Results
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Chances%20to%20win%20medal%20w.r.t%20height.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Countries%20Performance%20according%20to%20Seasons.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Countries%20Performance%20according%20to%20city.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Countries%20Performance%20according%20to%20year.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Percentage%20of%20winning%20medal%20w.r.t%20age.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Teams%20Contribution%20to%20Countries%20Medal%20Tally.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Top%20Countries%20by%20winning%20medals.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Top_Athletes.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Total%20Domination%20by%20winning%20gold.png)

## Dashboard building

### Header of the Dashboard
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Starting%20Header.png)
![alt text](https://github.com/Harshit0512/Harshit0512-120-years-of-Olympics-History-Athletes-and-Results---MS-Excel-Dashboard/blob/main/EDA%20Results/Full%20header.png)

**Note** - As a file is greater than 25mb I had converted the file in two zip files. One have dashboard and other have pivot table and charts. You have to download both the files then only it will work otherwise it wll not work on your system.
