# Coursera Capstone Project - The Battle of Neighborhoods
This project is the final delivery as part of the IBM Applied Data Science Capstone course. The comprehensive project report can be found at the following Medium Article: [Data Science Capstone Project](https://medium.com/@jerrylin0505/data-science-capstone-project-fd94975d8aa3)


## A. Introduction/Business Understanding
A.1 Description of the problem
Recently, Veganism has become the most in-vogue dietary trend around the world. More and more people embrace the plan-based lifestyles. Taiwan is not excluded from this fad, especially of its capital, Taipei.

Even though the prospect of vegan dietary seems to be optimistic, the hyper-competitive essence in the catering market shouldn't be neglected.

Under this scenario, the business problem we are currently posing is:

How could we support business partners to find a location that guarantees the higher profit potential of their vegan restaurant investment in Taipei?

A.2 Discussion of the Background
As the capital and a special municipality of Taiwan, Taipei is the political, economic, educational, and cultural center of Taiwan as well as one of the major hubs in East Asia with an estimated population of 2.6 million.

Considered to be a global city, Taipei has dozens of world-class restaurants where gourmets can sample from the best traditional Taiwanese cuisine to the wide variety of exotic choices. Aside from that, there are also plenty of night markets serving up scrumptious snacks in an environment of chaotic excitement and fun.

Undoubtedly, food plays an important part in Taipei, and this has further aggravated the competition in catering industry and the discerning taste buds of Taipei people. As a matter of fact, the average annual restaurant close down rate in Taipei is around 30%, which means out of 10 restaurants, there is only 7 survive after a year. Needless to say, if we transform the scope to a longer period, operating a restaurant that generates stable profit is definitely a challenge.

Even though the rising demand for vegan dietary brings profit potential, there are lots of indices that need to be cautiously considered. So, how could we utilize machine learning to find the proper location to start the vegan business? One solution is using clustering method to group different districts by their restaurant category and leverage the result with population data. In this following paragraph, I am going to walk through the whole process of this solution.

## B. Data Requirements
Districts name in Taipei
Data source: Github
Description: Using this dictionary combines with geopy to collect the latitude and longitude data of each district so we can use this geographic data later.
Population for each district
Data source: Taipei City Government- Department of Budget, Accounting and Statistic
Description: Population distribution for each district.
Restaurants information in each district
Data source: Foursquare APIs
Description: By using this API we will get all the venues in each district. We can filter these venues to get only restaurants.
Taipei Districts Geojson
Data source: Github
Description: Geojson used for plotting choropleth map with Folium.
