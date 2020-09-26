# SQLite

### Terminal Commands
#### ongoing...

```sh
$ sqlite3 Database.db;
```

```sh
sqlite> CREATE TABLE Person (ID int, Name String);
```

```sh
sqlite> INSERT INTO Person (ID, Name) VALUES (1, "Dr. Rajendra Prasad");
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






















### Just small things

- SQL commands are case-insensitive.
- * means 'all'.
