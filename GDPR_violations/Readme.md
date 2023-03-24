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

### 4.Document your understanding of challenges (Prepare a slide providing context to your potential audience) faced in Kenya when it comes to effective implementation of the DPA.

I will prepare a slide with below co

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

## Data Exploration and Findings

### 1.Explore the provided data and understand the business context by doing research on Data Protection and Privacy regulations locally and globally.

The provided data contains information on customers who purchased items from an e-commerce store. The dataset includes information such as customer names, email addresses, phone numbers, items purchased, and the amount spent.

In Kenya, the Data Protection Act was enacted in 2019, and it sets out rules and regulations on the processing of personal data. The Act requires organizations that collect and process personal data to ensure that such data is obtained and processed lawfully, transparently, and for specific, explicit, and legitimate purposes. The Act also requires organizations to obtain consent from individuals before collecting and processing their personal data and to provide individuals with access to their personal data upon request.

Globally, there are various data protection and privacy regulations, such as the General Data Protection Regulation (GDPR) in the European Union (EU) and the California Consumer Privacy Act (CCPA) in the United States. These regulations provide guidelines and rules for the collection, use, and protection of personal data, including requirements for obtaining consent, ensuring data accuracy, and providing individuals with access to their data.

Based on the provided and analysed data, it is important for the organizations to ensure that they are compliant with local and global data protection and privacy regulations. This can include obtaining consent from customers before collecting and processing their personal data, ensuring that the data is accurate and up-to-date, and providing customers with access to their data upon request. The organizations should also ensure that appropriate measures are in place to protect the data from unauthorized access or disclosure.

### 3.Obtaining an understanding of what are the implications of non-compliance and the core principles of the Data Protection Act.

Based on the analysis of the provided data and the business context, the implications of non-compliance with data protection and privacy regulations can be severe. Non-compliance can lead to legal and financial penalties, reputational damage, loss of customer trust, and potential business closure.

In Kenya, the core principles of the Data Protection Act include:

i)Lawfulness, fairness, and transparency: Personal data must be processed lawfully, fairly, and in a transparent manner.

ii)Purpose limitation: Personal data must be collected for specified, explicit, and legitimate purposes and not processed in a manner that is incompatible with those purposes.

iii)Data minimization: Personal data must be adequate, relevant, and limited to what is necessary in relation to the purposes for which they are processed.

iv)Accuracy: Personal data must be accurate and, where necessary, kept up to date.

v)Storage limitation: Personal data must be kept in a form that permits identification of data subjects for no longer than is necessary for the purposes for which the personal data are processed.

vi)Integrity and confidentiality: Personal data must be processed in a manner that ensures appropriate security, including protection against unauthorized or unlawful processing and against accidental loss, destruction, or damage.

Globally, data protection and privacy regulations vary by country, but many share similar core principles, including:

i)Transparency: Individuals have the right to know what personal data is being collected, processed, and stored about them.

ii)Purpose limitation: Personal data must be collected for specified, explicit, and legitimate purposes and not processed in a manner that is incompatible with those purposes.

iii)Data minimization: Personal data must be adequate, relevant, and limited to what is necessary in relation to the purposes for which they are processed.

iv)Accuracy: Personal data must be accurate and, where necessary, kept up to date.

v)Storage limitation: Personal data must be kept in a form that permits identification of data subjects for no longer than is necessary for the purposes for which the personal data are processed.

vi)Integrity and confidentiality: Personal data must be processed in a manner that ensures appropriate security, including protection against unauthorized or unlawful processing and against accidental loss, destruction, or damage.

### 4.Document your understanding of challenges (Prepare a slide providing context to your potential audience) faced in Kenya when it comes to effective implementation of the DPA.

I will prepare a slide with below content

Slide Title: Challenges in Effective Implementation of Data Protection Act in Kenya

Slide Content:

### Introduction:

I will briefly explain the importance of data protection and privacy regulations in Kenya taking key points already discussed above.

### Lack of Awareness and Understanding:

i)Many organizations and individuals are still not aware of the requirements of the Data Protection Act.
ii)Lack of understanding of the law has resulted in non-compliance and a low level of protection for personal data.

### Inadequate Resources:

i)Limited resources allocated towards the implementation of the Data Protection Act by both public and private sectors.
ii)Inadequate funding and training opportunities for organizations to implement data protection measures.

### Limited Enforcement Mechanisms:

i)The lack of clear guidelines for enforcement of the Data Protection Act has led to inconsistent enforcement of the law.
ii)Limited resources for the regulatory body responsible for overseeing data protection in Kenya has led to slow enforcement actions.

### Cultural and Social Challenges:

i)Social and cultural attitudes towards privacy and data protection may hinder effective implementation of the Data Protection Act.
ii)The reluctance of individuals to share personal data due to mistrust and fear of data misuse.

### Conclusion:

Effective implementation of the Data Protection Act in Kenya requires addressing these challenges to ensure the protection of personal data and compliance with the law.




