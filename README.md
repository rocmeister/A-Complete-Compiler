# A-Complete-Compiler

This is a semester-long compiler project written in Python that encompasses the front-end, optimizer, and the back-end of an ILOC compiler. The compiler takes in as input a set of ILOC (a simple assembly language) instructions, and returns as output a set of scheduled operations optimized for the machine.

The key steps/operations in my compiler are: (in order) 
1. Scan, parse, & rename the input ILOC code
2. Build a dependence graph for the block being scheduled
3. Compute priorities for each operation
4. Schedule the code in a way that preserves the dependences

This Python project makes use of greedy algorithms, linked list data structures, heuristics tuning, as well as shell scripting for testing purposes.