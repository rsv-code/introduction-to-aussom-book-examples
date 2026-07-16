# Chapter 28 - Script Mode

Example code for Chapter 28 of *Introduction to the Aussom Programming Language*.

## Files

- **`greet.auss`** - a script (no class/main) that reads `args`, uses an exit code, and has a shebang so it runs directly.

## Running

```
aussom greet.auss Ada Grace
chmod +x greet.auss && ./greet.auss Ada
aussom greet.auss          # no args -> usage + exit 1
```
