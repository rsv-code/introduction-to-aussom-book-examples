# Chapter 33 - Concurrency Basics

Example code for Chapter 33 of *Introduction to the Aussom Programming Language*.

## Files

- **`workers.aus`** - four threads (`thread`) safely sharing one `AtomicLong` counter (`concurrent`), joined with `join`.

## Running

```
aussom workers.aus
```
