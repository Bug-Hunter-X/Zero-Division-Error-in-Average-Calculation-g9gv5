# Zero Division Error in Average Calculation

This repository demonstrates a common, yet subtle, bug in Python related to zero division errors in average calculations.

The `bug.py` file contains the erroneous code that fails to handle the case where the sum of numbers in the input list is zero, leading to a `ZeroDivisionError`. The `bugSolution.py` file demonstrates how this issue can be resolved by explicitly checking for the sum being zero before performing the division.