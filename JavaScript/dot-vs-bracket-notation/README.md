# Dot vs Bracket Notation

## Dot Notation

### What is dot notation?

``` javascript
var obj = {prop: 'something'};
console.log(obj.prop); // what would this return?
```

## Bracket Notation

### What is bracket notation?

``` javascript
var obj = {prop: 'something'};
console.log(obj['prop']); // what would this return?

var obj2 = {
  a: 'foo',
  b: 'bar',
  foo: 'a',
  bar: 'b'
}

console.log(obj2.a) // what would this return?
console.log(obj2['foo']) // what would this return?
console.log(obj2['b']) // what would this return?
console.log(obj2['bar']) // what would this return?

var obj3 = {
  b: 1,
  a: 2,
  r: 3,
  bar: 'foo'
}

console.log(obj3['b' + 'a' + 'r']) // what would this return?
console.log(obj3.b + obj3.a + obj3.r) // what would this return?

obj3[obj.prop + obj2.a + obj3.r] = "a final value"
console.log(obj3.??) // what property should we log to print 'a final value'
```

### When would you want to use dot vs bracket notation?

### What is a computed property?

### Would you use dot or bracket notation to access a computed property?
