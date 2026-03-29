# TODO
> Edit this file to add your answeres to each TODO item. Its okay to link to external documentation as well, just remember to ensure that our reviewers has access.
> When you're ready to submit, click **Commit changes...** and save your responses to a new branch titled 'implementation' and create a pull request.

> Before you start reading, please configure your environment as described in the "Before you get started" README section of your GitHub repository.*

In this task, you will work with the [Chicago Crime Dataset](https://console.cloud.google.com/bigquery?ws=!1m5!1m4!4m3!1salva-coding-test!2schicago_crime!3scrime) to figure out some insights regarding the crimes commited in Chicago.

Here are some examples of the columns you will work with:

|Variable|Description|
|----:|-----|
|primary_type |What type of crime was committed|
|location_description |Description of the location where the crime was committed|
|arrest|If the crime led to an arrest or not|

Feel free to explore the dataset and try out different queries using the BigQuery interface.

Once you have a query that answers the question, add the code snippet to the specific question as well any supportive reasoning/comment that you may have.


## Files in this Repository

1. `Tele2US-2026-03-27-1.ipynb` - the initial source of truth, the actual working BigQuery Studio notebook
   with all code and execution cells with query/code execution results, graph plots

2. `Tele2US-2026-03-27-1.pdf` - the notebook in 1 transformed to `.pdf`, can be viewed in any reader like `acroread`, `qpdfview`, ...
   (BigQuery Studio notebooks are highly non-standard, some features may be lost)

3. `Tele2US-2026-03-27-1-clean.ipynb` - the notebooks from 1 stripped from all nonstandard BigQuery Studio widgets (to be able to transform to the `.html` file in 4)

4. `Tele2US-2026-03-27-1-clean.html` - the file in 3 transformed into `.html`

**Bottom line:** most reliable (and executable) in file in 1. Files 2, 4 are convenient to view in a pdf browser and any web browser, respectively.


## Task 1 

Which year had the highest amount of crimes?

> **Answer:** https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-1.-Which-year-had-the-highest-amount-of-crimes%3F


## Task 2

Let's define "Arrest Rate" as the share of crimes that led to an arrest.

What year had the highest arrest rate? What is the overall trend in number of crimes per year?

> **Answer:** https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-2.-Arrest-Rate


## Task 3

What were the five most common crimes in 2020? Which of those crimes had the highest and lowest arrest rate?

> **Answer:** https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-3.-What-were-the-five-most-common-crimes-in-2020%3F

## Task 4

How has the arrest rate looked like over time? 

- Plot the trend of the arrest rate.
- Between which years can you see the biggest change in "Arrest Rate"?
- Can you point at specific reasons to why the Arrest Rate dropped between those years? Comment on your conclusions.

> Since the data set is constantly updating, disregard the year 2021 and later for the analysis in this question.

> **Answer:** 
https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-4.-How-has-the-arrest-rate-looked-like-over-time%3F

## Task 5

* What was the arrest rate for thefts during 2017 and 2018?
* How much did the arrest rate decrease between those two years?
* Perform a t-test to determine if the decrease in arrest rate is significant at a 95% confidence level. 

Comment on your conclusions.

> **Answer:** https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-5.-What-was-the-arrest-rate-for-thefts-during-2017-and-2018%3F


## Task 6

Calculate the average number of crimes committed per day for each month. Which month has the highest respectively lowest number of crimes per day on average?

> Since the data set is constantly updating, disregard the year 2021 and later for the analysis in this question.

> **Answer:** https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-6.-Calculate-the-average-number-of-crimes-committed-per-day-for-each-month%2E


## Task 7

Select the five most common crimes and write and SQL query that answer the following for each crime (i.e. each primary_type). 

1. How many crimes are committed per day on average for the month with the lowest average? Which month is this?
2. How many crimes are committed per day on average for the month with the highest average? Which month is it?

> Since the data set is constantly updating, disregard the year 2021 and later for the analysis in this question.

> **Answer:** https://htmlpreview.github.io/?https://github.com/svorobyov/tele2/blob/A/Tele2US-2026-03-27-1-clean.html#Task-7.-Select-the-five-most-common-crimes-and-write-and-SQL-query-that-answer-the-following-for-each-crime-%28i.e.-each-primary_type%29%2E
