# Study Correlation Between the Number of Hospitals Per Person And GDP Per Capita Final Report

######  Since IBM Watson Studio free usage time has finished, I will not be able to share neither my report nor code from IBM Watson. Instead I used Jupyter Labs to write the code and attached pdf that show my work. 


###### Introduction:
###### I want to find out whether the number of hospitals per person in a country can be an indicator of country's development level. This project, by showing the number of hospitals per person in a country, may give companies that are on to hospital construction investments a first opinion on countries' position. Taking not only hospital per person, but also its relationship with GDP per capita as country's development level can provide investment fims a different parameter that can be depended on.

###### Data:
###### Since taking the hospital data in each country is not feasible, Search area is restricted with the capital cities. I took capital cities population data from wikipedia(url1: https://en.wikipedia.org/wiki/List_of_national_capitals_by_population), and GDP per capita data from CIA website(url2: https://www.cia.gov/library/publications/the-world-factbook/rankorder/2004rank.html). 

###### Methods:
###### Since I am not able to consider all the hospitals for all the capitals as datapoints. I'll choose 50 capital randomly from dataset to ensure dataset contains all kinds of countries from all development levels. The reason I selected random points is that the similar populated capitals are also belong to similar development levels. I will use foursquare to get the hospital data for the each capital. 
##### I multiplied the number of hospitals per person with 10,000 since really low numbers would give low quality results.
##### After the study, the clustering and mapping of similar countries shows possible areas to build hospitals.

##### Results:
##### Results show that there is a strong correlation between GDP per capita and number of hospitals per person but this rule is not valid for small countries like Monaco, Andora or Bahamas. 
##### Also it is found that the countries that showed strong growth in recent years have chance to be good investment areas since the number of hospitals built could not reached the GDP growth. 
