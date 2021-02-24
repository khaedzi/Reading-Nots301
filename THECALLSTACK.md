
## The Call Stack defined 
* A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function,
* Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
* When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing
![](https://miro.medium.com/max/2048/1*AycFMDy9tlDmNoc5LXd9-g.png)

## How does call stack work ..
* Since the call Stack is organized as a stack, the caller pushes the return address onto the stack, and the called subroutine, when it finishes, pulls or pops the return address   off the call stack and transfers control to that address.
what is the lifo :?
LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## what Error Type of JavaScript
* Reference errors
* Syntax errors
* Range errors
* Type errors
