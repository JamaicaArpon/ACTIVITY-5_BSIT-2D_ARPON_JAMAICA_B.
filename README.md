# Stacks and Queues Laboratory Activity
## Title
Stacks and Queues: Array vs Linked List

## Project Overview
This laboratory implements four fundamental data structures: ArrayStack, LinkedStack, CircularArrayQueue, and LinkedQueue. A menu‑driven driver allows users to perform operations and view the current state after each action. The program raises descriptive exceptions for overflow and underflow.

## Files Included
- array_stack.py
- linked_stack.py
- circular_array_queue.py
- linked_queue.py
- main.py
- analysis.md
- sample-runs.md

## Requirements
- Python 3.x
- No additional libraries required

## How to Run
1. Place all files in one folder.
2. Open terminal and run:
```bash
python main.py

3. Main menu options:
 
- 1 = Test ArrayStack
​
- 2 = Test LinkedStack
​
- 3 = Test CircularArrayQueue
​
- 4 = Test LinkedQueue
​
- 5 = Exit
 
4. Sub‑menu operations:
 
- Stacks: Push, Pop, Peek, Print
​
- Queues: Enqueue, Dequeue, Peek Front, Print
​
- The program prints the state after each operation
​
- Error messages appear for overflow and underflow
 
Features
 
- ArrayStack uses a top index starting at -1
​
- LinkedStack operates only at the head for O(1) efficiency
​
- CircularArrayQueue uses modulo arithmetic for wrap‑around and a size counter
​
- LinkedQueue maintains both front and rear pointers
​
- Exception handling for overflow and underflow
​
- Menu‑driven interface
​
- State printed after each operation
 
Sample Runs
 
- ArrayStack: Enter capacity first; pushing beyond capacity causes overflow
​
- LinkedStack: No fixed capacity; popping empty stack causes underflow
​
- CircularArrayQueue: Enter capacity first; enqueuing past the end demonstrates wrap‑around
​
- LinkedQueue: No fixed capacity; dequeuing empty queue causes underflow
 
Author
 
[ARPON, JAMAICA B. ]
[BSIT-2D]
[ACTIVITY-5_BSIT2D_ARPON_JAMAICA_B.]
