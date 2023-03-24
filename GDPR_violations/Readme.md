# GDPR VIOLATIONS ( TACKLING PRIVACY IN THE NEW INFORMATION AGE)

![GDPR Violations](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTM0K3EIWD8V_VlXOK-hSm_zu53f3tuXhi-bg&usqp=CAU)

## Introduction to GDPR Violation

The General Data Protection Regulation (GDPR) is a regulation in the European Union that aims to protect the privacy and personal data of EU citizens. GDPR sets out specific requirements for organizations that collect, process, and store personal data, and it imposes significant penalties for non-compliance.

Some common GDPR violations include:

i)Failure to obtain proper consent: Companies must obtain clear and explicit consent from individuals before collecting or processing their personal data.

ii)Inadequate data protection measures: Organizations must implement appropriate technical and organizational measures to ensure the security and confidentiality of personal data.

iii)Non-compliance with data subject rights: Individuals have the right to access, correct, and delete their personal data, and organizations must comply with these requests in a timely manner.

iv)Transferring data outside the EU without proper safeguards: Organizations must ensure that personal data is protected when it is transferred outside the EU.

v)Failure to report data breaches: Companies must notify the relevant authorities and affected individuals in the event of a data breach.

vi)Penalties for GDPR violations can be severe, with fines of up to €20 million or 4% of a company's global annual revenue, whichever is higher. It's important for organizations to take GDPR compliance seriously and implement appropriate measures to protect personal data.


# Code derivation and execution concept

The code begins with importing the necessary libraries, including Pandas for data manipulation, GeoPandas for working with geospatial data, Matplotlib for data visualization, Seaborn for statistical graphics, and Folium for creating interactive maps.

The code then reads in GDPR violations data from a URL and stores it in a Pandas DataFrame called "Violations". The data includes information about GDPR violations by companies in the European Union.

i)Time breakdown of the total violations in the EU:
The code first converts the date column in the DataFrame to Pandas datetime format, groups the data by year and month, and counts the number of violations for each group. The resulting table is then plotted as a bar graph to show the time breakdown of the total violations in the EU.

ii)Most expensive violation by country:
The code groups the data by country and finds the maximum fine for each country. The top 10 most expensive violations by country are then plotted as a bar graph.

iii)Vodafone's GDPR violations in volume:
The code first sorts the DataFrame by the controller column to group all Vodafone companies together. It then creates a subset of the data that includes only Vodafone companies and counts the number of GDPR violations. The resulting count is printed to the console.

iv)Companies with the highest violations:
The code finds the top 10 companies with the highest number of GDPR violations and creates a horizontal bar chart to visualize the results.

v)Map the data and make this interactive:
The code loads a world shapefile into a GeoDataFrame and merges the violations data with it on the country names. It then creates an interactive choropleth map using GeoPandas and Matplotlib to show the number of GDPR violations by country.

vi)Breakdown/Distribution and important metrics of fines levied per article:
The code groups the data by the article violated and calculates various metrics, including count, sum, mean, median, minimum, maximum, and percent of total fine. It then finds the top 5 most frequently violated articles, filters the data to include only these articles, and creates a boxplot of fines per article using Seaborn.

vii)Top 10 most violated articles:
The code gets the value counts of the article violated column and finds the top 10 most frequently violated articles.
