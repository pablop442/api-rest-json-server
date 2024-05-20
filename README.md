# JSON Server

Get a full fake REST API with zero coding in less than 30 seconds (seriously)

## How to use

```[bash]
docker-compose up
```

You can see the server running in `localhost:3000`

More information: <https://github.com/typicode/json-server>

## How to execute API Rest - JSON server collection

Install Newman to run the collection from your CI

```[bash]
npm install -g newman
```

Run the collection and execute automated tests

```[bash]
newman run json_server.postman_collection.json -e json_server.postman_environment.json 
```