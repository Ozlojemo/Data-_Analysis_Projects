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
## Key itmes to note on volcanic eruptions

Volcanic eruptions are natural phenomena that occur when magma, ash, and gas are released from a volcano. These eruptions can be explosive or effusive in nature, depending on the type of volcano and the viscosity of the magma.

Explosive eruptions occur when gas-rich magma is violently ejected from the volcano, sending ash, rocks, and other debris high into the air. These eruptions can be very destructive and can cause significant damage to the surrounding area.

Effusive eruptions, on the other hand, occur when less viscous magma flows relatively calmly out of the volcano, often creating lava flows that can be slow-moving or fast-moving depending on the slope of the volcano.

Volcanic eruptions can also release gases such as carbon dioxide, sulfur dioxide, and hydrogen sulfide, which can have harmful effects on the environment and human health.

It's important to note that volcanic eruptions can be difficult to predict, and can occur suddenly and without warning. Scientists monitor volcanoes around the world to try to predict when an eruption may occur and take steps to mitigate the potential damage.

## Data Exploration and Findings

### 1. The category of volcanoes that have the highest effects on population. 

From the study I was are able to identify that volcano type Stratovolcano(es) has the highest effect on population

### 2. Visualization of the tectonic plates around the globe

I was able to visualize the tectonic plates around the globe using the above already defined code concept

### 3.Locations of most active volcanoes since 1800

I was able to establish the regions and locations with the most active volcanoes. This were mainly the Japan,Indonesia,United States,Russia and
Iceland 




