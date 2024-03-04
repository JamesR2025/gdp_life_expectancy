# GDP versus Life Expectancy

## Introduction

This project sought to explore if there was any correlation between GDP and life expectancy.
I analyzed the United States, Zimbabwe, Mexico, Chile, Germany and China. 
With this variety of countries, I was able to come up with conclusion I felt accuratly reflect the truth.

## Data

I used data found on Codecademy, which was taken from the World Health Organization and World Bank. 
The data had no missing values, which made the process of analysis much easier

## Usage

For this project, I used Jupyter Notebook, Seaborn, and Pandas. 

## Analysis

My procedure went as follows:

1. I first check for any missing data, of which I found none.
2. I created a boxplot for each country in order to analyze the range of GDP's.
3. I found that China had the largest range, though the United States far surpassed everyone.
4. I used seaborn to create line plots of GDP for each country over time.
5. Though I was not satisfied, I used a for loop in order to create subplots for each country in order to analyze any dips unique to the country.
6. I found that in between 2008 and 2009 there was a dip in GDP.
7. I wanted to check if there was any correlation in that dip to Life Expectancy. I found that only Mexico and Chile experienced a dip in LE during those years.
8. I used seaborn scatterplot and regplot to explore GDP versus Life Expectancy. As expected, there was a positive corelation in each country.
9. I used boxplots to analyze the range of Life Expectancy for each country. I found Zimbabwe had an exponential increase in ages compared to other countries.


## Conclusion

- There is a positive corelation between GDP and LE for every country.
- There was a slight recession (GDP) during the years 2008 and 2009.
- Zimbabwe had the largest change in both GDP and LE, both of which were correlated.

