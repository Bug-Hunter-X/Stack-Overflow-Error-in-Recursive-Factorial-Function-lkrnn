# Stack Overflow in Hack Recursive Function

This repository demonstrates a common error in recursive functions written in Hack: stack overflow. The `bug.hack` file contains a factorial function that uses recursion.  When called with a large enough input, this function will exceed the maximum call stack depth and crash.  The solution, in `bugSolution.hack`, demonstrates how to refactor the function to use iteration instead, preventing the stack overflow error.

## How to Run

1.  Make sure you have the HHVM (HipHop Virtual Machine) installed and configured.
2.  Compile the code using the Hack compiler.
3.  Run the compiled code using HHVM.