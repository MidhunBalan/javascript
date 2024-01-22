# Javascript Execution Context

## Key Points:
* Everything in Javascript happens inside an Execution context
* Execution context has two parts, 
  1. Variable Environment(Memory Allocation Phase)
  2. Thread of Execution (Code Execution Phase) 

* Javascript is a synchronous single-threaded language. 
  → That means javascript can executed one command at a time in a specific order. 
  → It can only go to the next line once the current line has finished execution. 

* What happen when you run a Javascript program?
  → Execution context is created.

| Variable Environment (Memory Allocation Phase) | Thread of Execution (Code Execution Phase)  |
| --- | --- |
| Place where all the variables and functions are stored as a key value pair.  | Place where execution happens |
| a: 10
fn: {…} |  |

* CallStack
    → It is to manage the execution context. 
    → Call stack maintains the order of execution of `execution context`


Reference For Clear Explanation
```https://dev.to/narottam04/how-javascript-works-visually-explained-269j```