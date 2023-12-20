# Stack

## Introduction

One of the three data structures is stack. It is a linear data structure that can put things into a stack. You can use this data structure in other languages not just Python. 

## Description

The way stack works is last in first out (LIFO). First in Last out (FILO). Like for example it would kinda look like a stack of plates, stack off cups and other things.

### POP 
Pop is basically removing from the list. Removes the most recently added item. 
### PUSH
Push is basically adding to the list. Adds an item.
## Example

**Stack implementation in python**
Creating a stack
def create_stack():
    stack = []
    return stack


Creating an empty stack
def check_empty(stack):
    return len(stack) == 0


Adding items into the stack
def push(stack, item):
    stack.append(item)
    print("pushed item: " + item)


Removing an element from the stack
def pop(stack):
    if (check_empty(stack)):
        return "stack is empty"

    return stack.pop()


stack = create_stack()
push(stack, str(1))
push(stack, str(2))
push(stack, str(3))
push(stack, str(4))
print("popped item: " + pop(stack))
print("stack after popping an element: " + str(stack))

## Example Problem for student



## 


