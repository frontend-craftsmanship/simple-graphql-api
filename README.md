# simple-graphql-api
This repos is the simplest example of graphql server using express and express-graphql

We mock the data using json-server that will watch data.json file
The main idea of the graphql is the schema. Here I provide a schema for customers and operators.
Schema is builded on the GraphqlTypes (read: https://graphql.org/learn/schema/)
and must have resolver for each fields.

So let say that the DB server already live by run ```yarn json:server```
Then try to run the garphql playground by run ```yarn dev:server```



