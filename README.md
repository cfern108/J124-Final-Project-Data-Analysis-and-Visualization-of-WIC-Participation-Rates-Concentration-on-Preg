# J124 Final Project: Data Analysis and Visualization of WIC Participation (Postpartum and Pregnant Women) 
![d8e5eb8f5c04ab56be38b33641b1e4f2_wiclogo](https://user-images.githubusercontent.com/109619760/183957823-bd52d2e7-b2bd-4e04-b3a1-d2a182ae6665.jpg)
## By Fernanda Frausto-Bonilla
* *This dataset was downloaded as (12) individual .csv files from [U.S. Public Assistance](https://www.kaggle.com/datasets/jpmiller/publicassistance?select=WICAgencies2013ytd/).*
* *Link to [Google Sheet](https://docs.google.com/spreadsheets/d/1k-hFV07D_SuZsrD7_QWKM_obHQNqOTFNqP9yojNhaQQ/edit?usp=sharing)  with all .csv files grouped and cleaned.*
# Story Pitch and Summary

In my analysis, I am seeking to break down the Special Supplemental Nutrition Program for Women, Infants, and Children (commonly known as "WIC") participation rates by categories: postpartum and pregnant women. On a U.S. national basis, the cost of living and raising children has progressively increased rapidly. According to data from [Statista Research Department](https://www.statista.com/statistics/216426/average-costs-of-raising-a-child-from-birth-to-age-18-in-the-us--in-2010-by-category/), the average cost of feeding a child in the U.S. from birth to age 18 was $39,060 in 2013. This expense equals an average annual cost of $2,170 for feeding a child when divided by 18 (the total number of years it predicted spending money on feeding a child). As a result, more and more mothers (including soon-to-be-mothers) struggle to give their kids a healthy, quality diet and are compelled to deal with food insecurity head-on. To assist mothers and children facing food insecurity, the Federal and State government provide special funds through WIC to assist low-income women and children up to age five who are at nutritional risk. These funds are used to provide supplementary food, infant formula, medical care, and nutritional counseling. 

The purpose of my data is first and foremost to evaluate 1) which population group , either postpartum or pregnant women, utilize WIC services more often, 2) which state agencies and/or Indian Tribal Organizations serve participants most and least frequently, and 3) overall lay the groundwork for a proposal regarding which population groupings the federal government should concentrate its service efforts on based on a supply and demand logic. On a moral and ethical level, I believe my findings are relevant to a conversation surrounding the needs of women, prenatal and postpartum while simultaneously being intentional about shedding light on WIC participation, specifically one in which I hope will lead to a conversation in which groups are asked what needs they need met rather than being shunned for utilizing services. Questions I will be asking include, "Which population groups (e.g. pregnant women, postpartum women, etc.)make up the largest percentage of WIC participants?" or "Which state agency or Indian tribal organization has the highest relative participation rate?" and more. 


  SUMMARY OF FINDINGS 
![Preg_Wom_3Pic_banner](https://user-images.githubusercontent.com/109619760/183976534-93f365c0-0194-461c-9392-2a7df4008ee0.png)

# Secondary Sources 
* Some secondary sources I feel are relevant to further develop my story on WIC participation rates include the following: the [Public Policy Institute of California](https://www.ppic.org/publication/the-wic-program-in-california/#:~:text=The%20largest%20shares%20of%20children,of%20WIC%20recipients%20in%20California.), the [California Department of Public Health]( https://www.cdph.ca.gov/Programs/CFH/DWICSN/Pages/ResearchandData/WICProgramParticipantInfo.aspx#), and the [United States Census Bureau](https://www.census.gov/library/visualizations/interactive/wic-eligibility-participation.html).
- ***The Public Policy Institute of California** notes qualification requirements for WIC recipients, coverage rate per state, WIC child enrollment levels by county, participant’s racial demographics, and the rate in which WIC recipients also participate in other safety net programs. According to this site, “Participants must demonstrate that they are actively enrolled in CalWORKs financial aid, CalFresh nutrition assistance, or Medi-Cal health insurance in order to be eligible. Alternatively, if their income is less than the federal poverty level, which is now $44,863 for a family of four, they are eligible. Candidates are also judged on their eating patterns and health issues. Participants in WIC are obliged to attend programs that support breastfeeding and encourage a healthy diet, as well as to use vouchers to purchase specific items (such milk and eggs).* 
- ***The California Department of Public Health** illuminates the links that can be drawn in order to comprehend why women choose not to sign up for WIC during pregnancy, among other things, and poses the "why" question in response to my data.* 
- ***The United States Census Bureau** also provides audiences with more information about WIC program eligibility and participation based on age and race/ethnicity by county using an interactive map and graphic.*
 
# Potential Interviews:
1. Karen Farley, RD, IBCLC: Executive Director of the California WIC Association. 
* Farley is a renowned state authority on breastfeeding-related policy matters as well as nutrition and breastfeeding care reform for preventing chronic diseases and enhancing factors affecting family health. Her work focuses on supporting novel approaches for WIC to combine with public health and the community. Karen appreciates how diverse local, state, and national groups work together with CWA to more effectively address the intricacies of today's challenges. I believe Karen will be relevant to my story as she will be able to provide knowledge on what target groups would benefit from more services and overall care. 
* Email: kfarley@calwic.org
* Telephone: 916-572-0700 
2. Estefania Aparicio
* Aparicio is a Nutrition and Public Health Unit researcher on Nutrition and Mental Health (NUTRISAM), Faculty of Medicine and Health Science, Universitat Rovira i Virgili, 43201 Reus, Spain. Aparicio's work centers on nutrient intake, specifically she has published an article on nutrient intake during pregnancy and post-partum via an [ECLIPSES Study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7285175/). I am confident that she will bring a sharp understanding of the significance of high-quality, nutrient-dense foods for the target segments in my pitch.
* Email: estefania.aparicio@urv.cat
* Telephone: +34-977759334

# Data Analysis

## Notes:
* Download the "Pregnant_Women_Participation", "Postpartum_Women_Participation", and "Total_Number_of_Participants" .csv files for the years (2013-2016). 
* There is a total of (12) .csv files that should be cleaned in OpenRefine. When cleaning, I only needed to sort the State agency/Tribal organization columb, remove a duplicate column with no data (which was an extra Texas), format columns with dates to a (00/00/00) style, and format the data to 'number' rather than 'plain text.'
* Upload the cleaned .csv files to Google Drive. 
* In Google Sheets, import each .csv file into three separate sheets (as tabs) ("Pregnant_Women_Participation", "Postpartum_Women_Participation", and "Total_Number_of_Participants") and group together the data based on year. There should be a color-coded system for each year in each sheet (e.g. green for 2013, purple for 2014, yellow for 2015, and blue for 2016). All years' data on annual participation are color-coded in pink.
* My data is limited to the years (2013-2016) because those were the only years the data is available. The time frame for each year begins on October 1st and ends on September 1st of the following year. 
- In other words, 'Average Participation 10/12-09/13' refers to the year 2013, 'Average Participation 10/13-09/14' refers to the year 2014, 'Average Participation 10/14-09/15' refers to the year 2015, and  'Average Participation 10/15-09/16' refers to the year 2016. For clarification purposes, the '00/00' format refers to month and year.

## Analysis Question 1: Which year saw the highest total average WIC participation (across all State agencies/Indian tribal organizations) among pregnant and postpartum women? Which year was the lowest?

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
9. Create a pivot table utilizing the 'postpartum 2013-2016' sheet which reflects 'Postpartum_Woman_Participants' data from 2013-2016.
10. Add ''State Agency or Indian Tribal Organization' to a row. 
11. Order the row by 'Ascending.' 
12. Sort the row by 'State Agency or Indian Tribal Organization.' 
13. Show totals for the row. 
14. Add 'Average Participation 10/12-09/13', 'Average Participation 10/13-09/14', 'Average Participation 10/14-09/15', 'Average Participation 10/15-09/16' to values. Make sure to add these values in the correct year order.
15. Categorize each value by SUM. 
16. Compare the grand totals for each column and identify which average participation total is the highest and lowest. 
<img width="721" alt="Screen Shot 2022-08-10 at 3 41 49 AM" src="https://user-images.githubusercontent.com/109619760/183883343-82d8a1d7-836a-4196-83af-b4ec4f324fe9.png">
<img width="720" alt="Screen Shot 2022-08-10 at 3 42 17 AM" src="https://user-images.githubusercontent.com/109619760/183883377-10e1e3cb-cc6a-4fda-b097-bd8ab14385a1.png">
<img width="721" alt="Screen Shot 2022-08-10 at 3 42 41 AM" src="https://user-images.githubusercontent.com/109619760/183883386-d87a62be-94bc-4c62-a24e-1dd058e96724.png">


### *ANSWER KEY:* 
* The year with the highest total average WIC participation for both pregnant and postpartum women is 2013 (10/01/12 - 09/01/13) with a total average WIC participation score of (906,255.50) for pregnant women and a total average WIC participation score of (643,243.42) for postpartum women. This sheds light on pregnant women utilizing WIC services more than postpartum women.  
* The year with the lowest total average WIC participation for both pregnant and postpartum women is 2016 (10/01/15 - 09/01/16) with a total average WIC participation score of (767,635.50) for pregnant women and a total average WIC participation score of (562,171.92) for postpartum women. This sheds light on pregnant women utilizing WIC services more than post partum women.  

## Analysis Question 2: Among postpartum and pregnant women, which three state agencies or Indian tribal groups had the highest average participation for the year 2013? Which were the lowest?
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
9. Change the order of the row to 'Ascending.'
10. Evaluate the data for the lowest average participation score.
<img width="752" alt="Screen Shot 2022-08-10 at 1 35 54 AM" src="https://user-images.githubusercontent.com/109619760/183855559-01c17f8e-f856-4e5b-b5fb-ac8b6957ec08.png"> 
11. Create a pivot table utilizing the 'pregnant 2013-2016' sheet which reflects 'Pregnant_Woman_Participation' data from 2013-2016.
12. Add 'State Agency or Infian Tribal Organization' to a row.
13. Order the row by 'Descending.'
14. Sort the row by 'SUM of Average Participation 10/12-09/13.' This is the average participation for the year 2013.
15. Unclick 'Show Totals' for the row.
16. Filter the pivot table to show only 'Average Participation 10/12-09/13.'
17. Add 'Average Participation 10/12-09/13 to values.'
18. Evaluate data for the highest average participation score.
<img width="575" alt="Screen Shot 2022-08-10 at 4 08 12 AM" src="https://user-images.githubusercontent.com/109619760/183886818-f8bd2c24-aee1-4bf9-9813-535b235c384b.png">
19. Change the order of the row to 'ascending.'
20. Evaluate the data for the lowest average participation score.
<img width="843" alt="Screen Shot 2022-08-10 at 4 10 00 AM" src="https://user-images.githubusercontent.com/109619760/183887140-152f68c6-d9d8-4a2b-a889-e413c3b0aa26.png">

### *ANSWER KEY:*
* The three state agencies or Indian tribal groups with the highest average participation scores for the year 2013 among postpartum women are 1) California (79,040 average participation), 2) Texas (49,277 average participation), and 3) Mountain Plains (44,945.33 average participation). 
* Meanwhile, the three state agencies or Indian tribal groups with the highest average participation scores for the year 2013 among pregnant women are 1) California (126,481.83), 2) Texas (95,425.75), and 3) Mountain Plains (53,240.33). This tells me that pregnant women utilized WIC services more than postpartum women in 2013. 
* The three state agencies or Indian tribal groups with the lowest average participation scores among postpartum women include 1) Pleasant Point, ME (2.83), 2) Indian Township, ME (3), and Seneca Nation, NY (5.42). 
* Meanwhile. the three state agencies or Indian tribal groups with the lowest average participation scores among pregnant women include 1) Indian Towns (6.17), Pleasant Point, ME (8.17), and Santo Domingo Tribe, NM (16.17). 

