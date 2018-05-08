# PostgreSQL 10 Administration Cookbook
This is the code repository for [PostgreSQL 10 Administration Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/postgresql-10-administration-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781788474924), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
PostgreSQL is a powerful, open source database management system with an enviable reputation for high performance and stability. With many new features in its arsenal, PostgreSQL 10 allows users to scale up their PostgreSQL infrastructure. This book takes a step-by-step, recipe-based approach to effective PostgreSQL administration.

Through this book, you will be introduced to these new features such as logical replication, Native Table Partitioning, Additional Query Parallelism, and much more. You will learn how to tackle a variety of problems a which are basically the pain points for any database administrator - from creating tables to managing views, from improving performance to securing your database. More importantly, the book pays special attention to topics such as Monitoring roles, backup, and recovery of your PostgreSQL 10 database, ensuring high availability, concurrency, and replication.

By the end of this book, you will know everything you need to know to be the go-to PostgreSQL expert in your organization. 
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
SELECT table_name
,pg_relation_size(table_schema || '.' || table_name) as size
FROM information_schema.tables
WHERE table_schema NOT IN ('information_schema', 'pg_catalog')
ORDER BY size DESC
LIMIT 10;
```

In order for this book to be useful, you need at least access to a PostgreSQL client that is
allowed to execute queries on a server. Ideally, you'll also be the server administrator. Full
client and server packages for PostgreSQL are available for most popular operating systems
at http://www.postgresql.org/download/. All the examples here are executed at a
Command Prompt, usually running the psql program. This makes them applicable to most
platforms. It's straightforward to do many of these operations instead using a GUI tool for
PostgreSQL, such as pgAdmin or OmniDB.

## Related Products
* [PostgreSQL 10 High Performance](https://www.packtpub.com/big-data-and-business-intelligence/postgresql-10-high-performance?utm_source=github&utm_medium=repository&utm_campaign=9781788474481)

* [Mastering PostgreSQL 10](https://www.packtpub.com/big-data-and-business-intelligence/mastering-postgresql-10?utm_source=github&utm_medium=repository&utm_campaign=9781788472296)

* [Learning PostgreSQL 10 - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/learning-postgresql-10-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788392013)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
