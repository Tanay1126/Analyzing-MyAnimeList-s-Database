# Analyzing-MyAnimeList-s-Database
The dataset contains info obtained from the famed logging website MyAnimeList. It contains info about 24000+ anime related media &amp; 67273+manga related media. Last updated August 2023. We conducted data analysis , extraction and EDA operations on the dataset. This project reflects that work and the several analysis 

README:
Excel:

Load dataset from CSV to excel. Save data first.
Find missing or odd values using conditional formatting
Add number of missing values to column
Find null values using isNA()
Find any other values depending on analytical questions manually
Make formulas for finding basic analysis questions. (ie; COUNT(), MAX(), AVERAGE(), MODE() or etc)
Investigate sections of data using quartile
Make column for number of days since airing or publication
Make column for statuses and relegate categories to media based on IF function.
Modify data to match certain pre-requisites for analysis (ie; no negative values in the number of days since airing).
 Use Power Query/ BI to sort certain columns that have delimiters. (ie; Genres, Demographics have delimiters using commas. Sort columns to conduct any further operations).
Made delimiters for any other columns if needed.
Add a status for if a show has been going on/ went on for a long time, short time, ongoing.


Tableau:
Load the modified excel file into Tableau
From the sheets created using Power Query, drag genres into row and average score into column to find which genres are the most high/low rated.
Drag genres into row and average bloat into column to find a bar chart of which genres typically have bloated scores.
Drag status (of whether it is a hidden gem etc.) as color, a count of status into angle, and setting both of the above as label makes a pie chart showing the distribution of the different kind of statuses a show may have in discussions surrounding it.
Within shows that have won an award, drag genres into column, count of genre into row, set color as Avg Score, set size as Popularity(Sum of scored_by) to get a shape chart showing distribution of count, rating, and popularity of shows that have won an award.


