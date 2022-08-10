# J124-Final-Project-Data-Analysis-and-Visualization-of-WIC-Participation-Rates-Concentration-on-Preg
## By Fernanda Frausto-Bonilla
* This dataset was downloaded as (12) .csv files from [U.S. Public Assistance](https://www.kaggle.com/datasets/jpmiller/publicassistance?select=WICAgencies2013ytd/).
* Link to [Google Sheet](https://docs.google.com/spreadsheets/d/1k-hFV07D_SuZsrD7_QWKM_obHQNqOTFNqP9yojNhaQQ/edit?usp=sharing)  with all .csv files cleaned.
# Data Analysis
## Notes:
* Download the "Pregnant_Women_Participation", "Postpartum_Women_Participation", and "Total_Number_of_Participants" .csv files for the years (2013-2016). 
* There is a total of (12) .csv files that should be cleaned in OpenRefine. When cleaning, I only needed to sort the State agency/Tribal organization columb, remove a duplicate column with no data (which was an extra Texas), format columns with dates to a (00/00/00) style, and format the data to 'number' rather than 'plain text.'
* Upload the cleaned .csv files to Google Drive. 
* In Google Sheets, import each .csv file into three separate sheets (as tabs) ("Pregnant_Women_Participation", "Postpartum_Women_Participation", and "Total_Number_of_Participants") and group together the data based on year. There should be a color-coded system for each year in each sheet (e.g. green for 2013, purple for 2014, yellow for 2015, and blue for 2016). All years' data on annual participation are color-coded in pink.
* My data is limited to the years (2013-2016) because those were the only years the data is available. The time frame for each year begins on October 1st and ends on September 1st of the following year. 
- In other words, 'Average Participation 10/12-09/13' refers to the year 2013, 'Average Participation 10/13-09/14' refers to the year 2014, 'Average Participation 10/14-09/15' refers to the year 2015, and  'Average Participation 10/15-09/16' refers to the year 2016. For clarification purposes, the '00/00' format refers to month and year.
## Analysis Question 1: Which year saw the highest total average WIC participation (across all State agencies/Indian tribal organizations) among pregnant women? Which year was the lowest?
### Step-By-Step Solution: 
1. Create a pivot table utilizing the 'pregnant 2013-2016' sheet which reflects 'Pregnant_Woman_Participation' data from 2013-2016.  
2. Add 'State Agency or Indian Tribal Organization' to a row. 
3. Order the row by 'Ascending.' 
4. Sort the row by 'State Agency or Indian Tribal Organization.' 
5. Show totals for the row. 
6. Add 'Average Participation 10/12-09/13', 'Average Participation 10/13-09/14', 'Average Participation 10/14-09/15', 'Average Participation 10/15-09/16' to values. Make sure to add these values in the correct year order.
7. Categorize each value by SUM. 
8. Compare the grand totals for each column and identify which average participation total is the highest and lowest. 
<img width="856" alt="analysis #1 pt 1" src="https://user-images.githubusercontent.com/109619760/183837637-dd75ee26-10bf-4de6-b46b-c2b60a902693.png">
<img width="757" alt="Screen Shot 2022-08-10 at 12 24 43 AM" src="https://user-images.githubusercontent.com/109619760/183840563-3fb4409c-c3f0-4685-94ec-0ddb308c24bb.png">
<img width="753" alt="Screen Shot 2022-08-10 at 12 26 23 AM" src="https://user-images.githubusercontent.com/109619760/183840839-5c491bbb-d07d-4676-a788-760926e95286.png">

### ANSWER KEY: 
* The year with the highest total average WIC participation among pregnant women is 2013 (10/01/12 - 09/01/13). 
* The year with the lowest total average WIC participation among pregnant women is 2016 (10/01/15 - 09/01/16)
## Analysis Question 2: Among postpartum women, which three state agencies or Indian tribal groups had the highest average participation for the year 2013? Which were the lowest?
### Step-By-Step Solution:
1. Create a pivot table utilizing the 'postpartum 2013-2016' sheet which reflects 'Postpartum_Woman_Participation' data from 2013-2016.  
2. Add 'State Agency or Indian Tribal Organization' to a row. 
3. Order the row by 'Descending.' 
4. Sort the row by 'SUM of Average Participation 10/12 - 09/13.' This is the average participation for the year 2013. 
5. Unclick 'Show Totals' for the row. 
6. Filter the pivot table to only show 'Average Participation 10/12 - 09/13.'
7. Add 'Average Participation 10/12-09/13' to values. 
8. Evaluate data for the highest average participation score.
<img width="758" alt="Screen Shot 2022-08-10 at 1 36 18 AM" src="https://user-images.githubusercontent.com/109619760/183855518-20a81cb2-45fb-4edb-8d3a-b69d29ba051a.png">

9. Change the order of the row to 'ascending.'
10. Evaluate data for the lowest average participation score. 
<img width="752" alt="Screen Shot 2022-08-10 at 1 35 54 AM" src="https://user-images.githubusercontent.com/109619760/183855559-01c17f8e-f856-4e5b-b5fb-ac8b6957ec08.png">

### Answer Key:
* The three state agencies or Indian tribal groups with the highest average participation scores for the year 2013 among postpartum women are 1) California (79,040 average participation), 2) Texas (49,277 average participation), and 3) Mountain Plains (44,945.33 average participation). 
* The three state agencies or Indian tribal groups with the lowest average participation scores include 1) Pleasant Point, ME (2.83), 2) Indian Township, ME (3), and Seneca Nation, NY (5.42). 

## Analysis Question 3: Among total WIC participants, are any state agencies or Indian tribal organizations exceptional in regards to size in the year 2014?
