
# International-Football-Analysis-Using-SQL
Using POSTGRESQL I analyzed the International Football dataset 1872 - 2022 (Gotten from D'Challenger's June Challenge on LinkedIn). 
I used the dataset to practise my skills in data cleaning, data analysis and data visualization using Microsoft Excel, SQL and Tableau

### Inspiration
- What team is the best team of all time?
- Which team dominated different eras of football?
- What trends have been there in the international football throughout the ages? Home advantage? Total goals scored etc
- Which teams are most active in playing friendlies and friendly tournaments? does it hurt or help them?

### Data Cleaning
The dataset was cleaned in Microsoft Excel
- I checked for NULL Values
- I checked for duplicates
- I created a new column to extract the years from the date column. 
After I was done with cleaning the data, I took it to pgAdmin for the analysis

### Data Analysis
Some of the insights I got from the analysis are 
- The total number of goals was 126,992. This was gotten by finding the total number of goals for home_teams, away_teams and then summing them together (as seen in the code)
- The total number of tournaments was 129
- The total number of teams - 312
- BRAZIL was the best team of all time
- There was a sharp drop in the matches played in 2020. This was due to COVID
- The different teams that dominated different eras amongst other insights. 
All these can be seen in the PostgreSQL code uploaded

### Data Visualization 
Once I was done with the analysis, I took the tables I created into Microsoft Excel, saved it and uploaded them to Tableau (This is because tables from pgAdmin can not be uploaded directly into Tableau), then created a dashboard. 

![Dashboard 1 (2)](https://user-images.githubusercontent.com/106774340/179373850-69d3cd57-8e6f-4a13-889c-97213542bfb3.png)


