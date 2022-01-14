# [Project 2 : The Sakila Database Analysis (DVD Rentals)](https://github.com/davidgomezpr1/Python_Exploratory_Analysis/blob/Portfolio_Projects/The_Sakila_Database_Analysis.ipynb)
![](https://docs.oracle.com/cd/E17952_01/workbench-en/images/wb-sakila-eer.png)


## Business Request

The Sakila DVD rental chain hired me as a freelancer to help them analyze their business. They asked me a series of very specific questions about the rentals:

1. What is the mean of rental duration for all films?
2. What is the most common rental duration?
3. What is the most common rental rate?
4. How is the replacement cost distributed?
5. How many films of each rating does the store have?
6. Does the film replacement cost vary depending on film rating?
7. Give us the rental period in days.
8. How are the rental days distributed?
9. What is the highest daily rental rate for the films?
10. What are the titles of the 5 films with the lowest daily rental rate?
11. What are the titles of the 3 films with the highest daily rental rate?
12. How many rentals were made in Lethbridge city?
13. How many rentals were made in Woodridge city with a rental duration higher than 5 days?
14. How many rentals were made at the store with id 2 or with a replacement cost lower than 10.99 USD?

## Overview

- Importing the Sakila Database to Python.
- Importing the desired Pandas dataframe. Setting the index and parsing 
dates for better data handling.
- Exploring the dataframe.
- Data cleaning to drop any `null` values, if deemed desirable. 
- Exploratory analysis of the data:
    - Mean of the `rental_duration`.
    - Most common `rental_rate`.
    - Distribution of the `replacement_cost` associated with the films.
    - Number of films per rating, and their associated `replacement_cost`.
    - Creation of a calculated column `rental_days`, that will show the rental duration in days.
    - Distribution of the `rental_days`.
    - Various analysis of the `daily_rental_rate` (e.g. highest `daily_rental_rate`, 
    list of films with the lowest `daily_rental_rate`, etc.)
    - Various analysis of rentals in different cities.
    
## Conclusions

- The Business request was efficiently handled, with all requested insights and providing additional supporting charts.
- The client was able to interpret the analysis and, as a result, decided to change the rental prices of certain titles, such as King Evolution and Minds Truman, and consider raising the lower rental rate by 50 cents, to a total of 1.49 USD.
    
