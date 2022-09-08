# Debugging

## Syntax and Logical errors

When programming, there can be errors. An error is an unexpected output of the program. These errors can affect the proper execution of the program.
Therefore, it is necessary to remove all errors.
The key difference between syntax error and logical error is that, the syntax error occurs due to an error in the syntax of a sequence of characters
or tokens that is intended to be written in a particular programming language while logical error is an error that occurs due to the fault
in the program algorithm or the logic.

## The JavaScript Debugger

The ***JS Debugger*** keyword stops the execution of JavaScript, and calls (if available) the debugging function.
This has the same function as setting a breakpoint in the debugger. If no debugging is available, the debugger statement has no effect.
With a debugger, you can also set ***breakpoints*** (places where code execution can be stopped), and examine variables while the code is executing.
At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.
After examining values, you can resume the execution of code (typically with a play button).
A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that
calls multiple functions — what function is currently being run and what functions are called from within that function.
