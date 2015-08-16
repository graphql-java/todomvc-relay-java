# Relay TodoMVC with a Java Server

This is a port of the [Relay TodoMVC example](https://github.com/facebook/relay/tree/master/examples/todo)
where the GraphQL JavaScript server is replaced with a Java server based on [graphql-java](https://github.com/andimarek/graphql-java).


### Running

Starting the frontend:

```bash
cd app
npm install
npm start
```

Starting the backend: (running on port 8080)

```bash
./gradlew start
```

The app is now available at http://localhost:3000



  