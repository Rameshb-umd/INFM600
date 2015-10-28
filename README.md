INFM600 - Information Organization

Purpose
----------

**In Howard county, how does the number of schools in a particular area correlate with the population of that area?**

In order understand the correlation, three datasets from Howard county are considered.
    * Population by zip code
    * List of Elementary schools in Howard county
    * List of High schools in Howard county    
By Mapping the merged dataset on a graph and comparing the population and number of schools in a zip code, we can identify the areas
in which the schools are less/higher in relation to the population.

Analysis
------------- 
![Analysis of processed data](https://raw.githubusercontent.com/Rameshb-umd/INFM600/master/Result.PNG "Result")

Verison
-------------
Version 1.0 (October 2015)

Table of Contents
-------------

* [Maryland Census Population](https://github.com/Rameshb-umd/INFM600/blob/master/Maryland_Census_Population.xls)
* [Schools Elementary and Population](https://github.com/Rameshb-umd/INFM600/blob/master/Schools_Elementary_and_Population.xls)
* [Schools Elementary](https://github.com/Rameshb-umd/INFM600/blob/master/Schools_Elementary.xls)
* [Process Document](https://github.com/Rameshb-umd/INFM600/blob/master/ProcessDocument.pdf)
* [License](https://github.com/Rameshb-umd/INFM600/blob/master/LICENSE)

Description
------------

Maryland_Census_Population.xls 

This dataset retrieved from **Maryland State Data Center** provides population information based on zipcodes for the state of maryland.

**Reference**
```
Maryland State Data center.(2010).Zip code Tablulation Area [Data file and code book]. 
Available from Maryland State Data center Web site: http://census.maryland.gov/census2010/SF1DP/cen10_SF1DP.shtml
```
Schools_Elementary.xls
    
This dataset retrieved from Howard county Maryland data portal provides information on schools located in a zipcode.
The information are tabulated by *Name, City, Zipcdoe and geolocation*.

**Reference**
```
Howard County Maryland. Schools-Elementary (2014)[Data file and code book]. 
Retrieved from https://data.howardcountymd.gov/geoserver/ows? 
service=WFS&version=1.0.0&request=GetFeature&typeName=general:Schools_Elementary&outputFormat=csv
```

Schools_Elementary_and_Population.xls

This dataset contains merged data from Maryland census population and Schools Elementary data.
From the orginal dataset only, data required to understand the correlation between population and count of school in a area
has been considered.

This dataset is released as part of INFM600, Information Environments, Fall 2015, University of Maryland ischool, http://ischool.umd.edu/mim

**How to cite this dataset**
```
Ramesh Balasekaran.(2015). _Howard County School and population analysis (Verison 1.0)_ [Data file and code book].
Retrieved from https://github.com/Rameshb-umd/INFM600/blob/master/Schools_Elementary_and_Population.xls
```


Data Format
-----------
    Schools_Elementary_and_Population.xls
    | Zipcode       | Count of School| Population |
    | ------------- |:--------------:| ----------:|

License
-----------
Copyright [2015] [Ramesh Balasekaran]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Author
----------
Ramesh Balasekaran.