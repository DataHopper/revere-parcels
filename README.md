# Overview
This project provides an overview of the 2017 real estate tax parcel data set for the City of Revere, compiled and made available through MassGIS. There are 15,109 records in the data set, each associated with an individual parcel. Tax parcels are not the same as land parcels, however, as multiple tax parcels can exist on a single piece of land (a condo building, for example). This data set includes information for 12,780 lots (LOC_IDs). Each parcel record (PROP_ID) includes information on its assessed value, legal use, size, address, physical characteristics, and ownership information. This information can be used to explore the built environment in the City of Revere, including land use patterns, density of development, real estate transactions and valuation.

# In this repo
- Markdown that tidies, aggregates and visualizes the raw tax parcel data from the City of Revere.
- 2017 data set from MassGIS - this is a file geodatabase
- Data dictionary that includes all original fields from the MassGIS data set as well as all newly created fields from the RMarkdown file

# Fun Facts
-	The oldest structure in Revere is a two-unit garden apartment building at 22 School St, shown as built in 1696.
-	The highest density lot in Revere is located at 360 Revere Beach Boulevard. It is an 81-unit condominium building with a median assessed value of $277,000.
-	Most parcels in Revere are dedicated to residential uses. Approximately 88.4% of parcels are residential, followed by 6.4% tax-exempt, 3.8% commercial, 0.8% mixed-use and 0.5% industrial.
-	Of the 13,354 residential parcels in Revere, 4,497 are single-family homes (34%), 4,345 are in 2- or 3-family homes (33%), 20% are condo units. Approximately 7.7% of residential parcels in Revere are categorized as “Undevelopable Residential Land.”
-	The parcel with the highest total assessed value in Revere is a multifamily apartment building with 412 units located at 19 Overlook Ridge Drive. This property was built in 2006, is owned by Altera II LLC located in New Jersey, and has an assessed value of over $72 million (tax year 2017).

# Visualizations

<img src="images/tm1.png"/>
<img src="images/PriceDistributions.png"/>
<img src="images/SFHomeValbySF.png"/>
