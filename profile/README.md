# MKS

MKS is an interpreted programming language written in C.

It is designed around a minimal but expressive syntax and a custom runtime.

---

## Features

* Dynamic typing
* AST-based execution
* Custom syntax (`-> <-`, `=:`)
* Functions and control flow
* Arrays and basic methods
* Mark-sweep garbage collector

---

## Example

```mks
fnc fib(n) ->
    if (n < 2) ->
        return n;
    <-
    return fib(n - 1) + fib(n - 2);
<-

Writeln(fib(10));
```

---

## Goal

To build a minimal and flexible language with its own runtime and clear internal structure.

---

## Status

Work in progress.
