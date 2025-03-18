INET 3101 Lab 2: Memory and Structures
Overview
This lab implements an in-memory database in C using dynamic memory allocation. It manages records without using fixed-size arrays by allocating and resizing memory with malloc(), realloc(), and free().

Features
Records (Stored in a Structure):

Part Number (int)
Part Name (char[])
Part Size (float)
Part Size Metric (char[], e.g., "mm")
Part Cost (float)
Menu Options:

Print all records
Print number of records
Print size of database (in bytes)
Add a record
Delete the last record
Exit
Dynamic Memory Management:

Uses malloc() to allocate memory for records.
Expands/shrinks memory dynamically with realloc().
Releases memory with free() when deleting records.
How to Compile and Run
On Windows (VS Code & MinGW)
Install a C Compiler

Download and install MinGW-w64.
Add the MinGW bin directory to your system PATH.
Open VS Code

Install the C/C++ Extension by Microsoft.
Open the folder containing main.c.
Compile the Code
Open the terminal in VS Code (Ctrl+`) and run:

sh
Copy code
gcc main.c -o main.exe
Run the Program

sh
Copy code
.\main.exe
Files
main.c → C source code implementing the lab requirements.
README.md → This file with project details.
GitHub Repository
Create a repository on GitHub (e.g., https://github.com/yourusername/inet3101-lab2).
Push all project files, including this README.md.
