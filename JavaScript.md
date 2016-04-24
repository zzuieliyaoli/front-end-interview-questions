# JavaScript

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
  3. [querySelectorAll 方法相比 getElementsBy 系列方法有什么区别？](https://www.zhihu.com/question/24702250)
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

## Custom Events

1. `new CustomEvent()`
2. `Redux`...
