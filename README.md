#### NYU CUSP Capstone Fall 2021
### Mapping and Analyzing the Impact of Urban Agriculture in New York City
#### Nico Ampuero, Jeremy Rucker, Xiaolin Li

[Project website](https://ampu3ro.wixsite.com/mapnyc)

----

#### Platform
Mapping Agricultural Production in New York City (M.A.P. NYC) is a project led by Stern’s Center for Sustainable Business that aims to help the city and its partners reach equity and sustainability goals by cataloging all food growers within the city and mapping their attributes on a web-based platform. 

Our CUSP team performed research for the project and developed the [platform](https://mapnyc.herokuapp.com/), which provides administrative infrastructure for the city, crowdsources new data for future academic research, and creates a functional interface between urban farmers, city agencies, and community members. Code for the platform lives in a separate Github [repository](https://github.com/ampu3ro/mapnyc) as it will likely be passed on to a new development team in the near future.

#### Analysis
Additionally, the statistical analysis described in our capstone report presents an innovative perspective on the role of urban agriculture, and social infrastructure more broadly, in surrounding communities. Specifically, we explore spatial relationships between non-commercial agriculture, social infrastructure, and an approximate measure of subjective well-being across census tracts in New York City.


#### Data
All data and scripts referenced in our research are in this repository. We used [Google Colab](https://colab.research.google.com/?utm_source=scs-index) to run Python in the cloud, but it is possible to run any of the notebooks locally by skipping the `drive.mount` cell in each and referencing the path where the repository is downloaded/cloned. 

Files in the **/urban_agriculture** directory pertain to building the list of farms and gardens (output as _urban_ag.csv_) used on the platform and in our analysis. Those in the **/social_infrastructure** directory pertain to building a feature set (output as _social.csv_) for the modeling described in our report. 

This table includes data for ~2k census tracts in NYC and 30 variables representing social infrastructure, violent crime, voting and census participation, and other socioeconomic factors. We hope it also proves useful for future academic or policy research.

#### Modeling
Linear, non-linear and geographically weighted regression models detailed in the report are all in _models.ipynb_
