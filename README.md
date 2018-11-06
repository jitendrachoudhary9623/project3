

## Framework used

Express.js

## Getting started


npm install


## Testing

npm test


Or run the server:

node index.js

Use a software like postman or a simple CURL on the terminal to send the requests to the base url http://localhost:8000 with one of the below supported endpoints:

- GET
/block/{BLOCK_HEIGHT}

example:

```
 curl http://localhost:8000/block/0
```

- POST
/block

example:

```
curl -X "POST" "http://localhost:8000/block" -H 'Content-Type: application/json' -d $'{"body":"block body contents"}'
```
