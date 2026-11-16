
# Week 6 Assignment: Safe Functions

## Description
This assignment demonstrates how to use try and except to handle errors in Python and prevent programs from crashing.

## Files

- safe_tools.py: Contains three safe functions for division, number conversion, and dictionary lookup.
- README.md: Provides assignment information and explains error handling.

## Question: Why can the if check not catch abc on its own?

An if statement can check conditions, but it does not automatically catch errors that happen when Python executes a command. For example, int("abc") causes a ValueError because abc cannot be converted into a whole number. We use try and except to catch this error and display a friendly message instead of crashing the program.