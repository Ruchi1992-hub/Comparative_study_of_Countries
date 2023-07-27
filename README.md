# Comparative_study_of_Countries -- Tablaue Project

**Problem Statement:** Created a dashboard to do a comparative study on various parameters of different countries using the sample insurance dataset and world development indicators Datasets.

**Objective:** Create a dashboard to compare all the parameters mentioned above for different countries, to strategize market penetration and to target new customers.

# Dataset-
**Primary Dataset:** Insurance Sample Dataset.

**Secondary Dataset:** Global Financial Development Database.

# Steps To Perform:
1. Created a geographic map showing the countries' fields. Color the map based on the income column from the secondary dataset
    - Include income group filter in the dashboard

2. Included a webpage to show data from the world bank webpage driven by an URL action from a geography graph
    - The country names in the map will act as the trigger - https://en.wikipedia.org/wiki/Country
 
3. Created a KPI Table to show the comparison between the selected period and the period prior to the selected one
    - Created two parameters for Year Selection and Category Selection
    - Category parameter includes life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio
    - Created a calculated field to calculate the Growth %
    - Created a table to show these values

4. Create Growth Indicator Shapes based on the Growth %
    - Growth indicator displays Negative, No Change, and Positive as values and corresponding shapes against it

5. Created a trend line to show the selected category values
    - The line shows an arrow or triangle at the last mark

6. Created a dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well

# Dashboard: 
https://public.tableau.com/views/ComparativeStudyofCountry_16899511164380/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link
![Comparative Study Of Countries]( https://github.com/Ruchi1992-hub/Comparative_study_of_Countries/blob/main/Comparative%20Study%20of%20Countries.png?raw=true "Comparative_Study_of_Countries")
