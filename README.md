# proj1
# short data science project 
The United States, home to approximately 320 million citizens, is a large country made of 50 states and the nation’s capital, the District of Columbia (also called Washington D.C.). In this project, you will explore some of the economic statistics of each state and produce a report. No data on U.S. territories are included in the file.
Data will be read from a CSV (comma-separated values) file called Economic_Data_2010.txt. This file has not header record, so you may read it as a plain text file and split the line to separate the individual values.

Objective:
You are to provide economic statistics by region as follows:
• Total population for the region (sum of the column value)
• Total GDP for the region (sum of the fourth column)
• Average population in the region (total population / number of states in region)
• Average personal income (Total personal income / total population). You need to derive a meaningful measurement for this statistic

Your code must provide the following:
• Prompt the user for a region name.
• Read the data from the file selecting only the data for the region.
• Build three dictionaries for the region for the population, GDP, and personal income. The key for each dictionary is the State.
• In the case where the user entered an invalid region, an appropriate error message should be displayed. Note, you will not know this until you've read through the file and found no data.
• Write a function called calc_total_pop is passed the population dictionary and returns the total population. You will obviously need to iterate through the dictionary to produce the total population.
• Write a function called calc_total_gdp that is passed the gdp dictionary and returns the total GDP.
• Write a function called calc_total_pi that is passed the personal income dictionary and returns the total personal income.
