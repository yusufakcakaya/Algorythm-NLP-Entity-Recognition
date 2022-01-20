# Algorythm-NLP-Entity-Recognition 🗣 🤖 🎖

![image](https://user-images.githubusercontent.com/46165841/150334441-70aa2e5d-a1e7-43d3-a268-fb7c8182c97b.png)

## The Mission

This project aims to reveal the entity relations by randomly selecting data from ``from nltk.corpus import reuters`` data sets and transferring the relationships that emerged after the obtained text information extraction pipeline to the graphical database in neo4j.

![image](https://user-images.githubusercontent.com/46165841/150346744-2bf84de3-db34-4fdf-9c63-4123c9d7b02d.png)

**Text Cleaning :** Text cleaning is the process of preparing raw text for NLP (Natural Language Processing) so that machines can understand human language.

**Named-entity Recognition :** (NER)is an information extraction that seeks to locate and classify named entities in text into pre-defined categories such as the names of persons, organizations, locations, expressions of times, quantities, monetary values, percentages, etc.

![image](https://user-images.githubusercontent.com/46165841/150347262-1ae6a8fb-419d-4b89-9702-a133079eb22f.png)

**Coreference Resolution :** Coreference resolution is high useful task which is refer to the same entity in a text. It is an important part for the NLP projects to understanding such as document summarization, question answering, and information extraction

**Entity Linking :** Entity linking is the name we give as long as we find the connection between entities such as names of persons, organizations, locations, expressions of times, quantities, monetary values, percentages, which emerge after performing named-entity recognition.

**Relationship Extraction :** Relationship extraction is the task of extracting semantic relationships from a text. Extracted relationships usually occur between two or more entities of a certain type (e.g. Person, Organisation, Location) and fall into a number of semantic categories (e.g. married to, employed by, lives in)

**Graph :** The knowledge graph is created by Neo4j. Neo4j stores and manages data in its more natural, connected state, maintaining data relationships that deliver lightning-fast queries, deeper context for analytics and hepls us to understand relations.

#### How to reach the data?
You can find out how to use the data by clicking this link. [Reuters](https://www.cs.bgu.ac.il/~elhadad/nlp17/ReutersDataset.html)
- This dataset contains the text of 10,788 news documents totaling 1.3 million words and is publicaly available.


## Installation

- Pull requests are welcome.
- or clone ```https://github.com/yusufakcakaya/Algorythm-NLP-Entity-Recognition.git```

## Repo Architecture 

```
Algorythm-NLP-Entity-Recognition
│
│   
│  
│__ __ deployment              : pip environment
│
│__ __ static                  : static image file
|
|__ __ templates               : templates for Flask
|
|__ __ Dockerfile              
|
│__ __ Procfile                : for Heroku
│
│ 
│__ README.md                  : explains the project
│
|
│__ app.py                     : main file for flask
│  
│__ data_cleaning.ipynb        : data cleaning file
│
│__ database.json              : main data .json
│                
│__ games.db                   : flask database
│

```


## Visuals

Same visualisations:

![newplot (1)](https://user-images.githubusercontent.com/46165841/147486469-4b8ce8a4-6011-4598-a5be-d1e2aebbf1bf.png)

![newplot (2)](https://user-images.githubusercontent.com/46165841/147486500-7b51b3ac-bece-4df4-9168-94e00f277ca2.png)

## Collaborators

Design and construction phase of the project was made by 3 collaborators.([Arfa Meher](https://github.com/Arfameher), [Nichelle Pinto Machado](https://github.com/N1chelle),  [Yusuf Akcakaya](https://github.com/yusufakcakaya))


## Timeline

- Type of Challenge: Learning
- Duration: 2 weeks
- Deadline: 20/01/2021 4:30 PM
- Team challenge : group

## Good Luck!
