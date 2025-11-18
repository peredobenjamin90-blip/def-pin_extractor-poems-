📌 Pin Extractor

This program takes one or more poems and generates a numeric PIN for each one by analyzing the length of specific words based on their line index.

How it works (simple explanation):

Each poem is split into lines

For each line, it finds the word that matches the line number (line 0 → word 0, line 1 → word 1, etc.)

It adds the length of that word to the PIN

If that word does not exist, it adds 0

Example output:
['5202', '3430', '15111']

📚 Credits

This project is based on a freeCodeCamp exercise, completed as part of my learning and practice.
