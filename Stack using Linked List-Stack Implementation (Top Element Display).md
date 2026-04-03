# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program

stack = []

for i in range(3):
    value = input(f"Enter element {i+1}: ")
    stack.append(value)

if len(stack) > 0:
    print("\nTop element of the stack:", stack[-1])
else:
    print("Stack is empty")

## Output
Enter element 1: 10

Enter element 2: 20

Enter element 3: 30

Top element of the stack: 30

## Result
The program successfully:

Implements a stack using a list

Inserts elements using append() (push operation)

Retrieves the top element using stack[-1]

Displays the correct top element
