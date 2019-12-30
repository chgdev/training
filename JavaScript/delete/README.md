# Delete Operator

## What does the delete operator do?

## Does the delete operator free up memory?

## What are non-configurable properties?

## How can you create a property on an object that is non-configurable?

## What happens if you try to delete a property is that is non-configurable?

```javascript
let  dog = { age: 3}

Object.defineProperty(dog, 'name', {configurable: false})

console.log(delete dog.name) // what will this print out?
console.log(dog.name) // what will this print out?

console.log(delete dog.age) // what will this print out?
console.log(dog.age) // what will this print out?
```

## Can you delete properties on default JavaScript objects? 

```javascript
console.log(delete Math.PI) // What happens?
```

## What happens if you try to delete a property that is non-configurable in strict mode?

```javascript
"use strict"

var foo = 10
let bar = 20
const fooBar = 30

console.log(delete foo)
console.log(delete bar)
console.log(delete fooBar)
```

## What does the delete operator return when used on a property that exists?

## What does the delete operator return when used on a property that doesn't exist?
```javascript
var rabbit = {
    longEars: true,
    weight: 5
};

console.log(delete rabbit.longEars); // what does this log?
console.log(delete rabbit.weight); // what does this log?
console.log(delete rabbit.isFurry); // what does this log?
```

## Does delete have any affect on properties on an object's prototype chain?
```javascript
function Rabbit() {
    this.weight = 10
}

Rabbit.prototype.weight = 5
var bunny = new Rabbit()

console.log(bunny.weight); // what is logged here?
console.log(delete bunny.weight); // what is logged here?
console.log(bunny.weight); // what is logged here? why?

console.log(delete Rabbit.prototype.weight); // what is logged here?
console.log(bunny.weight); // what is logged here now? why?
```

## Can properties declared using var be deleted?

## When can properties declared with let or const be deleted?

## What happens when you remove an item from an array using the delete operator? Is the length of the array affected?

```javascript
var array = ['a', 'b', 'c', 'd'];

console.log(array.length); // what is logged here?
console.log(delete array[2]); // what is logged here?
console.log(array.length); // what is logged here?
console.log(array[2]); // what is logged here?
console.log(2 in array); // what is logged here?
```

## What are some better ways to remove an item from an array? 