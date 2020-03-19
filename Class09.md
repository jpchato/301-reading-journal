# Concepts of Functional Programming in JavaScript
* What is functional programming?
  * Programming paradigm. Style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.
* Pure Functions
  * It returns the same reuslt if given the same arguments
  * Reading Files
    * If it reads external files it is not a pure function
  * Random Number Generation
    * Any function that relies on rng cannot be pure
  * It does not cause any observable side effects
  * Mutability is discouraged in functional programming
  * Benefits
    * Code is easier to test
* Immutability
  * State cannot change after it's created
* Referential transparency
  * If a function consistently yields the same result for the same input
* Functions as first-class entities
  * functions are treated as values and used as data
  * refer to it from constants and variables
  * pass it as a parameter to other functions
  * return it as result from other functions
* Higher-order functions
  * takes one or more functions as arguments
  * return a function as its result

# Refactoring JavaScript for Performance and Readability
* Good code is the middle ground between speed and comprehension
* Strategies
  * Return early from functions
  * Cache variables so functions can be read like sentences
  * Check for Web APIs before implementing your own functionality
 