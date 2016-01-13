### TwitterMiner

•	This is a web application which allows users to enter a keyword and find distribution of related tweets across United States. 
•	Application front end is developed using JSF Framework and the back end analysis is performed by Hadoop MapReduce jobs.
•	The twitter activity in various geographic locations will be shown to the user on an interactive map, where users can zoom in and out to find percentage of tweets from each state. 
•	Users can also enter a keyword and get the sentiment associated with the keyword. 
•	Used Twitter4j to fetch tweets, Polymaps to display maps, LingPipe for sentiment analysis, and JFreeChart to display sentiment analysis results.  
•	As the core functionality of the application is implemented using Hadoop (MapReduce), the application can be easily scaled to an enterprise level to perform analysis on huge amounts of data, by using cluster computing. 
•	The only bottle neck in the current application is fetching input data from twitter. This bottleneck can be eliminated and the application can be made more effective by getting access to use Twitter Firehose.
