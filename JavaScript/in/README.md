# In

## What does the in operator in JavaScript do?

## What does it return when used with a value in an array? Explain and complete the example below.

```javascript
const array = ['a', 'b', 'c']
console.log('a' in array); // what would this print out?
```

## What does it return when used with an index in an array? Explain and complete the example below.

```javascript
const array = ['a', 'b', 'c']
console.log(1 in array); // what would this print out?
```

## What does it return when used with a property in an object? Explain and complete the example below.

```javascript
const dog = {
  name: 'Lynus',
  age: 5,
  favoriteToy: 'stuffed skunk'
}

console.log(age in dog); // what would this print out?
```

## What does it return when used with a property in an object's prototype chain? Explain and complete the example below.

```javascript
const dog = {
  name: 'Lynus',
  age: 5,
  favoriteToy: 'stuffed skunk'
}

console.log('toString' in dog); // what would this print out?
```


## What does it return when used with a deleted property in an object's prototype chain? Explain and complete the example below.

```javascript
const dog = {
  name: 'Lynus',
  age: 5,
  favoriteToy: 'stuffed skunk'
}

delete dog.age

console.log(age in dog); // what would this print out?
```

## What does it return when used with a property set to undefined in an object's prototype chain? Explain and complete the example below.

```javascript
const dog = {
  name: 'Lynus',
  age: 5,
  favoriteToy: 'stuffed skunk'
}

dog.favoriteToy = undefined

console.log(favoriteToy in dog); // what would this print out?
```

