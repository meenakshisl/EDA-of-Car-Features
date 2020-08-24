# EDA-of-Car-Features
#### Project for NEO Olympiad.

This repo contains the progress of my work while working on the project along with some of the practice code snippets I tried while taking the training.

## Project Title
Exploratory Data Analysis of Car Features

## Objective
The objective of the project is to do data pre-processing and exploratory data analysis of the Kaggle dataset of car features and predict the future price of a car from the given set

### Data Description
|Column name|Description|
|---|---|
|Make|Car Make |
|Model|Car Model | 
|Year|Car Year (Marketing)|
|Engine Fuel Type| Engine Fuel Type|
|Engine HP | Engine HorsePower (HP)|
|Engine|Cylinders Engine Cylinders|
|Transmission Type| Transmission Type |
|Driven_Wheels| Driven Wheels |
|Number of Doors| Number of Doors|
|Market Category| Market Category |
|Vehicle Size| Size of Vehicle |
|Vehicle Style| Type of Vehicle |
|highway| MPG Highway MPG |
|city mpg| City MPG|
|Popularity|Popularity (Twitter)|
|MSRP |Manufacturer Suggested Retail Price|

## Steps

1.  Import the dataset and the necessary libraries, check datatype, statistical summary,
shape, null values etc.
2. Are there any columns in the dataset which you think are of less relevance. If so, give reasoning and drop them.
3. Rename the columns "Engine HP": "HP", "Engine Cylinders": "Cylinders", "Transmission
Type": "Transmission", "Driven_Wheels": "Drive Mode","highway MPG": "MPG-H", "city
mpg": "MPG-C", "MSRP": "Price"
4. Check for any duplicates in the data, check for null values and missing data and remove
them.
5. Plot graphs of various columns to check for outliers and remove those data points from the
dataset.
6. What car brands are the most represented in the dataset and find the average price among
the top car brands.
7. Plot the correlation matrix and document insights.
8. Perform EDA and plot different graphs and document findings (Try to see how other
variables affect the price of the car)
9. Split the dataset into 80 and 20 ratio and build a machine learning model with
Price as the target variable
10. Try different algorithms and check their performance over metrics like R
square, RMSE, MAE etc and document findings
