INFM600 - Information Organization
=======
This Project contains datasets and anaylsis of elementary schools and correlation of the number of schools with population in a zipcode.

Verison
-------------
Version 1.0 (October 2015)

Documentation
-------------

* [Maryland_Census_Population](https://github.com/Rameshb-umd/INFM600/blob/master/Maryland_Census_Population.xls)
        File provides information on population for each zipcode in the state of Maryland.
* [Schools_Elementary_and_Population](https://github.com/Rameshb-umd/INFM600/blob/master/Schools_Elementary_and_Population.xls)
        File Provides information on the correlation between population and number of schools in a zipcode.
* [Schools_Elementary](https://github.com/Rameshb-umd/INFM600/blob/master/Schools_Elementary.xls)
        File Provides list of Elementary schools in a zipcode for the state of Maryland
* [Process Document](https://github.com/Rameshb-umd/INFM600/blob/master/ProcessDocument.pdf)
        Process document explaining how the data was merged to perform the data analysis
* [License](https://github.com/Rameshb-umd/INFM600/blob/master/LICENSE)
        License under which the derived data is distrubuted

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
Analysis
-----------


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