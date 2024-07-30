# DML Queries

## 1. INSERT Command

-> Used to insert the data into a table.<br>

<b>Syntax</b><br>
INSERT INTO table_name (column1, column2, ...) VALUES (value1, value2, ...);

## 2. UPDATE Command
-> Used to update the existing data within a table.<br>

<b>Syntax</b><br>
UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;

## 3. DELETE Command
-> Used to Delete records from a database table.<br>

<b>Syntax</b><br>
DELETE FROM table_name WHERE condition;

## 4. LOCK Command
-> Used to control the Table concurrency.<br>

<b>Syntax</b><br>
LOCK TABLE table_name IN lock_mode;