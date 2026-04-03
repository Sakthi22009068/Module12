# 📚 Stack using Linked List: Check and Print the Index Value of the Elements Stored in the Stack

This Python program demonstrates how to:
1. Create a stack using a list.
2. Add elements to the stack.
3. Print the index and corresponding value of each element in the stack.

## 🎯 Aim

To write a Python program that:
- Creates a stack using a list.
- Adds elements to the stack.
- Prints the index values of the stack elements along with the corresponding values.

## 🧠 Algorithm

1. **Create an Empty Stack**:
   - Initialize an empty list `stack` to store elements.

2. **Add Elements to the Stack**:
   - Append elements (e.g., 'a', 'b', 'c') to the stack using the `append()` method.

3. **Print the Initial Stack**:
   - Print the contents of the stack with a message "Initial stack: ".

4. **Iterate through the Stack**:
   - Use a `for` loop with `range()` to iterate through the stack.
   - Print the index value and corresponding element at that index.

5. **Print Index and Value**:
   - For each element in the stack, print the index and the value at that index.

## 📝 Program

stack = []

stack.append('a')
stack.append('b')
stack.append('c')

print("Initial stack:", stack)

print("\nIndex and Value of Stack Elements:")

for i in range(len(stack)):

    print("Index:", i, "Value:", stack[i])


## Sample Input & Output
Initial stack: ['a', 'b', 'c']

Index and Value of Stack Elements:

Index: 0 Value: a

Index: 1 Value: b

Index: 2 Value: c

## Result
The program successfully:

Creates a stack using a list

Adds elements using append()

Iterates through the stack using range()

Prints both index and corresponding values clearly
