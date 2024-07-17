# OSU-AI-Bootcamp-Group-Project-1-Group-4
OSU AI Bootcamp-Group Project 1-For Group 4


Thursday, July 11, 2024-
Geolocated the Whole Foods Locations from Google Places, created the Whole_Foods_Market_Locations.csv, then put these locations into a map-Whole_Foods_Market_Map.html (These are in the "Resources" Folder). 
Also created the Google_Places_Whole_Foods_Scrape.ipynb

Called the Census API to retrieve American Community Survey (ACS) 5-Year Estimates
for Educational Attainment, 2020 at Census Tract level, for Ohio, and put the .csv in the Resources Folder.

Monday, July 15th, 2024-
Downloaded Total Population data, merged that with the Educational Attainment Data, then concatenated that data output with the corresponding key/shell headers. Filtered Ohio Whole Foods Market Locations, made a map of the points, and exported a shapefile.

Wednesday, July 17th, 2024-
If you want to do Spatial Analysis and learn GIS I suggest downloading QGIS - An Open Source GIS Platform.

QGIS Download: https://qgis.org/download/
Note: May have to adjust security settings to allow Unknown Software.

The training manual can be found here:
https://docs.qgis.org/3.34/en/docs/training_manual/index.html

QGIS Community Support can be found here:
https://www.qgis.org/resources/support/

DISCLAIMER!: !DO NOT USE THE APP TELEGRAM! EVER! EVER! EVER! 
!THIS IS THE DARK WEB! !DO NOT USE IT! !YOU'VE BEEN WARNED!

Tasks:

Joined ACS_5_Year_Census_Tract_Edu_Attain_Total_Pop.csv to the tl_2020_39_tract Shapefiles, which are the ACS 5 Year, 2020, Census Tract Shapefiles, for the State of Ohio.

Created Centroids of Polygons and Relevant .csv's/xlsx files for analysis.

Created 20 Minute Drive Time Polygons.

Exported the Census Tracts that fell within these Polygons as Shapefiles and .csv's/xlsx files for analysis.

Specifically:

The Census_Tract_Centroid_Ohio_Plus_Edu_Pop.csv/xlsx contains data on Education and Population, but also has the Lat/Long for all the Census Tract Centroids for the State of Ohio.

The WF_Census_Tracts_Within_20Min_DT_Ohio_Centroid.csv/xlsx contains data on Education and Population, but also has the Lat/Long of all the Census Tract Centroids that fall within
the 20 Minute Drive Time Polygons from the Ohio Whole Foods Market Locations.


