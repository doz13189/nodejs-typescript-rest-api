# nodejs-typescript-rest-api

## 環境

```
node -v
v14.18.1
```

## ディレクトリ

Services that make our code cleaner by encapsulating business logic operations into functions that middleware and controllers can call.
Middleware that will validate prerequisite conditions before Express.js calls the appropriate controller function.
Controllers that use services to process the request before finally sending a response to the requester.
Models that describe our data and aid in compile-time checks.

Route configuration to define the requests our API can handle
Services for tasks such as connecting to our database models, doing queries, or connecting to external services that are required by the specific request
Middleware for running specific request validations before the final controller of a route handles its specifics
Models for defining data models matching a given database schema, to facilitate data storage and retrieval
Controllers for separating the route configuration from the code that finally (after any middleware) processes a route request, calls the above service functions if necessary, and gives a response to the client

## 参考

https://www.toptal.com/express-js/nodejs-typescript-rest-api-pt-1

