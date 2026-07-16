# Chapter 38 - A Complete Application

The capstone example for *Introduction to the Aussom Programming Language*.

**`tasks.aus`** - a command-line task tracker that stores tasks as JSON on disk. It ties
together classes, file I/O, JSON, lists/maps, command-line arguments, and error handling.

## Running

```
aussom tasks.aus add "Buy milk"
aussom tasks.aus list
aussom tasks.aus done 1
aussom tasks.aus rm 1
```

Tasks are saved to `tasks.json` in the current folder.
