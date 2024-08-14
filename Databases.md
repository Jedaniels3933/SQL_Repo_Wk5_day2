# **Databases**  -  Use Lucid Chart
## Deff: a structed collection of data
### **SQL** - structed querry language
Relational v/s non -relationable
1. Pre-defined with collums
2. Fixed SchemaVertical scalibilty
3. Vertical Scale
4. Full Acid compliance
5. Structed data
- Structure
- Components
   **Columns** and **Rows**
-Normalization - Goal **Elimanate Redundancy**
### **Rules**
1. Each row is unique
2. Organizes data into tables to reduce duplication and dependancy

### *Keys*:
1. *Primary*  UNique ID for each entry in table 
- Used to reference individual records
##### *Example* = In a "Users table" "user_id" can be a primary key 

2. - *Foreign* -Primary keys from other table used as reference entitys

## **Relationships** : 3
*1*. One to One = An entity in one table connects to another table
Country to Capital - each country has one capital  
*2*. One to many = An entity in one table can connect to mult entries in another table
*3*. Many to Many = Entitys in one table can connect to mult entities in another table   

### **<NON -SQL></NON>** 
1.Non relationable 
2. Dynamic Schema - flexible data model
3. Query language - varies
4. Horizontal scalibility
5. Unsctructed data 

#  **Entity Realationship Diagram
- ERD Tool : Luicid chart 
## Lucid Chart - Data types
1.CHAR(size)   example CHAR(50) sets max characters can use in this case 50 
2.VARCHAR(size)
  
#### Date/Time stuff




###  Cardinality and Ordinality
1. Cardinality - refers to the max number of times an instance in one entity can relate to instances of another entity.
    _____________________|__    One
    _____________________= crows foot = many 
    __________________||_____  


    Design Tips: 
    1. Ensure each table has a primary key.
    2. Use foreign keys to maintain data integrity
    3. Normalize data 

   Creating ERD's 
   1. Identify entities
   2. Determine relationships (1-1, 1-many, many-to-many)
   3.  




FIle then export- .pdf then crop then download 
then go to VS code - make a repo 
