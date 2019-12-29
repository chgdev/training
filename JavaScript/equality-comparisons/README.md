# Equality Comparisons

## ===
### When comparing two values, what does === mean in JavaScript? What does it do?

### What would the following === comparisons return and why?

```javascript
console.log(1 === 1) // ??
console.log('1' === 1) // ??
console.log(1 === '1') // ??
console.log(0 === false) // ??
console.log(0 === null) // ??
console.log(0 === undefined) // ??
console.log(null === undefined) // ??

const obj1 = {
  'key': 'value'
}

const obj2 = {
  'key': 'value'
}

console.log(obj1 === obj2) // ??
```

## ==
### When comparing two values, what does == mean in JavaScript? What does it do?

### What would the following == comparisons return and why?

```javascript
console.log(1 == 1) // ??
console.log('1' == 1) // ??
console.log(1 == '1') // ??
console.log(0 == false) // ??
console.log(0 == null) // ??
console.log(0 == undefined) // ??
console.log(null == undefined) // ??

const obj1 = {
  'key': 'value'
}

const obj2 = {
  'key': 'value'
}

console.log(obj1 == obj2) // ??
```
## Object.is()
### What is the Object.is() function?

### What does the Object.is() function take in as parameters?

### What does the Object.is() function return?

### What would the following return and why?

```javascript
console.log(Object.is(NaN, NaN)) // ??
console.log(Object.is(1, 1)) // ??
console.log(Object.is(1, 4)) // ??
console.log(Object.is(undefined, undefined)) // ??
console.log(Object.is(+0, -0)) // ??
console.log(Object.is(+0, +0)) // ??
console.log(Object.is(-0, -0)) // ??
console.log(Object.is(null, null)) // ??
console.log(Object.is(true, false)) // ??
console.log(Object.is(false, false)) // ??
console.log(Object.is("cat", "dog")) // ??
console.log(Object.is("dog", "dog")) // ??
console.log(Object.is({ "key" : "value" }, { "key": "value" })) // ??

const obj = {
  "key": "value"
}

console.log(Object.is(obj, obj)) // ??
```

## What is the difference between using ===, ==, and Object.is()?

## Can you use Object.is() in ES5?

## Can you use Object.is() in all versions of Node.js?
