## Swiggy-data-analysis

## Introduction
In the ever-evolving food delivery landscape, understanding the dynamics of popular platforms like swiggy.com is crucial for making informed decisions. By employing web scraping techniques to gather data on restaurant ratings, cuisine, and pricing, valuable insights and recommendations can be generated. This analysis not only aids in evaluating the viability of opening a remote kitchen in Bangalore but also offers broader industry insights, including area-wise distribution of restaurants, affordable and upscale options for various cuisines, and the prevalence of different culinary offerings.

## Problem statement
To collect data from the food delivery platform SWIGGY using web scraping and analyze the data to generate insights and recommendations for opening a remote kitchen in Bangalore, as well as provide broader industry insights such as area-wise restaurant distribution and affordable and upscale options for various cuisines.

## Data Description

1.CSV FILE: The first CSV contains data on restaurants, including columns such as restaurant ID, restaurant name, restaurant link, price for two people, ratings, and the cuisines they serve. This table provides an overview of the restaurants available on the food delivery platform.
The second CSV contains information on dishes offered by the restaurants. It includes columns such as restaurant ID, restaurant name, dishes, cuisines, and the price of each dish. This table provides detailed information about the specific dishes offered by each restaurant.

2.Jupiter notebook files: This folder contain IPYNB file where web_scrapping code are there which were used to scrap the data from Swiggy(Bangaluru).

3.SQL Server File : This folder contain SQL query that perform to generate insights.

## Scrapping the data
![part_1](https://github.com/avi251295/swiggy-data-analysis/assets/120267658/49a31185-4fa7-4b76-888e-690dd781afaa)
![part_2](https://github.com/avi251295/swiggy-data-analysis/assets/120267658/c01e34e5-20ba-441f-9b40-a754d300b912)
![part_3](https://github.com/avi251295/swiggy-data-analysis/assets/120267658/9f9bf3bc-794e-4922-ad0b-afd725ebf490)

## insights 
1. Areawise Restourant Distribution
2. Number of Restaurant above 1k rating in different location
3. Number of restourant for each cuisine
4. Most Popular Resturant by rating
5. Location of less rated restourant

## Methodology

The methodology for creating a dashboard based on the provided CSV data can involve the following steps:

1. Data Collection: Extract the data from the CSV files and load it into a suitable data analysis tool SQL.

2. Data Cleaning and Transformation: Clean the data by handling missing values, removing duplicates, and transforming it into a suitable format for analysis. Perform any necessary data preprocessing tasks.

3. Data Analysis: Utilize descriptive and exploratory data analysis techniques to uncover patterns, trends, and insights within the data. Calculate summary statistics, visualize data distributions, and explore relationships between variables.

4. Dashboard Development: Develop a dashboard using a suitable visualization tool such as EXCEL, Power BI. Design the dashboard to effectively communicate the key insights and recommendations derived from the data analysis, utilizing appropriate charts, graphs, and interactive elements.


## Dashboard Creation

![Screenshot (57)](https://github.com/user-attachments/assets/1f7086c1-1a3e-4379-99f9-352a61c8f4e6)

This dashboard provides a comprehensive overview of the food delivery platform's data. It showcases the top 5 locations with the highest count of restaurants, allowing users to identify popular areas. Additionally, it highlights the top 5 restaurants for each type of cuisine, aiding in the exploration of diverse culinary options. The treemap visualization illustrates the distribution of restaurants, while the location-wise breakdown of restaurants with reviews exceeding 1000 offers insights into highly reviewed areas.

## Visulization
![Screenshot (56)](https://github.com/user-attachments/assets/757921c1-6107-4a53-afd6-41179ea4aab6)

Indiranagr restaurants is a top restaurant in sum of rating count followed by other locations.

![Screenshot (54)](https://github.com/user-attachments/assets/a407177d-1afd-4195-b22e-0a1ed1aa82af)


Beverages are the most orderd followed by Desserts, Snacks, South Indian & Chineses respectively.

![Screenshot (53)](https://github.com/user-attachments/assets/14b6b993-41ad-4a7f-ae06-2d0f6a58d91d)

Most restaurants are listed in Indiranagar followed by Layout, Koromangala, Jayanagar, Basvanagudi respectively.


## Challenges Faces
1.Collecting data from single platform for different restaurants was time consuming.
2.Getting data well and consistent across different  sources requires careful data cleaning and processing.

## Lesson Learned
1.Web Scrapping can be effective tool for collecting larger amount of information but it requires careful consideration of legal & ethical issues.

2.Data Cleaning & processing are important steps in data analysis, investing time & effort can prevent many headaches.

3.Good data visualization is essential to convey understanding to stakeholders or clients.

## Future Scope
1. Expand analysis in other region
2. Incorporate external factors: External factors such as weather, events, or holidays
3. Collaborate with restaurants or food delivery platforms
4. Incorporate more data sources






