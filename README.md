# SF Car Crashes EDA

This project explores all crashes resulting in an injury in the City of San Francisco from years 2005 to mid-2024 using SQL.

## File Descriptions

- `Data_Exploration_SQL.ipynb` contains all the SQL queries for data exploration. 

The data files are found in `Data.zip`. <br>

The data files below are obtained from data.sfgov.org on August 19,2024. 
- `Data/Traffic_Crashes_Resulting_in_Injury_20240819.csv` contains all crashes resulting in an injury.

- `Traffic_Crashes_Resulting_in_Injury__Victims_Involved_20240819.csv` contains all victims (parties who are injured) involved in a traffic crash resulting      in an injury.

- `Traffic_Crashes_Resulting_in_Injury__Parties_Involved_20240819.csv` contains all parties involved in a traffic crash resulting in an injury.

- `Traffic_Crashes_Resulting_in_Fatality_20240819.csv` contains all fatalities resulting from a traffic crash.

The data file below is created after data wrangling (e.g. remove duplicates). It selects certain columns from `Traffic_Crashes_Resulting_in_Injury_20240819.csv` and    `Traffic_Crashes_Resulting_in_Injury__Victims_Involved_20240819.csv`. 
- `SF_Traffic_Incidents_Cleaned.csv` contains all crashes that resulted in an injury and information about the victims.

## Interesting Findings:
- There are on average ~3000 car crashes per year that result in an injury.
- On average 29 people are killed and ~3,700 are injured annually in these car crashes.
- Most car crashes happen on Mission St, followed by Market St, Vanness Ave, and Geary Blvd.
- The average number of injured individuals per car crash is 1.
- Men are twice as likely to be injured in car crashes compared to women, and this trend also holds true for those deemed at fault.
- The most common type of collision is broadside, followed by vehicle/pedestrian, rear end, and sideswipe. 
