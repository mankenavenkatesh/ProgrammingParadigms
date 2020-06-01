In this paradigm we express computations as the evaluation of mathematical functions.


## Functional Programming by Wikipidia:
“Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids state and mutable data”. In other words, functional programming promotes code with no side effects, no change of value in variables. It oposes to imperative programming, which enfatizes change of state”.


Functional Programming in the process of building software by using pure functions, avoiding shared state, mutable data and side-effects.


## Definition of Functional Programming
- Programming with functions as building blocks
- Programming with pure functions as building blocks
- Functional programming is programming without assignment statements


Functional programming is originated from lambda calculus. 

## What is lambda calculus?
https://www.youtube.com/watch?v=d0yEXKas8xE
https://www.youtube.com/watch?v=9T8A89jgeTI
https://www.youtube.com/watch?v=v1IlyzxP6Sg&list=PLDAqk5znTEXeQwDstVk5uzsNmj3RTMlVg 

- you can express any mathematical probelm in lamda calculus. 

```
Three rules of lambda calculus
1. variable (x,y,z,)
2. abstraction  (lambda * term . )
3. Application (term1 . term2)

Dot is applying term1 onto term2. 

variable - can be anything with a name

nested Abstraction - with abstraction 
f(x) = x is defined as (lambda*args).(returnval)
f(x, y) = x is defined as (lambda*X).(lambda*Y).(returnval)

Why??
because of currying. 
Currying - if there is function which takes x, y and returns x+y
with currying you can have function which takes x and return another function which takes y as parameter and returns x + y.

currying will delay the executing of function.
```


## Convert programs to lambda and vice versa
https://www.youtube.com/watch?v=3VQ382QG-y4&t=1088s


## Jargons of Functional Programming
- Higher order functions
- Pure functions
- Type strictness
- Recursion
- Immutability
- Category Theory
- Lambda calculus
- Currying


Core idea of Functional programming  - NO SIDE EFFECTS




Expression vs Statement
- Expression have no side effect
- checks conditions and returns value
- Statement have side effects
- contains assignments


#PSEUDO CODE:
#Statement
Int weight = 50 //kg
String comment = ""
if (x > 70) {
    comment = "Slim down, bro"
}else {
    comment = "you look fit"
}

#Expression
Int weight = 50 //kg
String comment = x>70? "Slim down, bro" : "You look fit!"



References 
- https://www.youtube.com/watch?v=iSs3LdUZziU
- https://www.youtube.com/watch?v=FYXpOjwYzcs
- https://hackr.io/blog/functional-programming
- https://www.amazon.in/Introduction-Functional-Programming-Calculus-Mathematics/dp/0486478831