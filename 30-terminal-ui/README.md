# Chapter 30 - Colorful Terminals and Text UIs

Example code for Chapter 30 of *Introduction to the Aussom Programming Language*.

**Run these in a real terminal window** so the colors and full-screen UIs display.

## Files

- **`colors.auss`** - colored, bold, and underlined text with `jansi`.
- **`dashboard.auss`** - clearing the screen and placing text with the cursor (`jansi`).
- **`form.aus`** - an interactive contact form (`curses`): components, a layout, and a menu.
- **`dialog.aus`** - a modal message dialog (`curses`).

## Running

```
aussom colors.auss
aussom dashboard.auss
aussom form.aus        # interactive - tab between fields, use the File menu
aussom dialog.aus
```
