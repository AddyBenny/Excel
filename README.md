# Excel

I used excel organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

- Using the Excel table provided, I modified and analyzed the data of 4,000 past Kickstarter projects to show some market trends.
- Used conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.
- Created a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.
- Used conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale started at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.
- Created a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.
- Created two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.
- Created a new sheet with a pivot table that analyze initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
- Created a stacked column pivot chart that can be filtered by country based on the table have created.

The dates stored within the deadline and launched_at columns use Unix timestamps. Also, there is a formula that can be used to convert these timestamps to a normal date.
- Created a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format.
- Created a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.
- Created a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.
- Finally, created a pivot chart line graph that visualizes this new table.

Additionally :
- Created a new sheet with 8 columns
- In the Goal column, created 12 rows 
- Using the COUNTIFS() formula, counted how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populated the Number Successful, Number Failed, and Number Canceled columns with this data.
- Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.
- Created a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.

Statistical Analysis:
- The mean number of backers.
- The median number of backers.
- The minimum number of backers.
- The maximum number of backers.
- The variance of the number of backers.
- The standard deviation of the number of backers.




