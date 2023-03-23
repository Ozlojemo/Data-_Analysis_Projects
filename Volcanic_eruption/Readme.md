# Volcanic eruptions analysis and findings

![Volcanic eruption](https://c.files.bbci.co.uk/113D1/production/_110090607_gettyimages-512766800.jpg)

## Code generation assumptions and method.
The code begins by importing necessary libraries including pandas, geopandas, shapely.geometry, matplotlib.pyplot, and seaborn. Two datasets containing information on volcanoes and their eruptions are then loaded from URLs using pandas read_csv function. 
The volcano data is then transformed into a geodataframe by creating a point column from longitude and latitude columns using the shapely library. 
The eruption data is also transformed into a geodataframe using a similar approach.
The volcano and eruption datasets are merged using the pandas merge function to create a new dataset, and missing values are checked using the isna() and sum() functions.
Five visualizations are created using matplotlib and geopandas. The first visualization shows the primary types of volcanoes that have the highest effects on population. 
The second visualization shows the tectonic plates around the globe by combining the dataset with the available data from the geopandas datasets. 
The third visualization shows the distribution across the globe using size difference. 
The fourth visualization shows the locations of the most active volcanoes since 1800, and the fifth visualization shows the frequency of eruptions per month worldwide for a chosen year
## Key analysis and findings
