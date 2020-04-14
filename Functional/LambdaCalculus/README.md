# Lambda Expression

# Functions as Lambda Expression
```
Function = \(head).(body)

`\ = lambda`
`head = function parameters`
`body = what is returned by the function`

```

Examples

```
    Function = \a.a
    
    This function take argument 'a' and returns 'a'    
    a can be number, character etc
```

```
    Function = \a.z

    This function takes argument 'a' and returns 'z'
    a, z can be anything
```


# Applying Lambda Expression to an argument
Examples
```
    (\a.a)3 means apply lambda expression \a.a to argument 3
    So (\a.a)3 becomes \3.3  returning 3

```

```
    (\a.az)b means applying lambda expression `a.az to argument b
    so (\a.az)b becomes \b.bz returning bz
```

# Applying Lambda Expression to another lambda expression
Examples

```
    (\a.ab) (\x.xx) becomes bb

    How?

    (\a.ab) (\x.xx)  takes argument (\x.xx) and returns (\x.xx)b

    (\x.xx)b takes argument b and returns bb    
```


References
- https://www.youtube.com/watch?v=9Q-Bi-Cg9tI