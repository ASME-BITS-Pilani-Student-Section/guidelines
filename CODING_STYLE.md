# Coding Style Guidelines

These guidelines ensure code across the club is **readable, consistent, and maintainable**.
They are strong recommendations—use judgment where necessary.

## Quick Navigation

* [Common Rules](#common-rules-all-languages)
* [C Guidelines](#c-language-guidelines)
* [Python Guidelines](#python-coding-guidelines)

## Common Rules (All Languages)

### Readability First

* Code should be understandable within minutes
* Prefer clarity over cleverness

### Consistency

* Follow existing patterns in the repository
* Avoid mixing styles unnecessarily

### Functions

* Keep functions small and focused
* Avoid deep nesting (~3 levels is a good guideline)

### Naming

* Use meaningful names
* Avoid cryptic abbreviations

### Comments

* Explain **why**, not how
* Keep comments concise and useful

### Code Hygiene

* Remove unused code and debug prints
* Ensure code runs/builds before submitting

## C Language Guidelines

Reference:
https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/process/coding-style.rst

### Formatting

* Use **tabs for indentation** (8 spaces)
* Keep indentation reasonable (avoid deep nesting)
* Aim for **80 column limit** (flexible for practicality)

### Layout

* One statement per line
* Align wrapped lines with opening parenthesis
* `case` labels align with `switch`

### Braces

* Same line for most cases
* Functions: opening brace on next line
* Optional for single-line statements (use judgment)

### Naming & Types

* Prefer short, meaningful names
* Macros:

  * Constants → `UPPERCASE`
* Typedefs allowed (`_t`, `_u`, `_e`)
* Avoid typedef-ing pointers

### Functions

* Should do one logical task
* Use helper functions when needed

### Error Handling

* `goto` for error handling is acceptable (forward jumps)
* Use clear label names

### General Practices

* Prefer modern C features
* Use compiler extensions when helpful
* Minimize excessive preprocessor usage

## Python Coding Guidelines

Reference:
https://peps.python.org/pep-0008/

### Formatting

* Use **4 spaces** (no tabs)
* Line length: **~88 characters**
* Avoid trailing whitespace

### Imports

* Order:

  1. Standard library
  2. Third-party
  3. Local modules

### Naming

* Variables/functions → `snake_case`
* Classes → `PascalCase`
* Constants → `UPPERCASE`

### Structure

* Keep functions small and focused
* Prefer simple, readable logic over clever tricks

### Comments & Docstrings

* Explain **why**, not how
* Use docstrings for public functions and classes

### Error Handling

* Use explicit `try/except`
* Avoid bare `except`

### Type Hints

* Recommended wherever practical

### General Practices

* Prefer built-in features and standard library
* Avoid overly complex one-liners

## Philosophy

* Readability > cleverness
* Consistency > personal preference
* Simplicity > complexity
