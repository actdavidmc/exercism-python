## [2026-05-04] Hello World

### 💡 Key Concepts
- **Function Structure:** Defined a basic function using the `def` keyword and ensured it returns a string instead of just printing it.
- **Strings:** Practiced basic string manipulation and the importance of exact character matching for passing tests.
- **Return Statement:** Reinforced the concept that `return` provides a value to the caller, which is essential for unit testing.

### 🛠 Workflow & Troubleshooting
- **Environment Setup:** Configured the development environment using **uv** and **Python 3.12** on macOS.
- **File Versioning:** Established my personal naming convention by creating `hello_world_original.py` to preserve the initial boilerplate code.
- **Test Execution:** Ran my first successful test suite using `pytest`. I learned how to interpret the terminal output to verify my solution.

### 📝 Technical English Practice
- **Unit Test:** A script (like `hello_world_test.py`) that checks if a small piece of code works as expected.
- **Return Value:** The result that a function sends back after it finishes executing.
- **Invoke:** To call or execute a function (e.g., "I need to invoke the `hello()` function").

## [2026-05-05] Guido's Gorgeous Lasagna

### 💡 Key Concepts
- **Constants:** Defined `EXPECTED_BAKE_TIME = 40` using `SCREAMING_SNAKE_CASE` for global visibility.
- **Function Composition:** Practiced calling one function inside another (DRY principle) to calculate elapsed time.
- **Docstrings:** Implemented triple double quotes `"""` to document function behavior and parameters.

### 🛠 Workflow & Troubleshooting
- **File Management:** Applied my "Original Backup" strategy (`lasagna_original.py`) to preserve the initial boilerplate.
- **Config Fix:** Resolved a `TOML` formatting error in `pyproject.toml` by correcting the `authors` list syntax.
- **Common Pitfall:** Corrected a `SyntaxError`; I learned that `def` statements do not use `=` to assign parameters.

### 📝 Technical English Practice
- **Boilerplate:** The starting code provided by the platform.
- **Parameter vs. Argument:** The variable in the `def` vs. the actual value passed during the call.
- **Runtime:** The period when the Python interpreter is actually executing the code.

## [2026-05-06] Ghost Gobble Arcade Game

### 💡 Key Concepts
- **Boolean Logic:** Combined multiple boolean conditions (`and`, `or`, `not`) to determine complex game states like winning and losing.
- **Function Interdependency:** Implemented the `win()` function by leveraging the logic already defined in the `lose()` function (composition).
- **Conditional Returns:** Used concise boolean expressions directly in `return` statements instead of verbose `if-else` blocks.

### 🛠 Workflow & Troubleshooting
- **Test Failure Analysis:** Analyzed `AssertionError` messages from `pytest` to understand why `win(True, True, True)` was failing.
- **Logic Debugging:** Realized that the initial logic for `win` was too restrictive and needed to account for the power pellet being active.

### 📝 Technical English Practice
- **Power Pellet:** A special item that empowers the player (Pac-Man) to eat ghosts.
- **AssertionError:** An error raised when a test's condition is not met (Expected vs. Actual).
- **Boolean Expression:** A logical statement that results in either `True` or `False`.
- **Composition:** The practice of using the results or calls of one function to build another.

## [2026-05-07] Currency Exchange & Refactoring logic

### 💡 Key Concepts
- **Simplifiable If-Expressions:** Learned to avoid redundant `return True if condition else False` by returning the `condition` directly, making the code more "pythonic".
- **Modulo & Floor Division:** Applied `%` to find leftovers and `//` to calculate the number of whole bills that fit into a given amount.
- **Code Nesting & Reuse:** Refactored the final task by nesting function calls (e.g., passing `exchange_money` into `get_number_of_bills`), which follows the DRY (Don't Repeat Yourself) principle.
- **Spread calculation:** Practiced percentage-to-decimal conversion to calculate exchange fees correctly.

### 🛠 Workflow & Troubleshooting
- **Git Versioning Control:** Mastered undoing mistakes using `git restore --staged` to unstage files and `git reset --soft HEAD~1` to revert a commit while preserving local changes.
- **Conventional Commits:** Standardized commit messages using `feat:`, `refactor:`, and `fix:` with specific scopes like `(exchange)` or `(ghost)`.
- **Pathspec Errors:** Resolved terminal errors by understanding that Git paths are relative to the current working directory.

### 📝 Technical English Practice
- **Spread:** The percentage fee or commission taken during a currency exchange.
- **Denomination:** The face value of an individual banknote or bill.
- **Unstage:** The process of removing files from the Git index before they are committed.
