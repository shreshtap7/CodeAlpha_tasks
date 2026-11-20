# CodeAlpha_tasks
# CodeAlpha Python Programming Internship

This repository contains my submissions for the **Python Programming Internship at [CodeAlpha](https://www.codealpha.tech)**. It includes four beginner-friendly console projects that cover core Python concepts such as loops, dictionaries, functions, file handling and string processing.

## Projects

| # | Project | File | Key Concepts |
|---|---------|------|--------------|
| 1 | Hangman Game | `hangman.py` | `random`, `while` loop, `if-else`, strings, lists |
| 2 | Stock Portfolio Tracker | `stock_tracker.py` | dictionary, input/output, arithmetic, file handling |
| 3 | Task Automation (JPG File Mover) | `move_jpg_files.py` | `os`, `shutil`, file handling |
| 4 | Basic Chatbot | `chatbot.py` | `if-elif`, functions, loops, input/output |

---

## Task 1: Hangman Game

A text-based Hangman game where the player guesses a word one letter at a time.

**Features**
- Picks a random word from a list of 5 predefined words
- Allows up to 6 incorrect guesses
- Shows the word progress with underscores and the letters guessed so far
- Validates input (single letters only, no repeated guesses)

**Run**
```bash
python hangman.py
```

**Sample output**
```
Word: _ y _ _ _ n
Guessed letters: n, y
Incorrect guesses left: 6
Enter a letter:
```

---

## Task 2: Stock Portfolio Tracker

Calculates the total investment value of a portfolio using manually defined stock prices.

**Features**
- Uses a hardcoded dictionary of stock prices (e.g. `AAPL: 180`, `TSLA: 250`)
- Takes stock names and quantities from the user
- Handles invalid stock names, invalid quantities and repeated entries
- Displays a per-stock breakdown and the total investment
- Optionally saves the result to `portfolio.txt`

**Run**
```bash
python stock_tracker.py
```

**Sample output**
```
--- Portfolio Summary ---
AAPL: 10 x $180 = $1800
TSLA: 5 x $250 = $1250
Total Investment: $3050
```

---

## Task 3: Task Automation with Python Scripts

**Chosen idea:** move all `.jpg` files from one folder to another.

**Features**
- Asks for a source folder and a destination folder
- Creates the destination folder if it does not exist
- Moves every `.jpg` file (case-insensitive, so `.JPG` also works)
- Skips files that already exist in the destination to avoid overwriting
- Prints each moved file and a final count

**Run**
```bash
python move_jpg_files.py
```

---

## Task 4: Basic Chatbot

A simple rule-based chatbot that replies to predefined inputs.

| User input | Chatbot reply |
|------------|---------------|
| `hello` | Hi! |
| `how are you` | I'm fine, thanks! |
| `bye` | Goodbye! (ends the chat) |
| anything else | Sorry, I don't understand that. |

**Run**
```bash
python chatbot.py
```

---

## Requirements

- Python 3.x
- No external libraries required (only built-in modules: `random`, `os`, `shutil`)

## How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. Run any project with Python, for example:
   ```bash
   python hangman.py
   ```

## About the Internship

CodeAlpha's Python Programming internship focuses on hands-on practice with Python fundamentals, data structures, file handling and automation through real-world style tasks.

## Author

**POTTOLLA SHRESHTA**
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/)

*Submitted as part of the CodeAlpha Python Programming Internship.*
