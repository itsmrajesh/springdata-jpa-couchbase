# Spring Boot Couch DB

## Create an Index for Query Operations

We must create an index if we intent to support query operations such as:
* count
* findAll
* deleteAll

To create an index, execute the following command from the query editor:

```sql
CREATE PRIMARY INDEX `example-primary-index` ON `example` USING GSI
```

For more info about Couchbase indexes, please [consult the documentation](https://docs.couchbase.com/server/current/n1ql/n1ql-language-reference/createprimaryindex.html).