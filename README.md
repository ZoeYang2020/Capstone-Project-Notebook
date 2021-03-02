# Capstone-Project-Notebook
This is my Capstone Project Notebook
###The Battle of Neighborhood_Job design###

Question:Find the most convenient place for a fiend to live in Toronto.

My friend Lin who will relocate from BeiJing to Toronto. She is asking my suggestion where is the most convenient for her to live. Lin likes doing exercise and enjoys going out for dinner. So the regions that she prefers to live needs to be close to gyms, parks, as well as restaurant.

Method: The list of neighbourhoods is scrapped from Wikipedia, using the library BeautifulSoup. Each neighbourhood's coordinates are retrieved using Geocoder. The list of venues for each neighbourhood are retrieved from FoursquareAPI. The clustering is done using a K-means algorithm. The neighbourhoods are displayed on a map using Folium, each colored for each cluster.

With this clustering method, we can see neighbourhoods that are similar using their most common types of venues. Find the regions that match Lin's requirement for setting her new home.
