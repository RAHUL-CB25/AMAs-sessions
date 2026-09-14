# AMA Questions

## Q1. What is the difference between `==` and `===` in JavaScript?

Answer: `==` compares values after type conversion, while `===` compares both value and data type without type conversion.

## Q2. What is the difference between `throw` and `return`?

Answer: `throw` is used to create or send an error, while `return` is used to send a value back from a function.

## Q3. What happens if a function is declared without a `return` statement?

Answer: If a function has no `return` statement, it automatically returns `undefined`.

## Q4. What is the `let` keyword?

Answer: `let` is used to declare a variable that can be reassigned and is block-scoped.

## Q5. What is the difference between a closure and lexical scope?

Answer: Lexical scope decides where variables can be accessed based on where the code is written, while a closure remembers variables from its outer scope.

## Q6. Explain execution context.

Answer: Execution context is the environment created by JavaScript to execute code, containing variables, functions, and the current `this` value.

## Q7. What is an anonymous function?

Answer: An anonymous function is a function without a name, commonly used as a callback or assigned to a variable.

## Q8. What are truthy and falsy values?

Answer: Truthy values act like `true` in conditions, while falsy values act like `false`, such as `false`, `0`, `""`, `null`, and `undefined`.

## Q9. What is the ternary operator?

Answer: The ternary operator is a short way to write an `if-else` condition using `condition ? value1 : value2`.

## Q10. What is the difference between `map()` and `forEach()`?

Answer: `map()` creates and returns a new array after modifying each element, while `forEach()` only loops through the array and returns `undefined`.

## Q11. What is `slice()` in JavaScript?

Answer: `slice()` is used to get a portion of an array or string without changing the original value.

## Q12. What is the difference between `Object.seal()` and `Object.freeze()`?

Answer: `Object.seal()` prevents adding or removing properties but allows modifying existing values, while `Object.freeze()` prevents all changes.

## Q13. What are mutable objects?

Answer: Mutable objects are objects whose properties or values can be changed after creation. Common mutable methods include `push()`, `pop()`, `shift()`, `unshift()`, `splice()`, and `sort()`.
