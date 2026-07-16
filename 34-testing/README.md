# Chapter 34 - Testing Your Code

Example code for Chapter 34 of *Introduction to the Aussom Programming Language*.

## Files

- **`calc.aus`** - a small `Calculator` class (the code under test).
- **`calctest.aus`** - `aunit` tests for it: `@Test` methods, `@BeforeEach` setup, `test.expect` assertions.
- **`strutil.aus`** - a second class to test, `StringUtil`.
- **`strutiltest.aus`** - `aunit` tests for `StringUtil`.
- **`alltests.aus`** - an aggregator that `include`s both suites so `-ta` runs them together.

## Running

Run one suite:

```
aussom -t calctest.aus
```

Run every suite at once (test-all):

```
aussom -ta alltests.aus
```
