## Mid Term Project carried out during Data Science course at Flatiron School, London in January - March 2019. 

### Summary:

With this project, I started exploring a dataset to uncover some initial insights.

The flat data file that I used is available on Kaggle and contains data from traffic accidents occurred in Barcelona city in 2017. 

### Goals: 

The main goal is to perform an initial exploratory data analysis (EDA) as the beginning for my final project where to apply a linear regression model to produce some useful predictions (please refer to the final project available here https://github.com/JaumeL/Final_Project)

### Techniques:

I have broken down the code into functional chunks and commented it appropriately.

I started importing the required libraries. 

I imported data to a pandas dataframe and cleaned null values to start working with it. 

I checked the shape, columns, index and data types at the dataframe.  

I used the ‘Group By’ built-in function as queries with different aggregate functions and sorting values to get some insights about when accidents’ severity is worse and in which areas severity is mainly concentrated. To visualise that, I have incorporated different visualisations, using appropriated labels and titles for the plots, redefining colours and styles while plotting the data. Furthermore, I created a map of Barcelona and plotting accidents’ geolocation with Folium.

In a first attempt to find out a bit more about correlations, I plotted a matrix of correlations along with a heatmap. Apparently, there aren't so many correlations betweem the variables available in this dataset.    

### Results:

I have defined a problem and have at least a preliminary analysis for this question: 

-	Is it possible to predict the number of victims per accident occurred? 

You will find a possible answer to that question at the final project: https://github.com/JaumeL/Final_Project   
