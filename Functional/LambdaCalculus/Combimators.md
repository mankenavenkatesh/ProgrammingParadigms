# Combinators in Lambda

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

References
- https://www.youtube.com/watch?v=3VQ382QG-y4&t=1088s
- https://www.cin.ufpe.br/~djo/files/Lambda-Calculus%20and%20Combinators.pdf