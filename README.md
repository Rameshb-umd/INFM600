INFM600 - Information Organization

Purpose
----------

**In Howard county, how does the number of schools in a particular area correlate with the population of that area?**

In order to understand the correlation, three datasets from Howard county are considered.

* Population by zip code
* List of Elementary schools in Howard county
* List of High schools in Howard county 

By Mapping the merged dataset on a graph and comparing the population and number of schools in a zip code, we can identify the areas
in which the schools are less/higher in relation to the population.

Analysis
------------- 
![Population vs zipcode](https://github.com/Rameshb-umd/INFM600/raw/master/Result%20-%20Images/Population_vs_Zipcode.PNG)
![Schools vs zipcode](https://github.com/Rameshb-umd/INFM600/raw/master/Result%20-%20Images/numberofschools_vs_Zipcode.PNG)
![Analysis of processed data](https://github.com/Rameshb-umd/INFM600/raw/master/Result%20-%20Images/Result.PNG)

Verison
-------------
Version 1.0 (October 2015)

Table of Contents
-------------

* [Maryland Census Population](https://github.com/Rameshb-umd/INFM600/raw/master/1_Maryland_Census_Population.xls)
* [School Elementary](https://github.com/Rameshb-umd/INFM600/raw/master/2_Schools_Elementary.xls)
* [Schools Middle](https://github.com/Rameshb-umd/INFM600/raw/master/3_Schools_Middle.xls)
* [Howard County School and population analysis](https://github.com/Rameshb-umd/INFM600/raw/master/Howard%20County%20School%20and%20population%20analysis.xls)
* [Process documentation](https://github.com/Rameshb-umd/INFM600/raw/master/Process%20documentation.pdf)
* [License](https://github.com/Rameshb-umd/INFM600/raw/master/LICENSE)

Description
------------

**Maryland_Census_Population.xls** 

This dataset retrieved from **Maryland State Data Center** contains population data for each zip code in Maryland.

*Reference*
```
Maryland State Data center.(2010).Zip code Tabulation Area [Dataset]. 
Available from Maryland State Data center Web site: http://census.maryland.gov/census2010/SF1DP/cen10_SF1DP.shtml
```
**Schools_Elementary.xls**
    
This dataset retrieved from **Howard County Maryland** data portal contains list of public elementary schools in Howard county.
This dataset provides the *Name, City, Zip code and geolocation* of each public elementary schools.

*Reference*
```
Howard County Maryland. Schools-Elementary (2014)[Dataset]. 
Retrieved from https://data.howardcountymd.gov/geoserver/ows? 
service=WFS&version=1.0.0&request=GetFeature&typeName=general:Schools_Elementary&outputFormat=csv
```
**Schools_Middle.xls**
    
This dataset retrieved from **Howard County Maryland** data portal contains list of public middle schools in Howard county.
This dataset provides the *Name, City, Zipcdoe and geolocation* of each public middle schools.

*Reference*
```
Howard County Maryland. Schools-Middle (2014)[Dataset]. 
Retrieved from https://data.howardcountymd.gov/geoserver/ows? 
service=WFS&version=1.0.0&request=GetFeature&typeName=general:Schools_Elementary&outputFormat=csv
```

**Howard County School and population analysis.xls**

This dataset contains merged data from Maryland census population and Schools Elementary data.
From the original dataset only, data required to understand the correlation between population and number of school in an area
has been considered.

This dataset is released as part of INFM600, Information Environments, Fall 2015, University of Maryland ischool, http://ischool.umd.edu/mim

**How to cite this dataset**
```
Ramesh Balasekaran.(2015). Howard County School and population analysis (Verison 1.0) [Dataset].
Available from https://github.com/Rameshb-umd/INFM600
```

Data Format
-----------
    
Howard County School and population analysis.xls

| **Zipcode**   |**Count of Schools**|**Population**|
| ------------- |:------------------:| ------------:|

License
-----------
Copyright [2015] [Ramesh Balasekaran]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Author
----------
Ramesh Balasekaran.