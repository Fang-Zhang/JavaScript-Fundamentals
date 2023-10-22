# Functional JavaScript

## 1. Functional Programming in Simple Terms
- What's Functional Programming?
  - A function must always take an argument
  - A function must always return a value
  - A function should act only on its receiving arguments not on the outside world
  - For a given input, a function must always return the same output
- Referential Transparency
  - There is no global reference inside function
  - This leads to parallel code and caching
- Imperative vs Declarative
  - Imperative programming is all about tellingthe compiler "how" to do something
  - Declarative programming is all about telling the compiler "what" to do
- Functional Programming Benefits
- Pure Functions (Return the same output for a given input)
  - Pure Functions Leads to Testable Code

```js
// Not Testable Code
var percentValue = 5;
var calculateTax = function(value) {
  return value * percentValue / 100;
}
```

```js
// Testable Code
var calculateTax = function(percentValue, value) {
  return value * percentValue / 100;
}
```

  - Reasonable Code
- Parallel Code
  - Pure function allows us to run code in parallel
- Cachable (Memoization)
  - Pure functions are cacheable
- Pipelines and Composition
- Pure Function is a Mathematical Function
- What We Are Going to Build
- Is JavaScript a Functional Programming Language?
## 2. Fundamentals of JavaScript Functions
- ECMAScript History
- Creating and Executing Functions
- Setting Up Our Project
## 3. Higher-Order Functions
- Understanding Data
- Abstraction and Higher-Order Functions
- Higher-Order Functions in the Real World
## 4. Closures and Higher-Order Functions
- Understanding Closures
- Higher-Order Functions in the Real World
## 5. Being Functional on Arrays
- Working Functionally on Arrays
- Chaining Operations
- Reducing Function
- Zipping Arrays
## 6. Currying and Partial Application
- A Few Terminologies
- Currying
- Currying in Action
- Data Flow
## 7. Composition and Pipelines
- Composition in General Terms
- Functional Composition
- Playing with Compose Function
- Pipelines/Sequence
## 8. Fun with Functors
- What's a Functor?
- MayBe
- Either Functor
- Word of Caution - Pointed Functor
## 9. Monads in Depth
- Getting Reddit Commments for Our Search Query
- The Problem
- Solving the Problem via join
## 10. Pause, Resume with Generators
- Async Code and Its Problems
- Generators 101
- Using Generators to Handle Async Calls