# DDL (Data Definition Language) Commands

## 1. CREATE Command

-> Create command is used to create a table or database.<br>

<b>Syntax: </b><br>
CREATE TABLE table_name (column1 data_type, column2 data_type, ...); 

## 2. DROP Command

-> Delete objects from the database.<br>

<b>Syntax: </b><br>
DROP TABLE table_name;

## 3. ALTER Command

-> Alter the structure of the database.<br>

<b>Syntax: </b><br>
ALTER TABLE table_name ADD COLUMN column_name data_type;

## 4. TRUNCATE Command

-> Remove all records from a table, including all spaces allocated for the records are removed.<br>

<b>Syntax: </b><br>
TRUNCATE TABLE table_name;

# 5. RENAME Command

-> Rename an object existing in the database.

<b>Syntax: </b><br>
RENAME TABLE old_table_name TO new_table_name;
