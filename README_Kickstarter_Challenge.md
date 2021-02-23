# Dinah---KickStarter---Analysis
## Analysis of Kickstarter Campaigns
### Using Examples of US Successful and Failed Kickstarter Plays Goals and Pledges
### and GB Musical Goals and Pledges

# Kickstarting with Excel

## Overview of Project

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset visualize campaign outcomes based on their launch dates and their funding goals. This is a report based on your analysis and the visualizations.


### Purpose

An assignment of two technical analysis deliverables and a written report on the results. 
To submit the following:

Deliverable 1: Outcomes Based on Launch Date Chart
Deliverable 2: Outcomes Based on Goals Chart
Deliverable 3: A written analysis of the results (README_Kickstarter_Callenge.md)



## Analysis and Challenges

### Deliverable 1: Outcomes Based on Launch Date Chart

1.	Use pivot tables and graphing in Excel to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date.
2.	Rename the StarterBook.xlsx file you have been working with in this module: Kickstarter_Challenge.xlsx.
3.	Create a folder called “resources” to hold the PNGs of the two charts you will create.
4.	In the Kickstarter_Challenge.xlsx workbook, create a new column labeled "Years."
5.	In the "Years" column, use the YEAR() function to extract the year from the “Date Created Conversion” column.
6.	Create a pivot table from the KickStarter worksheet, and place the pivot table in a new sheet.
7.	Label the sheet "Theater Outcomes by Launch Date."
8.	Filter the pivot table based on "Parent Category" and "Years."
9.	Place the appropriate pivot table fields in the columns, rows, and values.
10.	Filter the column labels to show only "successful," "failed," and "canceled."
11.	Confirm that your pivot table looks like this:
12.	Filter the "Parent Category" to show only the data for "theater."
13.	Sort the campaign outcomes in descending order so "successful" is first.
14.	Confirm that your final pivot table looks like the given example


### Deliverable 2: Outcomes Based on Goals Chart

1.	Use your Excel skills to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. 
2.	You'll need to use a new function, COUNTIFS(), to collect the outcome and goal data for the “plays” subcategory. 
3.	In the KickStarter sheet, create a new sheet and label it "Outcomes Based on Goals."
4.	In the new sheet, create the following columns to hold the data:
Goal
Number Successful
Number Failed
Number Canceled
Total Projects
Percentage Successful
Percentage Failed
Percentage Canceled

4.	In the “Goal” column, create the following dollar-amount ranges so projects can be grouped based on their goal amount.
5.	Use COUNTIFS() functions to populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column using the ranges created in Step 3, and on the "Subcategory" column using "plays" as the criteria.


### Analysis of Outcomes Based on Launch Date

1.	Create a line chart from the pivot table to visualize the relationship between outcomes and launch month.
2.	Add a title to the line chart, and save it as Theater_Outcomes_vs_Launch.png to the resources folder.


