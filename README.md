# Gowalla Network Analysis

* final project for CSC 481, in collaboration with [Ayan Patel](https://github.com/ayanpatel)
* Dataset: Gowalla (Stanford SNAP Data) https://snap.stanford.edu/data/loc-Gowalla.html 

* Read *Project Model* to see how the data is structured
* Read *Final Paper* for details on the Network Analysis
* Open `project.ipynb` to see the project code for data collection and analysis

## About 

Gowalla is a location-based social networking website where users share their locations by checking-in. The friendship network is undirected and was collected using their public API, and consists of 196,591 nodes and 950,327 edges. We have collected a total of 6,442,890 check-ins of these users over the period of Feb. 2009 - Oct. 2010. Using the user friendship table and the total check ins table we are able to generate some new data and create a graph representation that we can use to answer some questions. Our questions have three main categories: Popularity, Location, and Time. 
1. Popularity 

   * Who is the most influential / popular person? 
   * Given a user, which other users are friends with them? 
   * How many groups, or clusters, are present that are strongly connected? 
2. Location 
   * What is the most popular location? 
   * How are locations connected? 
   * Where do similar groups of people meet up? 
   * Are certain locations clustered? 
3. Time 
   * What time is a popular time for people to meet? (Check in terms of hours) 
   * Are most of the people that checkin at a given place and time friends? 
   * What time do people meet at different locations? 

The article tied to the dataset focuses on how long distance travel influences social networks, specifically what motivates a user to travel. Their choice of extracting data from Gowalla makes sense because Gowalla users were active in several different countries and many users use Gowalla in several countries (perhaps to document where they went on vacation). Our research will focus more on the centrality of social network groups as well as the centrality of popular locations. However our research will be similar to the paper’s research in the sense that we are going to be observing social networks on a global scale.