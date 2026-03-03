Decrement Operator Logic (Pre vs Post)


📊 Logic Overview
This project demonstrates the operational sequence of decrement operators in C++:
Pre-Decrement (--a): The value is decremented by 1 first, and then the updated value is displayed or used in the expression.
Post-Decrement (a--): The current value is displayed or used in the expression first, and then the decrement occurs for subsequent steps.
Variable State: While both operators reduce the variable by 1, the immediate output depends entirely on the operator's position.


🛠️ Features
Direct Comparison: Provides clear code examples explaining "1st decrement then output" vs "1st output then decrement" logic.
Concise Implementation: Focused on isolated operator behavior to ensure clarity for developers.


🚀 Execution & Environment Guide
To run this project, you will need a C++ compiler or a dedicated IDE.
1. Recommended IDEs
2. Dev-C++
3. Visual Studio Code (VS Code)
4. Online Compilers


2. Simple Execution Procedure
Regardless of the IDE you choose, the logic follows these steps:
(Step 1): Setup the Project
Create a new file named Decrement_Logic.cpp.
Copy and paste the source code into your editor.

(Step 2): Compile the Code
In Dev-C++: Press F11 to Compile and Run.
In VS Code/Terminal: Use the command: g++ Decrement_Logic.cpp -o DecrementDemo.

(Step 3): Observe the Results
Observe the console output to see how the value of a remains 5 during a post-decrement display but becomes 4 in the next call.
