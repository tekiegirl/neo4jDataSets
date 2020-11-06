layout: page
title: "Neo4j Data Sets"
permalink: /

# Neo4j Data Sets

Welcome to a selection of data sets and related cypher code for use with Neo4j, a graph database. These data sets and cypher queries can be used with a local, hosted or sandbox version of Neo4j.

For more information on Neo4j see [Getting started with Neo4j](https://neo4j.com/try-neo4j/)

## Using the data sets

The first thing you will need to do is have a Neo4j database instance to work on. The simplest way to do this is to go to the [Neo4j Sandbox](https://neo4j.com/sandbox/?utm_source=tekiegirl) where you can try Neo4j for free online, with no set-up required. Otherwise please refer to [Getting started with Neo4j](https://neo4j.com/try-neo4j/) for other ways of getting started with a Neo4j database.

Each data set has its own folder, titled the name of the data set (e.g. [MusicGraph](https://github.com/jacquibo/neo4jDataSets/tree/main/MusicGraph)) which contains the data set, in one or more csv files, and the respective Cypher code in a txt file with the same name as the csv file.

The csv files are hosted and accessible via this GitHub repo, but you do have the option of copying the files locally so you can use them offline. You will need to remember to change the path in the Cypher code to your local path before executing it though.

## Using a data set in Neo4j Sandbox
1. If you haven't already doen so go to [Neo4j Sandbox](https://neo4j.com/sandbox/?utm_source=tekiegirl), click Launch the Free Sandbox and follow the instructions.
2. Click on the empty option when asked what data you would like to use.
3. Open the neo4jDatSets data set folder, in this repository, that you would like to work with and open the txt file with the same name as the csv file you want to import into Neo4j.
NOTE: some data sets need to be run in order so that the relationships between data can be created. If the files in a data set are numbered you will need to run the cypher in the txt files in that order.
4. Copy the Cypher code from the txt file and past it into the prompt at the top of the Neo4j Sandbox browser, and press the play button in the top right corner.
NOTE: Many of the Cypher queries in the txt files will have a return statement so you will see nodes or properties that have been created. If the query does not have a return statement then you will see a summary of what the query did, e.g. number of nodes, properties and relationships created.
5. Once you have used all the Cypher in the txt files in the data set folder you can use the following to view the entire graph that has been created in your sandbox
`MATCH (n) RETURN n`

You can now explore your data set using your own Cypher Queries (see [Getting started with Cypher](https://neo4j.com/developer/cypher/), using any example Cypher queries in the data set folder (usually called exampleCypher.txt) or visually using the query above to show the whole graph and clicking and dragging the nodes and relationships displayed in the browser.

## Contributions, Feedback or Issues?
- Please feel free to make a [pull request](https://github.com/jacquibo/neo4jDataSets/pulls) if you wish to contribute, or fork and make changes in your own repository (please read the [project license](https://github.com/jacquibo/neo4jDataSets/blob/main/LICENSE) first)
- Any issues can be reported in the [project Issues](https://github.com/jacquibo/neo4jDataSets/issues)
- Feel free to [contact me](https://github.com/jacquibo) with feedback :D
