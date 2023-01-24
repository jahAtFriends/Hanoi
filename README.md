# Towers of Hanoi

Somewhere deep in the mountains of Hanoi is a monastery. Inside, the monks are hard at
work moving a tower of 64 gold rings of various sizes. Initially, the rings were stacked
largest to smallest on peg. The monks must move them one at a time from this peg to
another; however, they cannot place a small ring on top of a large ring. To help them,
there is a middle "helper" peg that they can use in the process.

But there is a dark side to this story: when the monks complete their task, the world
will end! Your job is to figure out how much time we have left.

## Assignment

In this project, you will write an algorithm to solve the towers problem for _n_ number
of rings. The program should take in an integer from the command line and print out the
step by step solution. Here is an example of what I'm looking for

```bash
java Hanoi 2

Move ring 1 from peg A to peg B.
Move ring 2 from peg A to peg C.
Move ring 1 from peg B to peg C.
```

Your solution should include a recursive method called `solveTower()` which does the bulk
of the work and contains at most four lines of code (if-statements count as one line).
Started code has been given to you help you structure your solution.
