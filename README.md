Exploratory Data Analysis (EDA) Project

EDA for Car Price Prediction Model

***
# Descriptions :
- A ``.json`` file containing a dataset consisting of 15919 rows and 54 columns is provided.
- This dataset, scraped from the on-line car trading company in 2019, contains many features of 9 different car models.
- The features (variables) of this dataset are too messy and distored.

# What is expected?
- Read the ``.json`` file and assign the dataset into a ``DataFrame`` using ``pandas``.
- Implement all aspects of the **EDA process** to the dataset.
   - Fix corrupted data formats,
   - Handle with outliers and missing values,
      - Domain (automobiles) knowledge is important.
      - Always use the internet to do the research that you need.
      - Think carefully to decide whether a data is outliers or not. Examples :
         - There is no conventional car model with an average fuel consumption of 1 - 1.5 liters per 100 km. 
         - Or you need to know that it cannot be a 300 euro car. 
         - Or if there is only one car with 3 doors out of the 15919 cars, this is what you should pay attention to and examine.
   - Drop the columns / rows you determined unnecessary as a result of your analysis,
   - Use visualization tools while doing all these processes.
- As a result, get the dataset ready to provide an appropriate input to the ML models.
- Save cleaned dataset into a ``.csv`` file.
