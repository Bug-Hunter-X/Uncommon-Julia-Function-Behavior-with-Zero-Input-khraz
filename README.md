# Uncommon Julia Function Behavior with Zero Input

This repository demonstrates a subtle issue in a Julia function's handling of zero as input.  The function works correctly for positive and negative numbers, but its behavior with zero is implicit rather than explicitly defined.

The `bug.jl` file contains the original function. `bugSolution.jl` provides an improved version with explicit handling of the zero case.

This example highlights the importance of comprehensive input validation and explicit handling of edge cases in Julia functions to prevent unexpected behavior.