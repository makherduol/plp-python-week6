PLP Python Week 6
Files

safe_tools.py — Contains three safe functions for division, number conversion, and dictionary field lookup.

unbreakable.py — Contains the Week 6 error-handling exercise.

README.md — Describes the files and explains why an if check cannot catch invalid number text on its own.

An if check cannot catch "abc" when converting it with int() because the conversion itself raises a ValueError before a normal condition can handle the result. Using try and except allows the program to safely handle that error.
