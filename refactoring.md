# Refactoring
the middle ground between speed of writing and comprehension of reading is where good code lives.
### Strategies:
- return early from functions
- cache variables so functions can be read easily
- check for APIs before implementing your own functionality

# Functional Programming
functional programming is a style of structuring programs that treats computation as the evaluation of mathematical concepts and avoids changing-state and mutable data.
It prioritizes *pure functions* 
### Pure Functions
Return Deterministic results
do not cause observable side effects

Every function in functional programming is isolated and unable to impact other parts of our system

  pure functions + immutable data = referential simplicity
  
### Functions as first-class entities
functions are also treated as values and used as data. This way we can combine different functions to create new functions with new behaviour. 
This allows us to create *higher-order functions*
This is *Declarative* rather than *iterative*
