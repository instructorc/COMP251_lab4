# Lab 4 - From Relational Schema to Document Databases
This lab will meet the following objectives:

1.  Distinguish the difference between a relational non-relational database schema.

2.  Interpret JavaScript object notation(JSON) data exchange format

## Instructions
For this lab, you'll explore the process of converting a relational database schema into a non-relational document schema suitable for MongoDB. You'll work with the given Album and Artist tables and learn to represent the data in JSON format.

![alt text](https://instructorc.github.io/site/slides/database/images/general/album_artist_erd.PNG)

You will use the README.md file to document your JSON code using the data listed below.
```
artistID,artistName
1,'Marvin Gaye'
2,'The Beach Boys'
3,'Joni Mitchell'
4,'Stevie Wonder'
5,'The Beatles'
6,'Nirvana'
7,'Fleetwood Mac'
8,'Prince and the Revolution'
9,'Bob Dylan'
10,'Lauryn Hill'
11,'Michael Jackson'
12,'Aretha Franklin'
13,'The Rolling Stones'
14,'Public Enemy'
15,'The Clash'
16,'Kanye West'
17,'Kendrick Lamar'

albumID,album_name,album_release_year,album_genre,album_artistID
1,'What's Going On',1971,'soul',1
2,'Pet Sounds',1966,'pop',2
3,'Blue',1971,'folk',3
4,'Songs in the Key of Life',1976,'funk',4
5,'Abbey Road',1969,'rock',5
6,'Nevermind',1991,'rock',6
7,'Rumours',1977,'rock',7
8,'Purple Rain',1984,'funk',8
9,'Blood on the Tracks',1975,'rock',9
10,'The Miseducation of Lauryn Hill',1998,'r&b',10
11,'Revolver',1966,'rock',5
12,'Thriller',1982,'pop',11
13,'I Never Loved a Man the Way I Love You',1967,'soul',12
14,'Exile on Main Street',1972,'rock',13
15,'It Takes a Nation of Millions to Hold Us Back',1988,'rap',14
16,'London Calling',1979,'rock',15
17,'My Beautiful Dark Twisted Fantasy',2010,'rap',16
18,'Highway 61 Revisited',1965,'rock',9
19,'To Pimp a Butterfly',2015,'rap',17
```

## Requirements

### Deliverable 1 - Data Definition Language (12 Points)
Review the given relational schema for tables **ARTIST** and **ALBUM**.  Convert the database schema into JSON using the data for ALBUM and ARTIST.  Consider using a syntax validator tool such as [https://jsonchecker.com/](https://jsonchecker.com/) to assist you in writing valid JSON. When documenting your code within the README.md file use the markdown syntax that allows for code to be included in your README.md file.  An example of how to implement coding markdown is listed below.  
```json
  {
      "title": "Lab 4: From Relational Schema to Document Databases",
      "point_value": 15
  }
```
  1. Proper JSON Syntax is used to format JSON data
  2. JSON Object is properly structured to represent a one-to-many relationship between **ARTIST** and **ALBUM**.
  3. All 17 JSON objects are reflected in README.md file
  4. When drafting your JSON objects, you do not need to include the artistID.

### Deliverable 2 - Reflection on relational and non-relational database schemas (3 Points)
Reflect on the differences between relational and non-relational database schemas. Consider the advantages and disadvantages of using a document-based database like MongoDB for the given data and document your reflections within this repository README.md file. 
  1. Reflections include 2 or more paragraphs
  2. Thoughtful considerations given to analysis of relational and non-relational database schemas.


## Submission Guidelines

For this lab, you will only need to update your repository README.md file with the responses for both Deliverable 1 and 2.
Once you have completed both deliverables above, you will need to submit the link to your repository for lab4 prior to the due date and time listed. 


## Lab Resources
- [Introduction to JSON Workshop slide deck](https://instructorc.github.io/site/slides/presentation/api.html)
- [JSON Schema Examples Tutorial](https://www.mongodb.com/basics/json-schema-examples)

