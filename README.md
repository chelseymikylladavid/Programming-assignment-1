# Programming Assignment

This repository contains solutions to several introductory Python programming exercises implemented in a Jupyter Notebook.

## Features
- **Alphabet Soup**: A function that rearranges the letters of a string into alphabetical order.
- **Emotify**: A function that replaces words like "smile", "grin", "sad", and "mad" with corresponding emoticons.
- **List Unpacking**: Demonstrates Python’s ability to unpack lists into first, middle, and last elements.
- Additional examples included with comments and outputs.

## Files
- `programmingassignment.ipynb` – Jupyter Notebook with the code solutions.

## Getting Started
To run this notebook on your computer:

## Unpacking the files 
### 1. Alphabet Soup
**File:** `programmingassignment.ipynb`  
**Function:** `alphabet_soup(s)`  

- Rearranges the letters of a string into alphabetical order.  
- Example:
  ```python
  alphabet_soup("hello")   # Output: "ehllo"
  alphabet_soup("hacker")  # Output: "acehkr"
  alphabet_soup("Chelsey") # Output: "Ceehlsy"

### 2. Emotify
**File:** `programmingassignment.ipynb`  
**Function:** `Emoticon(s)`  

- Interchange the word with an emoji.  
- Example:
  ```python
  emotify("Make me smile")       # "Make me :)"
  emotify("I am mad")            # "I am >:("
  emotify("Feeling sad today")   # "Feeling :(( today"
  emotify("Big grin")            # "Big :D"

### 3. List Unpacking
**File:** `programmingassignment.ipynb`  
**Function:** `Unpacking(s)`  

- This will output the first, middle, and last numbers.  
- Example:
  ```python
  lst = [1, 2, 3, 4, 5, 6]
  first, *middle, last = lst
  print("first:", first, "middle:", middle, "last:", last)
  # Output: first: 1 middle: [2, 3, 4, 5] last: 6



  
