# Appendix F - Calling Java and Native Code (AJI and Panama)

Example code for Appendix F of *Introduction to the Aussom Programming Language*.

## Files

- **`aji_demo.auss`** - the **Aussom Java Interface (AJI)**: call Java static methods, create
  Java objects, call instance methods, and read a static field - no Java code or compile step.
- **`panama_demo.auss`** - **Panama**: call native C library functions (`getpid`, `strlen`)
  directly through Java's Foreign Function & Memory API.

## Running

```
aussom aji_demo.auss
aussom panama_demo.auss
```
