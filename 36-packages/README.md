# Chapter 36 - Creating and Publishing a Package

Example for Chapter 36 of *Introduction to the Aussom Programming Language*.

## Files

- **`string_utils/`** - a small `pure` package source (a `StringUtils` class with `reverse`), scaffolded by `apac -ag -sm` and ready to package.

## Building it

```
apac -p string_utils        # -> string_utils-1.0.0.zip (with generated docs/)
# apac -pub string_utils-1.0.0.zip   # publish (needs a key in apac.yaml)
```
