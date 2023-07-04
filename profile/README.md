# Collatz Prefixes

> A pattern among hailstone numbers. Read the [Gitbook](https://erhany96.gitbook.io/collatz-prefixes) for the theory.

Implementing the theory in code is a simple & fun side-project, and a great excuse to try a new language. As such, I have implemented Collatz Prefixes in a few languages:

- [Go](https://github.com/collatz-prefixes/collatz-prefixes-go)
- [C++](https://github.com/collatz-prefixes/collatz-prefixes-cplusplus)
- [Rust](https://github.com/collatz-prefixes/collatz-prefixes-rust)
- [Haskell](https://github.com/collatz-prefixes/collatz-prefixes-haskell)
- [TypeScript](https://github.com/collatz-prefixes/collatz-prefixes-typescript)
- Python (not yet public)

At it's current state, the Rust implementation is the most performant (not a surprise).

Why is it a great excuse as said above? Here are a few reasons in my opinion:

- It has use-cases for bitwise operations.
- It makes use of both pass-by-value and pass-by-reference.
- It has static and dynamic arrays.
- It has well-defined and simple test cases.
- It makes use of bigints if possible.
- It provides a good excuse to separate code into modules, both public and private.
