# Arrow Functions

## What is an arrow function?

## Is there a difference, besides syntax, between an ES5 function and an arrow function?

## If an arrow function does not contain a body and just returns a value, how can you write it in one line without using the return keyword?

```javascript
var subtract = function(a, b) {
  return a - b
}

const oneLineSubtract = // ??
```

## If an arrow function only takes in a single parameter, do you have to use parenthesis around that parameter?

## Convert the following into arrow functions. Try to make all functions as concise as possible, keeping in mind parameters, braces, and return statements:

```javascript

var add = function(a, b) {
  return a + b
}

const addArrowFn = // ??

var doPromise = function(a) {
  return new Promise(function(resolve) {
    setTimeout(function () {
      resolve(a)
    }, 3000)
  })
}

const doPromiseArrowFn = // ??

const users = [
  {
    id: 1234,
    name: 'Jane'
  },

  {
    id: 4321,
    name: 'John'
  },

  {
    id: 5678,
    name: 'Jill'
  },

  {
    id: 8765,
    name: 'Joe'
  },
]

var getIds = function(users) {
  return users.map(function(user) {
    return user.id
  })
}

const getIdsArrowFn = // ??

```

## How can you use an arrow function to return an object without using a return statement? Convert the following to an arrow function that returns an object without using the return key word?

```javascript
var add = function(a, b) {
  return {
    sum: a + b,
    a: a,
    b: b
  }
}

const addArrowFn = // ???
```

## Resources
https://tylermcginnis.com/arrow-functions/