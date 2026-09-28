# 🐍 Python Programming Assignment

A collection of beginner-friendly **Python programming exercises** covering functions, numbers, strings, loops, character processing, patterns, and basic problem-solving techniques.

The assignment is implemented in a **Jupyter Notebook** and is organized into four sections, with each section containing small reusable functions followed by example executions.

## 📌 Project Overview

This assignment focuses on building Python fundamentals through practical programming problems.

The notebook covers:

- Basic function creation and return values
- Conditional statements
- Loops and iteration
- Number-based problems
- String manipulation
- Character and word counting
- Palindrome checking
- Case analysis
- Vowel and consonant processing
- Pattern generation using nested loops

## 📚 Assignment Sections

### Section A — Basic Functions

This section contains functions for common numerical and logical operations.

| Function | Purpose |
|---|---|
| `oddeven()` | Checks whether a number is odd or even |
| `check()` | Determines whether a number is positive, negative, or zero |
| `larger()` | Finds the larger of two numbers |
| `larger3()` | Finds the larger of three numbers |
| `sum_natural()` | Calculates the sum of natural numbers up to `n` |
| `multiplication_table()` | Prints the multiplication table of a number |
| `factorial()` | Calculates the factorial of a number |
| `count_digits()` | Counts the number of digits in a number |
| `reverse_number()` | Reverses a number |
| `check_prime()` | Checks whether a number is prime |

Example:

```python
def oddeven(n):
    return "Even" if n % 2 == 0 else "Odd"

print(4, "is", oddeven(4))
```

---

### Section B — Strings

This section focuses on character-level and string manipulation problems.

| Function | Purpose |
|---|---|
| `count_characters()` | Counts characters in a string |
| `count_vowels()` | Counts vowels in a string |
| `count_consonants()` | Counts consonants in a string |
| `count_vowels_consonants()` | Counts vowels and consonants together |
| `reverse_string1()` | Reverses a string using slicing |
| `reverse_string2()` | Reverses a string using a loop |
| `check_palindrome()` | Checks whether a string is a palindrome |
| `count_words()` | Counts words in a string |
| `character_frequency()` | Counts occurrences of a specified character |
| `remove_spaces()` | Removes spaces from a string |
| `convert_uppercase1()` | Converts a string to uppercase using `.upper()` |
| `convert_uppercase2()` | Converts lowercase letters using `ord()` and `chr()` |

The notebook demonstrates two different approaches for some problems, such as reversing a string:

```python
def reverse_string1(text):
    return text[::-1]
```

and:

```python
def reverse_string2(text):
    s = ''
    for i in text:
        s = i + s
    return s
```

## 🔄 Section C — String + Loop Problems

This section combines strings, loops, conditions, and character analysis.

| Function / Program | Purpose |
|---|---|
| `count_case()` | Counts uppercase letters, lowercase letters, digits, and spaces |
| `first_character()` | Returns the first character |
| `last_character1()` | Returns the last character using indexing |
| `last_character2()` | Finds the last character through iteration |
| `display_characters()` | Prints characters one by one |
| `display_position()` | Displays each character along with its position |
| `remove_vowels()` | Removes vowels from a string |
| `find_longest_word()` | Finds the longest word in a sentence |
| `vowel_occurance()` | Counts occurrences of each vowel |

Example:

```python
def display_position(text):
    for i in range(len(text)):
        print(f'Position {i}: {text[i]}')
```

The notebook also demonstrates basic text preprocessing using:

```python
replace()
split()
lower()
```

---

## 🔢 Section D — Loops, Patterns and Menus

The final section focuses on nested loops and pattern generation.

| Function | Purpose |
|---|---|
| `star_pattern()` | Generates a triangular star pattern |
| `star_pyramid()` | Generates a pyramid-style star pattern |
| `number_pattern()` | Generates an increasing number pattern |

Example output for `star_pattern(5)`:

```text
*
**
***
****
*****
```

Example output for `number_pattern(5)`:

```text
1
12
123
1234
12345
```

## 🛠️ Technologies Used

- **Python 3**
- **Jupyter Notebook**
- Python built-in functions and string methods

No external libraries are required for the exercises in this notebook.

## ▶️ How to Run

### Using Jupyter Notebook

1. Clone or download this repository.
2. Open `Assignment_1.ipynb` in **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.
3. Run the cells from top to bottom.
4. Modify the sample function inputs to experiment with different values.

### Using Google Colab

The notebook can also be uploaded directly to Google Colab and executed cell by cell.

## 📂 Project Structure

```text
Python-Assignment-1/
│
├── Assignment_1.ipynb
└── README.md
```

## 🎯 Learning Objectives

This assignment helps practice:

- Defining and calling functions
- Function parameters and return values
- `if`, `elif`, and `else`
- `for` and `while` loops
- Nested loops
- Arithmetic operations
- Number-based problem solving
- String indexing and slicing
- String methods
- Character classification
- Basic input/output
- Pattern printing
- Problem decomposition into reusable functions

## 🧠 Python Concepts Demonstrated

The notebook provides hands-on examples of:

```python
# Conditional expression
return "Even" if n % 2 == 0 else "Odd"
```

```python
# String slicing
text[::-1]
```

```python
# Character conversion
chr(ord(i) - 32)
```

```python
# String processing
text.lower()
text.split()
text.replace(",", "")
```

```python
# Nested loops
for i in range(1, n + 1):
    for j in range(1, i + 1):
        print(j, end='')
```

## 📈 Scope for Improvement

Possible extensions to the assignment include:

- Adding user-input-driven versions of all programs
- Improving input validation and handling negative values
- Adding more efficient prime-number and factorial implementations
- Handling uppercase vowels in vowel-related functions consistently
- Adding test cases for each function
- Converting the exercises into a menu-driven Python application
- Adding automated unit tests using `pytest`
