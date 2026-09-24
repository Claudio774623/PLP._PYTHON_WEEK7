# Week 7 Assignment: Shopping List Manager

This project practices Python lists, indexes, append(), remove(), membership checking, loops, and list summaries.

## Files

- `list_warmup.py` - Demonstrates list creation, index access, append(), remove(), and len().
- `shopping_list.py` - Provides an interactive shopping list manager for adding, removing, showing, and finishing a shopping list.
- `list_report.py` - Prints a numbered shopping list, counts item names with more than 4 letters, and finds the longest item name.

## Why Check `in` Before `.remove()`?

It is safer to check whether an item is in the list before using `.remove()` because `.remove()` causes an error if the item does not exist. Using `in` first allows the program to handle a missing item safely and continue running instead of crashing.

## Technologies Used

- Python
- Visual Studio Code
- Git
- GitHub