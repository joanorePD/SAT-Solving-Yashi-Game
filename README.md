# Solving the Yashi game using a SAT solver

This is the final project for the course "Knowledge and Data Mining". It consists on using the satisfiability techniques learnt throughout the course in order to solver an randomly generated instance of a Yashi game/puzzle.

An instance of the Yashi game is specified by a n×n integer grid for some n > 2, on which p > 2 nodes
are placed. A solution of the game consists in drawing horizontal and vertical segments, satisfying the
following conditions:

1. Every segment connects two and only two nodes.
2. No two segments overlap.
3. No two segments cross each other.
4. The segments form a tree, i.e., they form a graph without cycles. Put differently still, for every
two nodes a and b there is exactly one path between a and b.

## Code

The notebook named "yashi" plainly solves the Yashi game without using any SAT method. 
The notebook named "yashi_sat" uses both a SAT solver and a Z3 solver.