Theater_Outcomes_vs_Launch.png 
[Analysis/Theater_Outcomes_vs_Launch.png](Dinah---KickStarter---Analysis/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

1.	Use the SUM() function to populate the "Total Projects" column with the number of successful, failed, and canceled projects for each row.
2.	Calculate the percentage of successful, failed, and canceled projects for each row.
3.	Create a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.
4.	Confirm that your line chart looks like the following, and save it as Outcomes_vs_Goals.png to the resources folder.


Outcomes_vs_Goals.png
[Analysis/Outcomes_vs_Goals.png](Dinah---KickStarter---Analysis/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
+++	In Deliverable 1, Theater_Outcomes_vs_Launch, the Goal: Greater than 50000, actually includes 50,000, otherwise the value for 50,000 is missen.


+++	In Deliverable 2, Outcomes_vs_Goals, it tooks a few trials to get used to using the COUNTIFS() with the multiple criteria (notice the S at the end of COUNTIFS)


## Results

####  Deliverable 1 Requirements
You will earn a perfect score for Deliverable 1 by completing all requirements below:

1.	A "Years" column is created based on the "Date Created Conversion" column in the Kickstarter spreadsheet (10 pt).
2.	A pivot table is created in a new worksheet labeled "Theater Outcomes by Launch Date" (5 pt).
3.	The pivot table filters on "Parent Category" and "Years" (10 pt).
4.	The columns, rows, and values in the pivot table fields are correctly populated (10 pt).
5.	The "Parent Category" is filtered on "theater" (5 pt).
6.	The row labels are changed to display the months of the year, and the campaign outcomes are sorted in descending order (5 pt).
7.	A line chart is created showing the number of successful, failed, or canceled projects by month, it has a title, and it is saved as Theater_Outcomes_vs_Launch.png (5 pt).

+++ 	 This was all done and submitted

Theater_Outcomes_vs_Launch.png 
[Analysis/Theater_Outcomes_vs_Launch.png](Dinah---KickStarter---Analysis/Theater_Outcomes_vs_Launch.png)


#### Deliverable 2 Requirements
You will earn a perfect score for Deliverable 2 by completing all requirements below:

1.	A new sheet is created with eight columns and twelve rows, according to the instructions (3 pt).
2.	The COUNTIFS() function is used to populate the "Number Successful," "Number Failed," and "Number Canceled" columns, based on the project "outcome," the "goal" amount using the goal ranges in Step 3, and the Subcategory "plays" (15 pt).
3.	The SUM() function is used on each row to add the "Number Successful," "Number Failed," and "Number Canceled" columns to populate the "Total Projects" column (3 pt).
4.	The percentages of successful, failed, and canceled projects are calculated based on the data from the "Total Projects," "Number Successful," "Number Failed," and "Number Canceled" columns (3 pt).
5.	A line chart is created and saved as Outcomes_vs_Goals.png with the goal-amount ranges on the x-axis, the percentage of successful, failed, or canceled projects on the y-axis, and an appropriate title (6 pt).

+++ 	 This was all done and submitted
Outcomes_vs_Goals.png
[Analysis/Outcomes_vs_Goals.png](Dinah---KickStarter---Analysis/Outcomes_vs_Goals.png)
[Dinah---KickStarter---Analysis/Outcomes_vs_Goals.png](Dinah---KickStarter---Analysis/Outcomes_vs_Goals.png)
[Dinah---KickStarter---Analysis/README_Kickstarter_Challenge.md](Dinah---KickStarter---Analysis/README_Kickstarter_Challenge.md)


### Your written analysis must contain three sections:

1.	Overview of Project: Explain the purpose of this analysis.
2.	Analysis and Challenges: Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.
3.	Results: Answer the following questions in complete and coherent sentences.
4.	What are two conclusions you can draw about the Theater Outcomes by Launch Date?
+++	The 2 conclusions that can be drawn about the Teather Outcomes by Launch Date are:
	a. May is a good time for Theater
	b. October is a bad time for Theater


5.	What can you conclude about the Outcomes based on Goals?
+++	The Outcome on Goals that ca be concluded is
	a. To be successfull, have goals from less than 1000 to 5,000
	b. To fail, your goals are around 1,000 to 5,000
	c. If your goal is between 1000 and 5000, you have chance a 2 in 3 chance of success


6.	What are some limitations of this dataset?
+++	The limitations of this dataset we are working with data for Theater and Plays


7.	What are some other possible tables and/or graphs that we could create?
+++	The possible tables and graphs that could be created at:
	a. Outcome based on goals for drama, musical, or people
	b. Launch date and drama, musical, people
	c. Theater can include plays and having data on other types of theater, like drama, musical, and people, gives a broader picture


### Deliverable 3 Requirements

1.	Structure, Organization, and Formatting (8 points)
	The written analysis has the following structure, organization, and formatting:
a.	There is a title, and there are multiple paragraphs (2 pt).
b.	Each paragraph has a heading (2 pt).
c.	There are subheadings to break up text (2 pt).
d.	Links are working, and images are correct and displayed where appropriate (2 pt).
e.	Analysis (12 points)

2.	The written analysis has the following:
a.	Overview of Project
b.	The purpose and background are well defined (2 pt).

3.	Analysis and Challenges
a.	The overview of the analysis is well described with screenshots (2 pt).
b.	Challenges or difficulties that were encountered, and how they were overcome, are well explained. 
c.	If there were no difficulties, describe any possible challenges or difficulties that could be encountered (2 pt).

4.	Results
a.	Two conclusions are made about the Theater Outcomes by Launch Date (2 pt).
b.	One conclusion is made about the Outcomes based on Goals (2 pt).
c.	There is a summary of the limitations of the dataset, and there is a recommendation for additional tables or graphs (2 pt).

+++ 	 This is all done and submitted

READEME_Kickstarter_Challenge.md
[Analysis/READEME_Kickstarter_Challenge.md](Dinah---KickStarter---Analysis/READEME_Kickstarter_Challenge.md)


5.
- What are two conclusions you can draw about the Outcomes based on Launch Date?
+++	The 2 conclusions that can be drawn about the Teather Outcomes by Launch Date are:
	a. May is a good time for Theater
	b. October is a bad time for Theater	

- What can you conclude about the Outcomes based on Goals?
+++	The Outcome on Goals that ca be concluded is
	a. To be successfull, have goals from less than 1000 to 5,000
	b. To fail, your goals are around 1,000 to 5,000
	c. If your goal is between 1000 and 5000, you have chance a 2 in 3 chance of success
	

- What are some limitations of this dataset?
+++	The limitations of this dataset we are working with data for Theater and Plays	

- What are some other possible tables and/or graphs that we could create?
+++	The possible tables and graphs that could be created at:
	a. Outcome based on goals for drama, musical, or people
	b. Launch date and drama, musical, people
	c. Theater can include plays and having data on other types of theater, like drama, musical, and people, gives a broader picture
	


+++ Final File Submitted is compressed and renamed from KickStarter_Challenge to KickStarter_Challenge - DinahBondzie

[Analysis/KickStarter_Challenge - DinahBondzie.xlsx](Dinah---KickStarter---Analysis/KickStarter_Challenge - DinahBondzie.xlsx)

