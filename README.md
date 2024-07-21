# OSU-AI-Bootcamp-Group-Project-1-Group-4
OSU AI Bootcamp-Group Project 1-For Group 4


**Thursday, July 11, 2024-

Geolocated the Whole Foods Locations from Google Places, created the Whole_Foods_Market_Locations.csv, then put these locations into a map-Whole_Foods_Market_Map.html (These are in the "Resources" Folder). 
Also created the Google_Places_Whole_Foods_Scrape.ipynb

Called the Census API to retrieve American Community Survey (ACS) 5-Year Estimates
for Educational Attainment, 2020 at Census Tract level, for Ohio, and put the .csv in the Resources Folder.

**Monday, July 15th, 2024-

Downloaded Total Population data, merged that with the Educational Attainment Data, then concatenated that data output with the corresponding key/shell headers. Filtered Ohio Whole Foods Market Locations, made a map of the points, and exported a shapefile.

**Wednesday, July 17th, 2024-

If you want to do Spatial Analysis and learn GIS I suggest downloading QGIS - An Open Source GIS Platform.

QGIS Download: https://qgis.org/download/
Note: May have to adjust security settings to allow Unknown Software.

The training manual can be found here:
https://docs.qgis.org/3.34/en/docs/training_manual/index.html

QGIS Community Support can be found here:
https://www.qgis.org/resources/support/

DISCLAIMER!: !DO NOT USE THE APP TELEGRAM! EVER! EVER! EVER! 
!THIS IS THE DARK WEB! !DO NOT USE IT! !YOU'VE BEEN WARNED!

**Tasks:

Joined ACS_5_Year_Census_Tract_Edu_Attain_Total_Pop.csv to the tl_2020_39_tract Shapefiles, which are the ACS 5 Year, 2020, Census Tract Shapefiles, for the State of Ohio.

Created Centroids of Polygons and Relevant .csv's/xlsx files for analysis.

Created 20 Minute Drive Time Polygons.

Exported the Census Tracts that fell within these Polygons as Shapefiles and .csv's/xlsx files for analysis.

**Specifically:

**The Census_Tract_Centroid_Ohio_Plus_Edu_Pop.csv/xlsx contains data on Education and Population, but also has the Lat/Long for all the Census Tract Centroids for the State of Ohio.

**The WF_Census_Tracts_Within_20Min_DT_Ohio_Centroid.csv/xlsx contains data on Education and Population, but also has the Lat/Long of all the Census Tract Centroids that fall within
the 20 Minute Drive Time Polygons from the Ohio Whole Foods Market Locations.

Class Time:

The team mulled over the data, and we believe that it is in the right format. Shawn is now deciphering the ACS 5 Year Header Keys to generate a more user friendly DataSet.

Shawn also made a PowerPoint, and put it in the Presentation Folder.
This PowerPoint formulates and frames actionable questions, observations, and deliverable outcomes.

**Thursday, July 18th, 2024-

Cleaned up the Repo. May have to Refactor some code with the .ipynb file paths, if necessary.

Added a "MetaData" folder in the "Resources" folder. This is where the S1501 Series and B01003_001E MetaData is now located. I accessed this data from the ACS Census API, so I KNOW that it is correct, I AM POSITIVE.

We had labeled the fields in the S1501 Series incorrectly, and luckily these inconsistencies were quality controlled(Thanks Shawn!). With the advent of the "MetaData" folder, we can now decipher the Census fields to ensure accuracy. 

**Specifically, 

**S1501_C01_015E is the Estimate of Total AGE BY EDUCATIONAL ATTAINMENT Population 25 years and over - Bachelor's degree or higher.

**B01003_001E is the Total Population Estimate.

See MetaData.

**Friday, July 19th, 2024-

Added CARTO Mapping Application - Ohio Whole Foods Market_CARTO_Map_html to Root. Updated Slides in Presentation Folder.

**Saturday,July 19th, 2024-

Shawn ran some stats and pulled information from the data such as scatter plots and correlation matrices pertaining to Whole Foods Market Locations and Educational Attainment, Income, and Non-Family Households. He also added the visualizations to the .pptx in the Presentation Folder.

Ronald added his Mapping Slides to the .pptx Presentation, Updated the README.md file and pushed changes.
