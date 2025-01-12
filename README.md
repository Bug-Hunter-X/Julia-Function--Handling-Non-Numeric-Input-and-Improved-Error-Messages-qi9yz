# Julia Function: Handling Non-Numeric Input and Improved Error Messages

This repository demonstrates a common error in Julia: failing to handle non-numeric input in functions. The `bug.jl` file shows the problematic code, and `bugSolution.jl` provides a more robust solution.

## Problem
The original `myfunction` only correctly handles numeric input. If a non-numeric value is provided, it results in a `MethodError`, which can be challenging to debug without close inspection.

## Solution
The improved `myfunction` in `bugSolution.jl` adds input validation to check for numeric types.  If the input is not numeric, it returns a more informative error message, improving the user experience and debugging.