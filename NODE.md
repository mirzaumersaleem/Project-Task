# Node.js Questions

## What's wrong with the following code snippets?

```javascript
new Promise((resolve, reject) => {
  throw new Error('error')
}).then(console.log)
```

```javascript
function checkApiKey (apiKeyFromDb, apiKeyReceived) {
  if (apiKeyFromDb === apiKeyReceived) {
    return true
  }
  return false
}
```


## What would be the output be?

```javascript
Promise.resolve(1)
  .then((x) => x + 1)
  .then((x) => { throw new Error('My Error') })
  .catch(() => 1)
  .then((x) => x + 1)
  .then((x) => console.log(x))
  .catch(console.error)
```

## How do you set a cookie in node? Clear cookie?

## How do you prevent XSS Attacks in Node.js?

## What are the 3 arguments in an express middleware/route callback?

## What is the difference between Asynchronous and Non-Blocking?

## List 5 common modules in Node.js?

## What is a `Stream` in Node.js?

## What's the difference between the following HTTP requests: GET, POST, PUT, PATCH, DELETE?