# Chapter 19 - Handling Errors

Example code for Chapter 19 of *Introduction to the Aussom Programming Language*.

## Files

- **`errors.auss`** - raising an error with `throw`, catching it (and a language
  error) with `try`/`catch`, and reading the exception with `getText`.
- **`stacktrace.auss`** - a chain of method calls that fails deep down, then reads
  the call chain with `printStackTrace`.

## Running

```
aussom errors.auss
aussom stacktrace.auss
```
