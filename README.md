ud858
=====

Course code for Building Scalable Apps with Google App Engine in Python class

## Lesson - 3
### Google Datastore
* A paper on BigTable : [http://research.google.com/archive/bigtable.html]

On a high level, Google Datastore functions the following way - Kinds, Entities, Properties


| Profile                    |
| -------------              |
| displayName: John Doe      |
| teeShirtSize: Large        |
|                            |


| Conference              |
| -------------           |
| name: Thai Cooking      |
| startDate: Aug 15th     |
| endDate: Aug 16th       |
| city: Bankok            |
| ----------------------- |
| name: Top Fishing       |
| startDate: Feb 15th     |
| endDate: Feb 19th       |
| city: Juneau            |


1. Kinds - The Profile, Conference Columns
2. Entities - (group of properties in each Kind)
3. Properties - name, startDate etc. in each Entity


## Lesson - 4
### Advanced Google Datastore Concepts

#### Data Relationships
For Modeling in datastore there are two main types of relationships - Ancestor and Has-A

#### Types of Queries
1. Query by Kind
2. Query by Kind filter by Ancestor
3. Query by Kind filter by Property