## Analysis Question 3: Among total WIC participants, are any state agencies or Indian tribal organizations exceptional in regards to average participation size in the year 2014?

### Step-By-Step Solution:
1. Create a pivot table utilizing the 'total participation 2013-2016' sheet which reflects 'Total_Number_of_Participants' data from 2013-2016.  
2. Add 'State Agency or Indian Tribal Organization' to a row. 
3. Order the row by 'Descending.' 
4. Sort the row by 'SUM of Average Participation 10/13 - 09/14.' This is the average participation for the year 2014. 
5. Unclick 'Show Totals' for the row. 
6. Filter the pivot table to only show 'Average Participation 10/13 - 09/14.'
7. Add 'Average Participation 10/13-09/14' to values. 
8. Evaluate data for any exceptional data.
<img width="1016" alt="Screen Shot 2022-08-10 at 1 55 52 AM" src="https://user-images.githubusercontent.com/109619760/183859874-0fb39f52-e071-4c40-b92d-033d9123ba6c.png">
<img width="1013" alt="Screen Shot 2022-08-10 at 1 56 49 AM" src="https://user-images.githubusercontent.com/109619760/183860021-4bf25c96-7eff-4d4b-af5f-454f66a75b07.png">
<img width="1006" alt="Screen Shot 2022-08-10 at 1 58 37 AM" src="https://user-images.githubusercontent.com/109619760/183860449-d9e8f77b-f6ce-484a-a074-0029bc4c8d41.png">

