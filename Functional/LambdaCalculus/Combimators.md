# Combinators in Lambda
- Combinators are functions with no free variables.
- Free variable - variable in the body not bound to any parameter.
```
Examples
  \b.b combinator
  \b.a not a combinator
```



## Various Combinators
```
 1. Identity 
 - Lambda expression => \a.a
  - in programming, represented as I = a => a
  - Takes `a` outputs `a`

  Example I(I) = I 
 ```

```
2. MockingBird => 
  - Lambda expression => \f.ff
  - in programming, represented as M = f => f(f)
  - Applying function to itself. 

  Example.  M(I) = I How?
    M(I) = I(I) = I 
    where I = identity function

    what is M(M)
    M(M) == M(M) == M(M) == M(M) == M(M).........goes on for ever
    This is called (HALTING PROBLEM solved by Alan turing)
```

```
3. KESTREL => 
  - Lambda expression => \ab.a
  - in programming, represented as K = a => b => a
  - Second argument is irrelevant. Always returns first argument.

  Examples: 
    K(I)(M) = I
    K(K)(M) = K
    K(M)(I) = M
```

```
3. KITE => 
  - Lambda expression => \ab.b
  - in programming, represented as KI = a => b => b
  - First argument is irrelevant. Always returns second argument.

  KITE combinator is derived by combining KESTREL and IDENTITY

  Examples: 
    KI(M)(K) = K
    KI(K)(M) = M    
```



```
3. CARDINAL => 
  - Lambda expression => \fab.fba
  - in programming, represented as C = f => a => b => f(b)(a)
  - It takes a function `f` with two arguments (a, b) and calls that function with (b, a) arguments. Just flips the arguments.

  KITE combinator is derived by combining KESTREL and IDENTITY

  Examples: 
    CKIM == K(M)(I) == M == KI(I)(M)

```

## Why Combinators?
- 


References
- https://www.youtube.com/watch?v=3VQ382QG-y4&t=1088s
- https://www.cin.ufpe.br/~djo/files/Lambda-Calculus%20and%20Combinators.pdf