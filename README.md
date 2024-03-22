# Porous Matrix Solver

## The Problem

**Objective:** Verify if a solid modeled as a 2D matrix is porous, meaning if it's possible to find a path of white blocks (where water can flow) from the first row (entrance) to the last row (exit).

**Assumptions:**
- Water can flow diagonally (through white blocks that allow it).
- Multiple entrances and exits are allowed.
- 0 = point where water can flow.
- 1 = point where water cannot flow.

## Solution Approach

To solve the problem, we utilize a data structure based on Disjoint Set. The code is designed for a generic NxM matrix. For "Matrix Visualization" three examples of visualization have been provided. To visualize them, simply execute the preceding code: for each randomly generated matrix, the three representations will be displayed.

## Contributors

- [Alberto Taddei](https://github.com/albtad01)
