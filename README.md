# Scientific calculator

A menu-driven scientific calculator written in C.

This is early work from when I was first learning to program, and it is here as a record rather than a showcase. It covers the usual set of operations: arithmetic, powers and roots, logarithms, trigonometric functions, factorials, with input handled in a loop so the calculator keeps running until you exit.

Writing it taught me more about handling bad input than about mathematics. Deciding what should happen when someone asks for the square root of a negative number, or the factorial of something that is not a whole number, turned out to be most of the actual work.

## Building

    gcc calculator.c -o calculator -lm

The `-lm` flag links the maths library, which the trigonometric and logarithm functions need.
