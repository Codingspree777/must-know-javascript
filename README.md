# Must-Know JavaScript

# QUIZ NIGHT!!!

Tonight is a hands-on workshop night where we will focus on technical JS knowledge and interview skills!

Preferably with a partner (or alone if you prefer), write short answers to all of the questions (you can copy and paste this document into a Google Doc or fork this repository and use markdown -- advanced).

For each of the exercises, do the following:

1. Do an I-O-C-E analysis (Inputs, Outputs, Constraints, Edge Cases).
1. Write down three clarifying questions to ask for the interviewer.
1. Write some pseudocode or bullet-points about the problem.
1. (Optional) Write a possible code solution.

---

## Loops Quiz

- When would you use a _for...of_ loop over a regular _for_ loop?
- What are `while` loops good for?
- What are the first two parameters for the `Array.prototype.forEach` callback function?
- What happens to the return values for the `Array.prototype.forEach` callback function?
- A _for...in_ loop is primarily used to iterate over the `____` of an `____`.
- What is the value of `i` after the following loop:

```js
for (var i = 0; i < 4; i++) {
  console.log(i);
}
```

- What is the value of `j` after the following loop:

```js
for (var j = 5; j >= 0; j--) {
  console.log(j);
}
```

### Loops Exercises

**Analyze Array**

Write a function that takes an array and prints each element, its index, and its type on the same line, like this: `1 is at index 0 and its type is number`.

**So Random (Bonus)**

Write a function that takes an integer between 1 and 10, inclusive. The function should continue generating random integers until it produces the target integer. When the target integer is generated, exit the function and return how many tries it took to do that.

---

## Array Methods Quiz

- How can you check if something is an array?
- How can you easily make a copy of an array?
- What are the function signatures (parameters and return values) of:
  - includes
  - indexOf
  - push
  - pop
  - splice
  - slice
  - join
  - shift
  - unshift
  - concat
  - sort
- How does the `Array.prototype.map` function work?
- How does the `Array.prototype.filter` function work?
- How does the `Array.prototype.reduce` function work?

### Arrays Exercises

**Remove Extremes**

Write a function called `removeExtremes` that removes the smallest and largest elements of an array of numbers.

**Evens and Odds**

Write a function called `evensOdds` that takes an array and a string that is either exactly `evens` or `odds`, then return a new array that has only the evens or the odds in it (depending on the second argument).

---

## String Methods Quiz

- What are the parameters to `String.prototype.slice`?
- How do you replace _all_ occurrences of a character using `String.prototype.replace`?
- Why doesn't `str[0] = 'x'` work?
- When do you use `+=` for strings?
- What are the function signatures (parameters and return values) of:
  - slice
  - split
  - replace
  - indexOf
  - includes

### String Exercises

**Replacer**

Write a function that takes three strings. The first string is a word like `cactus`. The second string is a character to replace. The third string is a character to replace the second character with. Return the transformed string.

---

## Objects Quiz

- What does `Object.keys` give you?
- What does `Object.values` give you?
- What does `Object.entries` give you?
- What are the differences between dot access and bracket notation?
- An object's keys are always what data type?

### Objects Exercises

**Merge Objects**

Given an array of objects, return an object that consists all of the individual objects combined.

---

## Type Coercion and Conversion Quiz

- What are four ways to convert the following string to an integer:

```js
let x = '515';
```

- What does `Number.isNaN` do?
- What is the difference between `==` and `===`?
- What is a method to convert arrays and numbers to strings?
- What is a valuable way to convert an object to a string?
- What are two ways to convert anything to its boolean value?
- What are the 6 falsy values in JavaScript?

## Type Exercises

Write your own version of [Number.isNaN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isNaN).
