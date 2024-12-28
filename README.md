# Lua Pairs Iterator Bug

This repository demonstrates a potential issue with Lua's `pairs` iterator when used with nested tables.  The `pairs` iterator might skip elements or behave unexpectedly if the table structure is modified during iteration.

The `bug.lua` file contains code that showcases this issue.  The `bugSolution.lua` file provides a corrected version.

## Reproducing the Bug

1. Clone this repository.
2. Run `bug.lua` using a Lua interpreter.
3. Observe the unexpected output.

## Solution

The solution involves careful consideration of when and how to modify tables during iteration.  The `bugSolution.lua` file demonstrates alternative approaches that avoid this problem.