## Limitations
The graph database structure itself is in a half-baked state, I've decided to start using an actual (de-identified) medical database instead of a 6 patient excel file, so the changes that were being made in progress on this graph database are not completely finished. The excel file will also be provided in the GitHub. New graph database updates will be pushed to Patient-Graph-Database-2, which will utilize MIMIC III database provided by MIT.

## patients-database
This is the first of two graph databases and graph database applications that I've created. This one is more of a rough draft for the upcoming graph database that utilizes MIT's MIMIC III demo database. The main code is located in the neo4j/main folder.

The Patient Database uses Neo4J and has two functions - the first creates a sample graph database using Neo4J's embedded Java library. Then, after creating the graph database, it opens a Java application that allows users to easily query the graph database.

Graph Database 2 will optimize the connections between data points (and utilize far more data) than this first graph database, as well as provide a cleaner and even easier way to query the data.

## The Graph
![alt text](https://i.imgur.com/S5YRuqw.png)

## The Application
![alt text](https://i.imgur.com/vuxdNVJ.png)

## Motivation
This first patient database is part of learning about Graph Databases and potential utilizations for them.

## Technology Stack
Neo4J, Java, Apache POI

## Contributor

**andrew**

## License
A free and open source project.
MIT © [andrew]()
