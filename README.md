# Amazon-Sales-Insight
This project is similar to a previous project I completed during my work. The primary objective of this project is to gain insight into the sales data of Amazon to understand the various factors that affect sales across different branches. 

#Analysis List:
Product Analysis:
This analysis delves into the dataset to comprehend the performance of various product lines. It identifies the top-performing product lines and highlights areas for improvement.

#Sales Analysis:
This analysis seeks to unveil the trends in sales for different products. Its findings enable us to assess the efficacy of each sales strategy implemented by the business and determine necessary adjustments to drive increased sales.

#Customer Analysis:
This analysis aims to reveal distinct customer segments, purchasing patterns, and the profitability associated with each segment.

#Approach Used

1. Data Wrangling: This initial step involves inspecting the data to detect any NULL or missing values. Data replacement methods are then employed to address any identified issues.

1.1 Build a Database.

1.2 Create a Table and Insert the Data.

1.3 Select Columns with NULL Values: Our database has been designed to enforce NOT NULL constraints for each field during table creation. Therefore, there are no NULL values present in the dataset, as they are filtered out during the table creation process.

2. Feature Engineering: This phase focuses on generating new columns from existing ones.

2.1 Added a New Column Named "timeofday": This column provides insights into sales patterns during different times of the day—Morning, Afternoon, and Evening—facilitating analysis on when most sales occur.

2.2 Added a New Column Named "dayname": This column extracts the day of the week for each transaction, aiding in understanding the busiest days for each branch.

2.3 Added a New Column Named "monthname": This column extracts the month of the year for each transaction, enabling analysis on which months yield the highest sales and profit.

3. Exploratory Data Analysis (EDA): EDA is conducted to address the project's objectives and answer the listed questions.


#Business Questions To Answer:
1. What is the count of distinct cities in the dataset?
2. For each branch, what is the corresponding city?
3. What is the count of distinct product lines in the dataset?
4. Which payment method occurs most frequently?
5. Which product line has the highest sales?
6. How much revenue is generated each month?
7.  which month did the cost of goods sold reach its peak?
8. Which product line generated the highest revenue?
9. In which city was the highest revenue recorded?
10. Which product line incurred the highest Value Added Tax?
11. For each product line, add a column indicating "Good" if its sales are above average, otherwise "Bad."
12. Identify the branch that exceeded the average number of products sold.
13. Which product line is most frequently associated with each gender?
14. Calculate the average rating for each product line.
15. Count the sales occurrences for each time of day on every weekday.
16. Identify the customer type contributing the highest revenue.
17. Determine the city with the highest VAT percentage.
18. Identify the customer type with the highest VAT payments.
19. What is the count of distinct customer types in the dataset?
20. What is the count of distinct payment methods in the dataset?
21. Which customer type occurs most frequently?
22. Identify the customer type with the highest purchase frequency.
23. Determine the predominant gender among customers.
24. Examine the distribution of genders within each branch.
25. Identify the time of day when customers provide the most ratings.
26. Determine the time of day with the highest customer ratings for each branch.
27. Identify the day of the week with the highest average ratings.
28.  Determine the day of the week with the highest average ratings for each branch.



