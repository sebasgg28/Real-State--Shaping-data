# Real State  Shaping data
 
## Introduction
This projects porpuse is to integrate different data sources into 1. The original dataset includes basic information about real state properties in Melbourne such as address, coordinates, size and price. From different data sources it is created a more robust dataset the contains:

<br><br>-Suburb coordiantes
<br>-Suburb council
<br>-Average crime rate by type of crime
<br>-Closest schools
<br>-Rancking of closest schools
<br>-Identifying overpriced houses compared to average price
<br>-Finding closes train station with direct service to Southern Cross
<br>-Travel time to CBD

*Note for the routes such as travel time to CBD we used the PTV timetable that can be downloaded here: https://discover.data.vic.gov.au/dataset/ptv-timetable-and-geographic-information-2015-gtfs

## Libraries used:
* `pandas`
* `datetime`
* `ast`
* `numpy`
* `sklearn`
* `networkx`
* `Geopandas`
* `Re`

Finally, the data is reshaped to be able to visualize it as a whole.
