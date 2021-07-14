# Javascript

[Array destructuring](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment#array_destructuring)

---

**Arrow functions** have an implicit return value: they can be written in one line, without the need for the braces.

**Immediately invoked functional expressions** need a semicolon at the beginning to separate it from any code above it

```js
;(function callMeNow() {
  // I'm being called right away!
})()
```

---

`requestAnimationFrame()` : for running animations efficiently by running a specific block of code before re-rendering the display in the browser

---

## Operators

[**Nullish Coalescing Operator (`??`)**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing_operator)
: if the first value is either `null` or `undefined`, it will return the second value, unlike the [**logical OR (`||`) operator**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_OR) that will return the second value if the first is any falsy value including `''` or `0`
- `const value = null ?? 'default value'`
