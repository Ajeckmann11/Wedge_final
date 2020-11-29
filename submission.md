
# Applied Data Analytics

## Wedge Project

<!-- Any general commentary you'd like to say about the project --> 

### Task 1

* Files for this task: 
<!--  List of file or files here  --> 

Loads all data into GBQ data set.

`File1 Name`: 
Description of what this file does.

<!--  Repeat for each file  --> 



### Task 2

* Files for this task: 
<!--  List of file or files here  --> 

Loads all data into GBQ data set.

`File1 Name`: 
Description of what this file does.

'sample_of_owners.txt':
My sample of owners text file
	

### Task 3

* Files for this task: 
<!--  List of file or files here  --> 

Loads all data into GBQ data set.

`File1 Name`: 
Description of what this file does.

'sales_by_date_by_hour.txt':
My text file for the query of sales by date by hour

'sales_by_owner_by_year_by_month.txt':
My text file for the query of sales by owner by year by month

'sales_by_product_description_by_year_by_month.txt':
My text file for the query of sales by product description by year by month


## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - my_results)/my_results)`. 



|  Query  |  Your Results  |  My Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |85760086|85760139|-53|-0.00000062|
| January 2012 Rows  |1070905|1070907|-2|-0.00000187|
| October 2012 Rows  |1042285|1042287|-2|-0.00000192|
| Month with Fewest  |2|2|No|NA|
| Num Rows in Month with Fewest  |6556769|6556770|-1|-0.00000015|
| Month with Most  |5|5|No|NA|
| Num Rows in Month with Most  |7578370|7578372|-2|-0.00000026|
| Null_TS  |7123786|7123792|-6|-0.00000084|
| Null_DT  |0|0|0|0|
| Null_Local  |234843|234843|0|0|
| Null_CN  |0|0|0|0|
| Num 5 on High Volume Cards  |14987.0|14987.0|No|NA|
|  Num Rows for Number 5 |460630|460630|0|0|
| Num Rows for 18736  |12153|12153|0|0|
| Product with Most Rows  |banana organic|banana organic|No|NA|
| Num Rows for that Product  |908637|908639|-2|-0.0000022|
| Product with Fourth-Most Rows  |avacado hass organic|avacado hass organic|No|NA|
| Num Rows for that Product  |456771|456771|0|0|
| Num Single Record Products  |2769|2769|0|0|
| Year with Highest Portion of Owner Rows  |2014|2014|No|NA|
| Fraction of Rows from Owners in that Year  |0.7591|0.7591|0|0|
| Year with Lowest Portion of Owner Rows  |2011|2011|No|NA|
| Fraction of Rows from Owners in that Year  |0.7372|0.7372|0|0|

## Reflections

<!-- I'd love to get 100-200 words on your experience doing the Wedge Project --> 

I actually enjoyed this project, besides a couple problems I ran into. Parts of this (like loading the data into the database) was a little annoying just due to the amount of time that it took where you couldn't work on it. This was probably more of a problem for me though because I was very late in getting this done. The first time I loaded the data into the db, my free account ran out, so I had to set up the billing and run it again. I must've had an error when I did this the second time because I appended rows to the bottom of the tables that were already written in. So the first time I went to run these tests I had 1.5x as many rows for everything (because the first 25 files were twice the length they should've been). I ended up just deleting all these tables and rewritting them in, which took a few hours, but eventually yielded good results. Other than those problems, I enjoyed the project. I ran into some problems getting the "A" part for Part 1 to work, and with this already being late, I just decided to go for a "B" on this project and bump down my course grade as a result.