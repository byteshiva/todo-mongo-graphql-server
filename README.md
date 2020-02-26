# todo-mongo-graphql-server
Using GraphQL with MongoDB


Download Mongodb debian and install on ubuntu
https://www.mongodb.com/download-center/community

refe:

```mongodb
// Create database
use todo
db.movie.insert({"name":"sample"})
// Create User example/somepassword
db.createUser({user: "example", pwd: passwordPrompt(), roles: [ "readWrite", "dbAdmin" ]});
```

[https://docs.mongodb.com/manual/reference/method/db.createUser/](https://docs.mongodb.com/manual/reference/method/db.createUser/)
