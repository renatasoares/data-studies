### First Steps

#### Features

1. It has concurrent design, scalability and performance features and it is configurable and extensible.

 1.1. **Multiversion Concurrency Control (MVCC)**: Feature from postgresql that allow readers and write not block each other.

 1.2. You can add your own data types, operatores, index types and functional languages.

2. Client-server architecture

 2.1. Client–server model is a distributed application structure that partitions tasks or workloads between the providers of a resource or service, called servers, and service requesters, called clients. [Wikipedia](https://en.wikipedia.org/wiki/Client%E2%80%93server_model).


3. It offers support for many kinds of data models: relational, post-relational, document and key/value.

4. Robustness

  4.1. All actions on the database are performed within transactions, protected by a transaction log that will perform automatic crash recovery in case of software failure.

5. [Security](https://www.postgresql.org/support/security/).

6. SQL and NoSQL data models.

#### Tools

1. [pgAdmin](https://www.pgadmin.org/)
2. [OmniDB](https://omnidb.org/)
3. [psql](https://www.postgresql.org/docs/13/app-psql.html)

  3.1. There are two type of commands: psql meta-commands and SQL.

  3.2. `\?`: provides help on psql meta-commands.

  3.3. `\h`: provides help on SQL commands.

  ```
  banco=> \h DELETE
Command:     DELETE
Description: delete rows of a table
Syntax:
[ WITH [ RECURSIVE ] with_query [, ...] ]
DELETE FROM [ ONLY ] table_name [ * ] [ [ AS ] alias ]
    [ USING from_item [, ...] ]
    [ WHERE condition | WHERE CURRENT OF cursor_name ]
    [ RETURNING * | output_expression [ [ AS ] output_name ] [, ...] ]
URL: https://www.postgresql.org/docs/13/sql-delete.html
```
  3.4. Execution timing using `\timing` command.
