# Chapter 4 — Your First Program

Example code for Chapter 4 of *Introduction to the Aussom Programming Language*.
These are **scripts**: files ending in `.auss` that Aussom runs top to bottom,
with no class or `main` needed.

## Files

- **`hello.auss`** — the classic first program. Prints `Hello, Aussom!`.
- **`greet.auss`** — a first look at command-line arguments. Greets you by the
  name you type after the file.

## Running

From this directory:

```
aussom hello.auss
```

Expected output:

```
Hello, Aussom!
```

Then try the greeter, with and without a name:

```
aussom greet.auss Ada
aussom greet.auss
```

Expected output:

```
Hello, Ada!
Hello there! Tip: type your name after the file name.
```

Everything here runs with the **Aussom CLI** (`aussom`), which you installed in
Chapter 2. No extra packages are needed.
