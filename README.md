### Project Title
Exploring Weather Trends

### Date created
Project is created on Feb 11th 2020.

### Description
In this project, I analyzed local and global temperature data and compare the temperature trends to overall global temperature trends. I created a visualization and prepared a write up describing the similarities and differences between global temperature trends and temperature trends in Memphis.

### About
+ The final report is "Exploring Weather Trends.pdf" file.
+ I included a clearer imagine of visualized data "Global vs memphis weather trend.png".
+ Queries:  SELECT * FROM city_data WHERE city = ‘Memphis’;
+ How to calculate moving average: I picked seven years as window, used 	=AVERAGE(:) function in excel to 	calculated average for every seven years.
+ Key consideration: I notice in global file, the data didn’t start until 1750, while in 	Memphis file the 	data started 1743, however, there are four year’s missing value 	between 1746 and 1749 in Memphis 	file. Science I picked seven years as window, 	this missing 	part will become an outliner, so it make 	sense to drop it off and 	start both data analysis from 1750.

### Software used
+ Postgre SQL
+ WPS Office (Excel/ Word)
+ Tableau

### Files used
+ city_data.csv
+ city_list.csv
+ global_data.csv

### Credits
+ Data provided by: [Udacity](https://www.udacity.com/)
+ Instruction and assist: [Become a Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
