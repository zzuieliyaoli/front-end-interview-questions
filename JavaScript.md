# JavaScript

## Data Type

### How many data types in JavaScript?

### How to determine the variable type in JavaScript(as many as possible)?

1. List methods.
2. Compare methods listed above.
  - Disadvantage
  - Advantage
3. ES5、ES2015/ES6

### Why us create so many complex methods?

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

3. `Array.every`、`Array.filter()`、`Array.forEach()`、  `Array.map()`、`Array.some()`


## Simple Harmonic Motion

### How to use JavaScript to make the element do simple harmonic motion?

```html
<div id="block"></div>
```

```css
#block {
    display: inline-block;
    width: 30px;
    height: 30px;
    position: absolute;
    background-color: red;
}
```

**Hint**

1. Selector
  1. `document.getElementById()`and`document.querySelector()`
  2. Difference between selectors above
2. Window Timer
  1. `window.setTimeout()`and`window.setInterval()`
    1. Difference between window timers above
    2. How does `window.setTimeout()`replace`window.setInterval`
    4. Why window timers not go well?
  2. Better way? `animationRequestFrame`
    1. What's `animationRequestFrame`
    2. Graceful degradation when browsers don't support `animationRequestFrame`?

### When hit `Keyboard Spacebar`, pause the simple harmonic motion?

**Hint**

1. `window.clearTimeout`and`window.clearInterval`
  1. Useage
  2. Use `window.setTimeout()` to do other brilliant work?
2. Event Handler
  1. DOM on-event handlers
  2. DOM event listener handlers
  3. Difference
  4. Event target
  5. Key Code
  6. Prevent browser default action when event fires
  7. Fire event many times in a short time

### When hit `Keyboard Enter`, change the simple harmonic motion direction?


