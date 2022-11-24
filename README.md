# Routes-Against-Harassment
Data science project aimed at calculating a safer route regarding street harassment given two points in the city. The proposed solution yields three different paths: the first the shortest, the second with the least probability of street harasssment and the third with its average.

Made in python with the help of Geopandas, Jupyter Notebook, Network X

Explanation of the software

1. Given the information of each street in the city of Medellin, Colombia, a graph is created
2. Dijkstra's algorithm is applied based on attribute length, harassment risk and an average of the two.
3. THe three paths are graphed with the helped of GeoPandas.
