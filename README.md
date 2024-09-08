# SF Traffic Crashes EDA

This project explores all traffic crashes resulting in an injury in the City of San Francisco from years 2005 to 2023 using SQL. Data from 2024 were excluded as the year is still ongoing. Traffic crashes include vehicle/pedestrian, vehicles only, vehicle/bicycle,etc.

## File Descriptions

Traffic crash data were obtained from data.sfgov.org on August 19,2024. The data files below can be found in `Data.zip`. <br>
- `Traffic_Crashes_Resulting_in_Injury_20240819.csv` contains all crashes resulting in an injury.

- `Traffic_Crashes_Resulting_in_Injury__Victims_Involved_20240819.csv` contains all victims involved in a traffic crash resulting in an injury.

- `Traffic_Crashes_Resulting_in_Injury__Parties_Involved_20240819.csv` contains all parties involved in a traffic crash resulting in an injury.

- `Traffic_Crashes_Resulting_in_Fatality_20240819.csv` contains all fatalities resulting from a traffic crash.

The data files below were created after data wrangling (e.g. remove 2024 entries and duplicates) and can be found in `Data.zip`. 
- `Traffic_Crashes_All_Cleaned.csv` contains crashes that resulted in an injury from 2005 to 2023.  

- `At_Fault_Demographics.csv` contains demographic data of parties who may or may not be at fault for the incidents from 2005 to 2023. The table was generated from `Traffic_Crashes_Resulting_in_Injury__Parties_Involved_20240819.csv`

Code file:
- `Data_Exploration_SQL.ipynb` contains all the SQL queries for data exploration. 

## Interesting Findings:

- There are on average ~3000 car crashes per year that result in an injury.
- On average 29 people are killed and ~3,800 are injured annually in these car crashes.
- Most car crashes happen on Mission St, followed by Market St, Vanness Ave, and Geary Blvd.
- The average number of injured individuals per car crash is 1.
- Men are twice as likely to be injured in car crashes compared to women, and this trend also holds true for those deemed at fault.
- The most common type of collision is broadside, followed by vehicle/pedestrian, rear end, and sideswipe. 

## Tableau Visualization

Check out the Tableau visualization of the San Francisco traffic crashes [here](https://public.tableau.com/app/profile/karen.zhu3272/viz/SanFranciscoTrafficCrashes2005-2023/Dashboard?publish=yes). This visualization shows a timelapse of the traffic crashes in San Francisco from 2005 to 2023. It also shows the top 10 neighbhoords/streets with the most incidents as well as the most deadly collision types.

![image](https://github.com/KarenZ2023/SF_Car_Crashes/blob/main/Tableau_viz_screenshot.png)
