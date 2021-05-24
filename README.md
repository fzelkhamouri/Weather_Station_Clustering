# Weather_Station_Clustering

##### DBSCAN is specially very good for tasks like class identification on a spatial context. The wonderful attribute of DBSCAN algorithm is that it can find out any arbitrary shape cluster without getting affected by noise. For example, this following example cluster the location of weather stations in Canada. <Click 1> DBSCAN can be used here, for instance, to find the group of stations which show the same weather condition. As you can see, it not only finds different arbitrary shaped clusters, can find the denser part of data-centered samples by ignoring less-dense areas or noises.

##### let's start playing with the data. We will be working according to the following workflow:

#### Loading data
#### Overview data
#### Data cleaning
#### Data selection
#### Clusteing

## About the dataset
### Environment Canada Monthly Values for July - 2015 
#### Name in the table	Meaning
##### Stn_Name|	Station Name
##### Lat|	Latitude (North+, degrees)
##### Long|	Longitude (West - , degrees)
##### Prov|	Province
##### Tm|	Mean Temperature (°C)
##### DwTm|	Days without Valid Mean Temperature
##### D|	Mean Temperature difference from Normal (1981-2010) (°C)
##### Tx|	Highest Monthly Maximum Temperature (°C)
##### DwTx|	Days without Valid Maximum Temperature
##### Tn|	Lowest Monthly Minimum Temperature (°C)
##### DwTn|	Days without Valid Minimum Temperature
##### S|	Snowfall (cm)
##### DwS|	Days without Valid Snowfall
##### S%N|	Percent of Normal (1981-2010) Snowfall
##### P|	Total Precipitation (mm)
##### DwP|	Days without Valid Precipitation
##### P%N|	Percent of Normal (1981-2010) Precipitation
##### S_G|	Snow on the ground at the end of the month (cm)
##### Pd|	Number of days with Precipitation 1.0 mm or more
##### BS|	Bright Sunshine (hours)
##### DwBS|	Days without Valid Bright Sunshine
##### BS%|	Percent of Normal (1981-2010) Bright Sunshine
##### HDD|	Degree Days below 18 °C
##### CDD|	Degree Days above 18 °C
##### Stn_No|	Climate station identifier (first 3 digits indicate drainage basin, last 4 characters are for sorting alphabetically).
##### NA|	Not Available
