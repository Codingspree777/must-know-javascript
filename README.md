# Must-Know JavaScript

This is the companion repository for these slides: [https://slides.com/hueter/must-know-javascript/](https://slides.com/hueter/must-know-javascript/)

---

## Loops Quiz

- When would you use a _for...of_ loop over a regular _for_ loop?
- What are the first two parameters for the `Array.prototype.forEach` callback function?
- What happens to the return values for the `Array.prototype.forEach` callback function?
- A _for...in_ loop is primarily used to iterate over the `____` of an `____`.

---

## Array Methods Quiz

- Which array methods are pure functions?
- How can you easily make a copy of an array?
- What are the return values of:
  - push
  - pop
  - splice
  - shift
  - unshift
- How does the `Array.prototype.map` function work?
- How does the `Array.prototype.filter` function work?
- How does the `Array.prototype.reduce` function work?

Given the following code:

```js
var arr = [2, 17, 3, 15, 18, 19, 1, 0];
```

1.  Use method-chaining to remove the largest item from the array in one line.
1.  Use method-chaining to create a new array that contains only the squares of the numbers that are greater than 9 in one line.

---

## String Methods Quiz

- What are the parameters to `String.prototype.slice`?
- How do you replace _all_ occurrences of a character using `String.prototype.replace`?
- Why doesn't `str[0] = 'x'` work?
- When do you use `+=` for strings?

---

## Objects Quiz

- What does `Object.keys` give you?
- What does `Object.values` give you?
- What does `Object.entries` give you?

---

## Type Coercion and Conversion Quiz

- What are four ways to convert the following string to an integer:

```js
let x = '515';
```

- What does `Number.isNaN` do?
- What is special about `NaN` that is different from every other value in JavaScript?
- Write your own version of `Number.isNaN`:

```js
function myIsNaN(val) {
  // your code here
}
```

- What is the difference between `==` and `===`?
- What is a method to convert arrays and numbers to strings?
- What is a valuable way to convert an object to a string?
- What are two ways to convert anything to its boolean value?
- What are the 6 falsy values in JavaScript?
