# fibonacci-js

## Requirements

Docker

## Running it locally

```
$ docker-compose up --build
```

## Structure

* client - frontend code written in React
* nginx - routes / calls to the client code and /api calls to server
* server - api that handles the Fibonacci calls from client, written in Node.js
* worker - subscribes to Redis messages to calculate the Fibonacci values asynchronously