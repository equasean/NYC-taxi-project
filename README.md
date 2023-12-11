# NYC Taxi Data Analysis Project

## Overview
Thanks for viewing my NYC Taxi Data Analysis Project. As part of my Google data analysis course, I undertook an in-depth exploration of New York City's taxi service data provided by the Taxi and Limousine Commission. This project aims to uncover insights into taxi usage patterns, fare distributions, and tipping behavior across different payment methods and passenger counts.

## Data
The dataset has records of yellow taxi trips in New York City for the year 2017. It includes various attributes such as pickup and drop-off dates/times, trip distances, fare amounts, tip amounts, and payment types.

## Tools Used
- **Python**: For data manipulation and analysis.
- **Pandas**: To organize and prepare the data for analysis.
- **Tableau**: For data visualization and creating an interactive dashboard.

## Key Steps
1. **Data Loading**: Importing the taxi trip data into a Pandas DataFrame.
2. **Data Cleaning**: Identifying and handling missing or anomalous data entries.
3. **Data Exploration**: Analyzing trip distances and total amounts to identify outliers and trends.
4. **Payment Analysis**: Investigating the distribution and average amounts of different payment types.
5. **Tipping Behavior Analysis**: Calculating the average tip amount by payment type and by passenger count for credit card payments.
6. **Vendor Comparison**: Counting trip occurrences and comparing the average and most common fare amounts by vendor ID.

## Findings

Here are my **Key Insights:**

**Payment Types:**

- The majority of trips are paid for using credit cards, followed by cash. Few trips resulted in no charge or disputes.

- The average tip for trips paid for with a credit card is approximately $2.73, while cash tips aren't recorded in the system (average is $0.00).

---

**Vendor Analysis:**

- Two vendors are represented in the dataset, with both having a very similar average total fare.

- The dataset contains information on different passenger counts, with a noticeable number of rides having more than 2 passengers.

---

**Amounts and Distances:**

- When sorting by trip_distance, some values seem unusually high, suggesting potential outliers or data entry errors.

- In terms of total_amount, there are both unusually high and negative values, which require further investigation.

--- 

**Potential Variables for Predictive Modeling:**

- Based on the analyses, trip_distance and total_amount could be the two most helpful variables for building a predictive model for NYC TLC. These variables capture key information about the trip's length and the fare, which are crucial for predicting outcomes like total fare or tip amount.

- Additionally, understanding patterns in payment_type could be valuable, especially if NYC TLC wants to promote one payment method over another or assess tipping patterns.

--- 

## **My Conclusion:**

- Before building predictive models, it's essential to handle potential outliers, especially in columns like trip_distance and total_amount.

- Given the discrepancies observed in the dataset (e.g., high fares for zero-distance trips), data quality checks and preprocessing are crucial.

- For a more in-depth analysis, considering temporal patterns (e.g., time of day, day of the week) could provide additional insights and enhance predictive modeling.


Thank you for checking out my project!
