# Mapping Puerto Rico's Pediatricians
For this project, I was interested in identifying regional gaps in pediatric care in Puerto Rico. I used data from the Health Resources and Services Administration’s 2023–2024 Area Health Resource File and conducted my analysis using pandas.

To adjust the number of pediatricians in each town for population differences, I calculated the child population (ages 0 to 19) in each municipality using 2020 Census data. I then added a new column with the child population count per town and calculated the median child population across all of Puerto Rico.

Next, I normalized the pediatrician count in each town to the median child population, allowing for consistent comparison across municipalities. To analyze broader trends, I grouped towns into regions based on the Puerto Rico Department of Health’s administrative boundaries and calculated the total number of pediatricians and children in each region.

Lastly, I used geopandas to create a GeoJSON file representing the regional boundaries. This analysis focused on general pediatricians and didn't include pediatric subspecialists.

This project was part of my course work for the Lede Program at Columbia University's Journalism School. 
