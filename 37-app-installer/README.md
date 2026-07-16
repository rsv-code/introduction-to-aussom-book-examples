# Chapter 37 - Packaging an Application

Example for Chapter 37 of *Introduction to the Aussom Programming Language*.

## Files

- **`todo/`** - a small app package with a `main(args)` in `todo.aus`, an `installer:` block in `package.yaml`, and a scaffolded `package-files/` folder.

## Building an installer

```
cd todo
apac -ib -t deb        # build the .deb on Linux (use msi on Windows, pkg on macOS)
apac -ib --dry-run     # preview the jpackage command without building
```

The installer lands in `target/installer/<platform>/`.
