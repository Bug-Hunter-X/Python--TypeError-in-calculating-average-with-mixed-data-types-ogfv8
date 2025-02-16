# Python: TypeError when calculating average with mixed data types
This repository demonstrates a common Python error: a `TypeError` that occurs when calculating the average of a list containing both numbers and strings.  The `sum()` function is unable to operate on strings, leading to an error.

The `bug.py` file contains the erroneous code, while `bugSolution.py` presents a corrected version that handles mixed data types gracefully.

## How to reproduce the error
1. Clone this repository
2. Run `bug.py`
3. Observe the `TypeError`

## Solution
The solution involves data validation and error handling to prevent this `TypeError`. The solution code demonstrates a better approach using exception handling, type checking, and filtering to only use numbers in the calculation.