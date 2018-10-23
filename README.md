## Bookmark Manager

#### User Stories
```
As a user
So that I can quickly go to web site I visit regularly
I would like to see a list of bookmarks
```

### Setting up the database
- Instal PostgreSQL
- To start `psql` type the command `psql postgres` into your terminal
- Create the database using the `psql` command `CREATE DATABASE bookmark_manager;`
- Connect to the database using the `pqsl` command `\c bookmark_manager;`
- Run the query in the file: `01_create_bookmarks_table.sql`

### Setting up the test database
- Create the database using the `psql` command `CREATE DATABASE bookmark_manager_test;`
- Connect to the database using the `pqsl` command `\c bookmark_manager_test;`
- Run the query in the file: `01_create_bookmarks_table.sql`
