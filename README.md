# MountainCirclesData
map and qgis project data for Mountain Circles visualisation

Due to file size limitation on github, here are only:
- The main QGIS file, constructing the final map when you link all the required data files
- the peaks file
- the mountain passes file
- the cities file

All remaining files can be found in the data folder on https://drive.google.com/drive/folders/1fr68iDfBMsFurlEx9bBe8ZorvOEG9Lc7?usp=share_link


The peak and mountain pass files contain way more data that is shown on the final map, in order to allow quick modifications of which ones we want to see, and which ones we want to hide.

They all have a "classe" field. classe = 1 are displayed, classe = 2 are hidden. Toogle the class to modify the output.

The cities all have a field with their population, as well a field with the population of the biggest cities in a radius of 10, 5, and 2.5km around them, to allow sorting depending on zoom level.

