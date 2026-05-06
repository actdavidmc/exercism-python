# Exercism Journey: Python Track

This is my personal repository for the Python track on Exercism.

## Overview

This repository contains my solutions to the exercises in the Python track on Exercism. My goal is to improve my Python skills and learn new concepts. Also, I'll be using this repository to document my journey and the concepts I learn.

## Project Structure

Inside each folder is the exercise *provided* by *Exercism* through the command line interface (CLI).

To download a new exercise, I use:
```bash
exercism download --track=python --exercise=<exercise-slug>. 
```

On the other hand, to submit a solution for review by the community, I use:

```bash
exercism submit <exercise-name>/<solution-file>
```

The commands and the folder structure can be seen in the [Exercism CLI Documentation](https://exercism.org/docs/using/command-line-interface)

## Workflow Strategy

To maintain a clean and traceable environment, I follow this process for every exercise:

1. **Backup:** I create a copy of the original boilerplate file (e.g., `hello_world_original.py`) before writing any code.
2. **Development:** I work directly on the main file (e.g., `hello_world.py`) to keep it compatible with the provided test suite.
3. **Testing:** I run tests frequently using `pytest` to ensure the solution meets all requirements.

## Learning Log

This is a table that logs the exercises I complete and the concepts I learn. To see more details about each exercise, I recommend checking my [Learning Log](./LEARNINGLOG.md).

| Date | Exercise | Concepts |
| :--- | :--- | :--- |
| 2026-05-04 | [Hello World](./hello-world) | Functions, strings and return statement. |
| 2026-05-06 | [Guido's Gorgeous Lasagna](./guidos-gorgeous-lasagna) | Constants, parameters, arithmetic operators and function calls. |
