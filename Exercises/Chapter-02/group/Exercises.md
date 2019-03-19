# Exercises for Chapter 2

## Exercise 1 - Sparks

Write a program, that creates a spark that ...

* that /duds/ 
* /fizzles/
* gets garbage-collected

*Tipp*: Do not use `-O2` which aggressively inlines and eliminates expressions
leading to surprising results.


## Exercises 2 - rpar

Consider this definition of `rparWith`: 

```
rparWith s = rpar . s 
```

Is it equivalent to the Definition in `Data.Parallel`? (Why not?)

