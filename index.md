## Suggesting the Most Livable City in the US for you

---

See projects in detail:
[This Project's Repo](https://github.com/skyrockets-21/Livable-Cities) \
[Back to my GitHub Homepage](https://skyrockets-21.github.io/) \
[Go to my LinkedIn Page](https://www.linkedin.com/in/thomasyctam/) 

---

![image](https://user-images.githubusercontent.com/22537687/152666033-a97da2d3-b008-4cf4-8493-92fbe2f296d0.png)


### Introduction
The COVID-19 pandemic has reshaped many facets of Americans’ lives, and coupled
with the prevalence of remote-work enabling technologies, it has driven workers in
certain industries or positions to choose to relocate.

To assist users in their relocation decision-making process, the team has created an application
that manipulates and visualizes data regarding the “livability” of major cities in the U.S. The
‘Livability’ is calculated based on user-weighted scores of six dimensions: Environment, Job,
Education, Leisure & Accessibility, Safety, and Affordability. Users can select their current city
and weightings for all six dimensions. The application produces a bubble map, a table, and a
radar plot of cities with their livability scores and ranks for city comparison, thereby facilitating
users’ decision-making.

### Python Libraries Used
|#| Library Name| Usage|
|--|--|--|

|1 |Pandas |Data manipulation
|2 |Numpy |Data manipulation
|3 |Beautiful Soup |Pulling data from scraping static web pages
|4 |folium |Visualizing data on the map
|5 |Plotly |Visualizing data
|6 |ipywidgets |User interface’s interactive components
|7 |Request |an HTTP library for page download
|8 |Json |API


### Data Sources Used
|Category |Attribute	|Source 	|URL
|--|--|--|--|

|City	|Cities rank by population	|.xlsx 	|https://www2.census.gov/programs-surveys/popest/tables/2010-2019/cities/totals/SUB-IP-EST2019-ANNRNK.xlsx 
|City|State Abbreviation 	|.xls	|https://www3.epa.gov/ttnairs1/airsaqsORIG/manuals/State%20and%20County%20Codes.xls 
|City	|Coordinates	|API	|https://developer.mapquest.com/documentation/open/ 
|City	|Zip Code	|CSV	|https://simplemaps.com/data/us-zips
|Environment| Air quality index - PM2.5	|API	|https://docs.airnowapi.org/
|Environment|Safe drinking water violation %	|CSV	|https://www.sustainabledevelopment.report/reports/2019-us-cities-sustainable-development-report/
|Job	|Job Opportunity	|Web scraping	|https://wallethub.com/edu/best-cities-for-jobs/2173 
|Education 	|Education index	|Web scraping	|https://wallethub.com/edu/e/most-and-least-educated-cities/6656 
|Safety|	Safety score|Web scraping	|https://wallethub.com/edu/safest-cities-in-america/41926 

&copy; Thomas Tam
