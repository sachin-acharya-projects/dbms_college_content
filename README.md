# MySQL Practice
_________________________________
[MySQL Manual](http://g2pc1.bu.edu/~qzpeng/manual/MySQL%20Commands.htm)
#### Logging in to MySQl CLI
````
mysql -u username --password PASSWORD
````
#### Displaying all the databases available (R)
````
SHOW DATABASE
````

#### CREATING NEW DATABASE (C)
````
CREATE DATABASE DB_NAME;
````

#### Changing to Different databases
````
USE DB_NAME;
````

#### DELETING DATABASE (D)
````
DROP DATABASE DB_NAME
````

#### DISPLAYING ALL THE TABLES INSIDE CURRENTLY SELECTED database
````
SHOW TABLES:
````

#### CREATING TABLE 
````
CREATE TABLE table_name(
    column_name_1 datatypes(size) ...,
    column_name_2 datatypes(size) ...,
    column_name_3 datatypes(size) ...,
    column_name_4 datatypes(size) ...,
    ....
    column_name_n datatypes(size) ...
)
````

#### TO SEE DATABASES FIELD FORMATS
````
DESCRIBE table_name
````