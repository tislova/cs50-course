# CS50x: Problem Sets & Projects

Solutions and projects from Harvard's **CS50x: Introduction to Computer Science**, 
taught by [David J. Malan](https://cs.harvard.edu/malan).

This repository is an archive of coursework completed during the course. 
For original portfolio projects, see my [pinned repositories](https://github.com/tislova).

## About CS50x

CS50x is Harvard's introduction to computer science and programming, covering 
algorithmic thinking, low-level memory management, data structures, databases, 
and web development.

## Problem Sets

### Week 1: C Fundamentals
- **`mario.c`** — Generates a Mario-style pyramid of hashes with adjustable height. 
  Practice with loops, nested loops, and user input validation.

### Week 2: Arrays & Strings
- **`scrabble.c`** — Simulates a Scrabble round between two players, computing 
  word scores from a letter-value lookup table.
- **`readability.c`** — Calculates the Coleman-Liau readability index of input 
  text by counting letters, words, and sentences.

### Week 3: Algorithms
- **`plurality.c`** - Implements the plurality voting method (most votes wins) 
  with support for ties.
- **`runoff.c`** — Implements ranked-choice voting with elimination rounds, 
  tie detection, and majority calculation. Uses structs and 2D arrays.

### Week 4: Memory
- **`volume.c`** — Modifies the volume of a `.wav` audio file by reading raw 
  byte data, scaling 16-bit samples, and writing to a new file.
- **`recover.c`** — Recovers deleted JPEG images from a raw memory card by 
  scanning for JPEG file signatures and reconstructing files block-by-block.

### Week 5: Data Structures
- **`inheritance.c`** — Simulates genetic inheritance of blood types across 
  three generations using recursive struct allocation, pointer-linked family 
  trees, and proper memory cleanup with `free()`.

### Week 6: Python
- **`credit.py`** — Validates credit card numbers using Luhn's algorithm and 
  identifies the issuer (Visa, MasterCard, AMEX). C version also included 
  in `credit.c`.
- **`readability.py`** — Python port of the Coleman-Liau readability calculator.
- **`mario.py`** — Python port of the pyramid generator.
- **`substitution.c`** — Substitution cipher implementation with input 
  validation for repeated/invalid characters.

### Week 7: SQL
- **`fiftyville/`** — Forensic SQL investigation: write queries against a 
  crime scene database to identify the thief, their getaway city, and 
  accomplice. Practices `JOIN`, subqueries, and filtering.

### Week 8: HTML, CSS, JavaScript
- **`trivia/`** — Interactive multiple-choice trivia page with instant 
  feedback styling.
- **`homepage/`** — Multi-page personal site built from scratch with 
  semantic HTML and CSS.

### Week 9: Flask
- **`birthdays/`** — Web app that stores and displays birthdays using Flask 
  and SQLite. Practices form handling, server-side validation, and 
  database queries.
- **`finance/`** — Stock trading simulation. Users register, query real-time 
  stock prices via API, "buy" and "sell" shares, and view their portfolio 
  and transaction history. Built with Flask, SQLite, and Werkzeug 
  authentication.

## Skills Demonstrated

- **C programming** — Manual memory management, pointers, structs, file I/O, 
  bitwise operations
- **Algorithm design** — Voting algorithms, Luhn validation, signature-based 
  file recovery, recursive data structures
- **Python** — Translating low-level C logic to higher-level Python idioms
- **SQL** — Multi-table joins, subqueries, forensic data analysis
- **Web development** — Semantic HTML, CSS layouts, Flask routing, Jinja 
  templating, server-side form handling
- **Database design** — Schema design and SQL integration in Flask apps
- **Security basics** — Password hashing with Werkzeug, input validation, 
  parameterized queries

## Running the Code

**C programs:**
```bash
clang -o mario mario.c
./mario
```

**Python scripts:**
```bash
python3 readability.py
```

**Flask apps (finance, birthdays):**
```bash
cd finance/
pip install -r requirements.txt
flask run
```
