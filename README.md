# PLP Python Week 6 Assignment: Safe Functions

## Files

- `safe_tools.py` — Contains three safe functions using `try` and `except` to handle division by zero, invalid number conversion, and missing dictionary keys.
- `README.md` — Provides the assignment title, file descriptions, and an explanation of error handling.

## Why can the `if` check not catch `abc` on its own?

An `if` statement cannot automatically determine whether arbitrary text can be converted into an integer. The `int()` function raises a `ValueError` when the text is invalid, so `try` and `except` are used to catch the error and return `"Not a number"` instead of crashing the program.