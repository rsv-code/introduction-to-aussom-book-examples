# Chapter 20 - Organizing Code with Modules

Example code for Chapter 20 of *Introduction to the Aussom Programming Language*.

## Files

- **`main.auss`** - the program; it `include`s the two modules below.
- **`greetings.aus`** - a `Greeter` module (with doc comments for `aussomdoc`).
- **`lib/mathutil.aus`** - a `MathUtil` module in a subfolder.

## Running

```
aussom main.auss
```

Generate documentation from the doc comments:

```
aussom -d greetings.aus
```
