# Audit: Fibonacci Program in Python

| No. | README Claim                                                                | Verdict       | Evidence from the Code                                                                                                            |
| --: | --------------------------------------------------------------------------- | ------------- | --------------------------------------------------------------------------------------------------------------------------------- |
|   1 | The program prints a specified number of terms from the Fibonacci sequence. | **Supported** | `n = int(input("How many terms? "))` accepts the number of terms, and `for i in range(n):` repeats the process `n` times.         |
|   2 | Python must be installed on the computer to run the program.                | **Supported** | The program contains Python statements that require a Python interpreter for execution.                                           |
|   3 | The user should open a terminal in the folder containing `fibonacci.py`.    | **Supported** | The script can be executed from a terminal when the file is accessible from the current directory or its path is specified.       |
|   4 | The command `python fibonacci.py` runs the program.                         | **Supported** | The provided code is valid Python. The command works if the file is saved as `fibonacci.py` and `python` is configured correctly. |
|   5 | The program prompts the user to enter the number of terms.                  | **Supported** | `input("How many terms? ")` displays a prompt and accepts user input.                                                             |
|   6 | The program demonstrates Python variables.                                  | **Supported** | The variables `n`, `a`, `b`, and `i` store the number of terms, Fibonacci values, and loop counter.                               |
|   7 | The program demonstrates loops.                                             | **Supported** | `for i in range(n):` uses a `for` loop to generate the requested number of terms.                                                 |
|   8 | The program demonstrates how to update multiple variables.                  | **Supported** | `a, b = b, a + b` updates both variables in a single assignment to generate the next Fibonacci values.                            |
|   9 | The program displays a sequence of numbers using `print()`.                 | **Supported** | `print(a, end=" ")` displays each Fibonacci number, separated by spaces.                                                          |

## Audit Summary

* **Total claims audited:** 9
* **Supported:** 9
* **Not Supported:** 0

**Conclusion:** All README claims are supported by the provided Python code.

**Additional observation:** The code does not validate the input. If the user enters a negative integer, the loop does not execute, and no Fibonacci terms are displayed.
