# TA Solver

This is one of the final problems of the online course ["How to Code: Complex Data"](https://www.edx.org/course/how-code-complex-data-ubcx-htc2x) by Gregor Kiczales (University of British Columbia).

The core program is a function that takes a list of TAs and a list of time slots as arguments and produces a schedule (if possible). The function only returns a schedule if all of the listed time slots can be filled and no TA is booked for more slots that they are able.

The program is run in [Racket](https://racket-lang.org/download/).

All code my own, aside from what was provided in the base file (which was mostly constant definitions and the base data definitions - no functions). Unfortunately, I did not track changes on GitHub while building the project, which is why the first commit is the completed project.

The core purpose of this project was to practice using fundamentals taught by the course; in this case, generating an arbitrary-arity backtracking search tree. This particular function demonstrates knowledge of mutually recursive functions, functions operating on two or more arguments that are of two or more types, encapsulation with local functions, abstract higher-order functions, and generative recursion. The end result is perhaps not as elegant as I would like it to be, but I am happy to say that it works!

## Acknowledgments

Grateful to Professor Kiczales for putting together a great course!