### *ANSWER KEY:*
* The states that seem most exceptional to me include California (1,348,938.58 average participation score) and Texas (916,461.17 average participation score). I feel that these are exceptional because 1) California doubles the average participation score of every other State agency or Indian Tribal Organization besides Texas, and 2) Both Texas and California are the only state agencies to surpass a score of 530,000 average participation. 

## Analysis Question 4: California was consistently the top state agency for highest average WIC participation among pregnant and postpartum women, what was the percent change in average WIC participation among both pregnant and postpartum women from the years 2013-2016?
### Step-By-Step Solution:
1. Create a pivot table utilizing the 'pregnant 2013-2016'sheet which reflects 'Pregnant_Woman_Participation' from 2013-2016.
2. Add 'State Agency or Indian Tribal Organization' to Row.
3. Order your row as 'Ascending'.
4. Sort your row by 'State Agency or Indian Tribal Organization.
5. Unclick 'Show Totals'
6. Add 'Average Participation 10/12-09/13', 'Average Participation 10/13-09/14', 'Average Participation 10/14-09/15', 'Average Participation 10/15-09/16' to values. Make sure to add these values in the correct year order.
7. Filter 'State Agency or Indian Tribal Organization to only show data for California and Texas. 
8. Create Two new columns "Percent Change Yearly."
9. Use the equation "=((current year value - previous year value)/previous year value) for analysis. 

## Analysis Question #5: What percentage of total WIC participants are pregnant women? What percentage of total WIC participants are postpartum women? 
### Step-By-Step Solution: 
1. 

