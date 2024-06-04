# Urban spatial order: street network orientation, configuration, and entropy

### Objective: 
To get hands-on experience in implementing clustering techniques on real-world datasets 

###  Introduction: 
The paper explores how street network configurations shape urban space worldwide, analyzing 100 cities to measure orientation entropy, circuity, and connectedness. 
It introduces a new indicator, orientation-order φ, revealing significant relationships between city orientation and spatial order, with most cities exhibiting a tendency towards north-south-east-west orientation, particularly notable in American cities.

### Background: 
The paper "Urban Spatial Order: Street Network Orientation, Configuration, and Entropy" by Geoff Boeing examines street network patterns across 100 global cities. 
It utilizes OpenStreetMap data and OSMnx software to analyze street orientations and configurations. 
The study focuses on the entropy of street bearings and other metrics like average street segment length, circuity, node degree, and proportions of intersections and dead-ends. 
It also introduces a new measure, orientation-order, to quantify a city's grid-like structure. 
Statistical relationships between street orientation-order and other spatial order indicators are explored, revealing distinctive patterns in different regions, particularly between U.S./Canadian and other cities. 
The research provides insights into urban design and planning, highlighting the complexity and patterns of urban transportation systems worldwide. 

### Data:
https://appliednetsci.springeropen.com/articles/10.1007/s41109-019-0189-1

### Key Parameters:
φ is the orientation-order indicator, 
Ηo represents street orientation entropy, 
Ηw represents weighted street orientation entropy, 
ĩ represents median street segment length (meters), 
ς represents average circuity, 
k̅ represents average node degree, 
Pde represents the proportion of nodes that are dead-ends, and 
P4w represents the proportion of nodes that are four-way intersections

### Tasks 

1.Read the research paper and understand the method used in the work 
2.Load the urban navigation data set (Table 1) 
3.Preprocess the data (if necessary), such as normalizing or scaling the features 
4.Find out why we need to maintain a uniform scale across the variables for K-means and Hierarchical clustering 
5.Do we need to use scaling techniques for this dataset? 
6.Implement K-means clustering to categorize the data into clusters 
7.Use elbow method to determine number of clusters 
8.Implement Hierarchical clustering using an appropriate linkage method 
9.Try all the linkage criteria 
10.Plot the dendogram for each criteria 
11.For aforementioned methods generate the clustering solution. The clustering solution simply groups the counties into different groups based on similarity.
12.Investigate and comment on the clusters






