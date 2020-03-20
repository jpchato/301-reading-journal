# Call Stack
* A mechanism for an interpreter to keep track of its place in a script that calls multiple functions
* When a script calls a function, the interpreter(JS) adds it to the call stack and then carries out the function
* Functions that are called by that function are added to the call stack, and run when their call is reached
* When a function is finished, it is removed from the call stack 
* If the stack takes up more space than it has assigned to it, it will result in a stack overflow

# Understanding the JavaScript Call Stack
* The call stack is primarily used for function invocation
* Function execution is done one at a time from top to bottom. The call stack is synchronous
* Last in, first out to temporarily store and manage function invocations
* When a function is invoked, the function, its parameters, and variables are pushed into the call stack to form a stack frame
* Manage function invocation (call): The call stack maintains a record of the position of each stack frame. It knows which function will be executed next and it will remote it after its execution. Therefore, JS is synchronous.
* Stack overflow occurs when there is a recursive function without an exit point
* Summary
  * Callstack is single-threaded. It can only do one thing at a time
  * Code execution is synchronous
  * Function invocations create stack frames that occupy temporary memory
  * Last in first out

  # JavaScript Error Messages and Debugging
  * Reference errors
  * Syntax errors
  * Range errors
  * Type errors
  * Learning to read error messages and practicing debugging will improve skills as a developer. Remove bugs before acp