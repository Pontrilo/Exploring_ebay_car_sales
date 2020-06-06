# Exploring_ebay_car_sales

- Used a dataset of 50,000 points from used car listings on Ebay. The data we are using is a somewhat cleaned dataset provided by Dataquest as an improvement on the original dataset uploaded to Kaggle.
- Using Pandas, read in and explored the initial data using built in functions like; info(), head(), describe() and value_counts().
- Cleaned the data using vectorised functions. Dropping columns with .drop(), removing unneeded string characters with the str.replace() function and converting column types using astype().
- After renaming some columns with rename(), used unique().shape() to sum the unique items of the column before exploring the values with value_counts().
- Performed some column filtering by using inequalities to create Boolean masks.
- Corrected date data using the between() function to create Boolean masks.
- Created loops that investigated columns and returned dictionaries to investigate popular car brands.
- Created a separate dataframe to compare the mean price against mean mileage to identify potential trends.
- This project was an exploration into the potential of the Pandas built in functions for analysis and to test my understanding of the dataframe and series functions.

