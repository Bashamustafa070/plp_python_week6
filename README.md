```markdown
# Week 6 Assignment - Safe Functions

## Files

- `safe_tools.py` - Contains three safe functions for division, number conversion, and dictionary field lookup.
- `README.md` - Describes the assignment and explains why an `if` check alone cannot catch invalid number conversion.

## Why can the `if` check not catch `abc` on its own?

An `if` check cannot catch `abc` during `int()` conversion because `int("abc")` raises a `ValueError` before the program can continue normally. Using `try` and `except ValueError` allows the program to handle the error safely and return `Not a number` instead of crashing.