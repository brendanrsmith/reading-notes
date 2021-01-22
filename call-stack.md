# Call-Stack
A call stack is the mechanism by which an interpreter keeps track of what function is currently being run.
- When a script calls a fn, it is added to the stack.
- Any function that is called by the original fn is added to the call stack further up. 
- When the current fn finishes, the interpreter takes it off the stack and resumes where it left off on the next item down
- if the stak takes up more space than allocated, you will error "stack overflow"

JS utilized a single call stack, so all functions are run one-at-a-time *(Synchronous)*

In asynchronous JS, the callback fn is acted upon by the call stack during execution after the call back fn has been pushed to the stack by the event loop.

A recursive fn without an exit point will throw a stack overflow.

## Error messages
some error messages we can receive:
### Reference errors
When you try to use a variable that is not yet declared
### Syntax errors
interpreter cannot parse your text
### Range errors
usually means you are using mutable variables, not cool.
### Type errors
incompatible data types, often thrown when you are working with objects something is undefined
### 
