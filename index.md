Sql vs Nosql

We have tables with specific structure , and we can't enter data in another structure. All records in tables must have the same structure .
Ex. postgresql, mysql
But in Nosql databases we don`t have a certain structure. And each record can have its own structure.
We have for type in Nosql databases:


Key_value: redis,...
You have a key and can store anything as  value. And structure is not important.
And your key must be unique but value can be anything.
Graph: neo4j,...

Document: mongodb  
Store data in json form




Wide_column: cassandra
In this kind of database we have a table for storing data , like the pic below .
But each record can have its own fields.  For example for Bob we store email, gender and age but for Britny we have email and gender and for Tori we store email and country and haircolor.







