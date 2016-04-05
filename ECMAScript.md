# ECMAScript

## Data Type

### How many data types in JavaScript?

### How to determine the variable type in JavaScript(as many as possible)?

1. List methods.
2. Compare methods listed above.
  - Disadvantage
  - Advantage
3. ES5、ES2015/ES6

### Why us create so many complex methods?

### How to know two arrays are equal?

### Why `string` have methods?

## For Loop And Iteration

### Usage of `for of` and `for in`

1. Usages
2. Difference
3. `Array` loop methods.
  - methods.
  - Difference.
4. If I use `for in` to get `Object's property`
  - What's the result?
  - Why the result contain the properties of `Object.prototype`?
  - What's `[[Enumerable]]` property?
  - If I don't need the properties of `Object.prototype`, what should I do?

**Hint**

1. Object.hasOwnProperty(propertyName)
2. Object.keys()
3. Object.getOwnPropertyNames()


3. `Array.every`、`Array.filter()`、`Array.forEach()`、  `Array.map()`、`Array.some()`

## Promise

### Promise.race、Promise.all

```JavaScript
'use strict';

var run = delay => {
    return new Promise(function (resolve) {
        setTimeout(function () {
            resolve(delay);
        }, delay);
    });
}
```
What't the difference between these code below

```JavaScript
Promise.race([run(1), run(10), run(1500)]).then(function (delay) {
    console.log(delay);
});
```

```JavaScript
Promise.all([run(1), run(10), run(1500)]).then(function (delay) {
    console.log(delay);
});
```

## Fetch
