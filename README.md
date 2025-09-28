# EVAnalysisDashboard_Tableau
This Tableau project involves cleaning two combined CSV files, creating calculated fields and bins. The dashboard will feature KPIs for total vehicles, electric range, and BEV/PHEV metrics, plus charts analyzing distribution by year, state, make, and model. The final deliverable is an interactive dashboard with navigation and a data story.

1.	Import the 2 CSV files attached in this document in Tableau and combine them in a single file in Tableau.

2.	Perform the following data cleaning operations in Tableau.

a.	Rename the values of Electric vehicle type column. Battery Electric Vehicle (BEV) to Battery Electric Vehicle. Plug-in Hybrid Electric Vehicle (PHEV) to Hybrid Electric Vehicle.

b.	Exclude all the records from all the analysis where Vehicle Location column is Blank

c.	Create a new variable Electric Range Bin which will have 3 values (High, low or Medium). If electric range column has value 0-100 then value will be low, if 101-200 then medium, if greater than 200 then High.

d.	In vehicle location column, latitudes and longitudes of the locations are given. Create 2 new columns based on this column. First column name will be Latitude_location which will have first numeric value and 2nd column will be Longitude_location which will have second numeric value.
Eg: POINT (-122.34301 47.659185) will have -122.34301 in latitude_location and 47.659185 in longitude_location.

e.	Create a new column(Address) using city, state and postal code. New column name will be combinations of those 3 columns - City,State, Postal code. Also, If state is WA, replace it with Washington. 

Eg: Seattle, Washington, 98103.

3.	KPIs requirement for Dashboard build:

a)	Total Vehicles:
Understand the overall landscape of electric vehicles, encompassing both BEVs and PHEVs, to assess the market's size and growth.


b)	Average Electric Range:
Determine the average electric range of the electric vehicles in the dataset to gauge the technological advancements and efficiency of the EVs.


c)	Total BEV Vehicles and % of Total BEV Vehicles:
Identify and analyze the total number of Battery Electric Vehicles (BEVs) in the dataset.
Calculate the percentage of BEVs relative to the total number of electric vehicles, providing insights into the dominance of fully electric models.


d)	Total PHEV Vehicles and % of Total PHEV Vehicles:
Identify and analyze the total number of Plug-in Hybrid Electric Vehicles (PHEVs) in the dataset.
Calculate the percentage of PHEVs relative to the total number of electric vehicles, offering insights into the market share of plug-in hybrid models.

4.	Charts Requirement:

a)	Total Vehicles by Model Year (From 2011 Onwards):
Description: This chart will illustrate the distribution of electric vehicles over the years, starting from 2011, providing insights into the growth pattern and adoption trends.


b)	Total Vehicles by State:
Description: This chart will showcase the geographical distribution of electric vehicles across different states, allowing for the identification of regions with higher adoption rates.


c)	Top 10 Total Vehicles by Make:
Description: Highlight the top 10 electric vehicle manufacturers based on the total number of vehicles, providing insights into the market dominance of specific brands.


d)	Total Vehicles by CAFV Eligibility:
Description: Illustrate the proportion of electric vehicles that are eligible for Clean Alternative Fuel Vehicle (CAFV) incentives, aiding in understanding the impact of incentives on vehicle adoption.


e)	Top 10 Total Vehicles by Model:
Description: Highlight the top 10 electric vehicle models based on the total number of vehicles, offering insights into consumer preferences and popular models in the market.


5.	Below is the sample Dashboard view which can be taken as a sample. DO NOT copy this dashboard exactly but take the idea from this and use your own Analytical skills and creativity to create an end to end dashboard. Please add 2 Navigation buttons also in this dashboard , so that when user clicks on that button it will take him to the other screen/chart/dashboard. On that other screen/chart/dashboard, add 1 Navigation button with the "Back" option. So that when user clicks on "Back" button, user will come back to main dashboard.

6.	Create the story also, starting with the dashboard and then moving towards into more granular level.


Below is the sample dashboard for an idea. You need to add Navigation buttons also as mentioned in previous point.

