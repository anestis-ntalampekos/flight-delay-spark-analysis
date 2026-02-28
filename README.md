# Flight Delay Analytics with Apache Spark

This project analyzes flight delay data using Apache Spark (PySpark) in a cloud environment.

The goal was to process flight records, clean the dataset, and identify routes with the highest average departure delays.

## Technologies
- Python
- Apache Spark (PySpark)
- Google Colab
- Data Analysis

## Dataset
The dataset used contains flight delay information from the file:

flights_2000.csv

It includes approximately 2000 flight records with fields such as:
- Origin Airport
- Destination Airport
- Departure Delay
- Cancelled Flights

## Data Processing
The following steps were implemented:

1. Dataset loading using Spark DataFrame
2. Data cleaning and filtering
3. Removal of cancelled flights
4. Handling missing values
5. Aggregation of delays per route
6. Identification of routes with the highest average delays
7. Export of results

## Results
The analysis produced the Top 10 routes with the highest average departure delays.

## Project Structure
notebook/
    flight_delay_spark.ipynb

## Environment
The project was executed in Google Colab using PySpark.
