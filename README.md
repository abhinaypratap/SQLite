# SQLite
#### ongoing...


### Terminal Commands

```sh
$ sqlite3 Database.db;
```

```sh
sqlite> CREATE TABLE Person (ID int, Name String);
```

```sh
sqlite> INSERT INTO Person (ID, Name) VALUES (1, "Dr. Rajendra Prasad");
```
or, 
```sh
sqlite> INSERT INTO Person VALUES (1, "Dr. Rajendra Prasad");
```
```sh
sqlite> .schema
```
-   For schema of a particular table 'tableName' in the database:
```sh
sqlite> .schema tableName
```
- To display the contents of a table:
```sh
sqlite> SELECT * FROM Person;
```
- To get out of sqlite3:
```sh
sqlite> .quit
```
```sh
sqlite> .q
```
```sh
sqlite> .width 2 10 10 10 30 6
```
```sh
sqlite> .show
```
```sh
sqlite> .mode column
```
```sh
sqlite> .tables
```
```sh
sqlite> .headers on
```

```sh
sqlite> DROP TABLE tableName;
```

```sh
sqlite> .backup tableOne_backup.db
```

```sh
sqlite> .restore tableOne_backup.db
```

* Update something in a record:

```sh
sqlite> UPDATE tableName SET columnName = "quotes only for text or string" WHERE rowid = 3;
```

* Add a column to a table:
```sh
sqlite> ALTER TABLE tableName ADD COLUMN columnName columnDataType;
```

## Modifications on existing table:
- `ALTER TABLE`
	1. Rename a table
	2. Add a new column to a table
	3, Rename a column

### Just small things

- Open-source database
- Lightweight (~250kb to implement)
- Embedded or Self-Contained, (no external dependencies(libraries) are needed)
- Relational Database Management System (RDBMS)
- Serverless
- Zero configuration
- SQL commands are case-insensitive
- \* means 'all'
- Written in C language
- It is ACID compliant RDBMS: 
	- A:Atomicity
	- C:Consistency
	- I:Isolation
	- D:Durability


## Storage Classes (Data types) in SQLite:

- INTEGER
- REAL
- TEXT
- NULL
- BLOB (Binary Large OBject)

- Boolean values in SQLite are stored as integers 0 (false) and 1 (true).  SQLite does not have a separate Boolean storage class.

##

- SELECT
- CREATE
- INSERT
- UPDATE
- DROP
- DELETE

