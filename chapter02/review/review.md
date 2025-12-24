# Review Questions – Chapter 1

---

## 1. What is the purpose of the “Hello, World!” program?

To test my programming environment and to give me a first feeling of how to make a computer do things.  
Actually, this is not my first time programming. I am just refreshing my knowledge. My first experience with programming was in February 2022 when I got my first laptop.

---

## 2. Name the four parts of a function.

The four parts of a function are:
- the return type  
- the function name  
- the list of parameters enclosed in parentheses  
- the function body inside curly braces  

---

## 3. Name a function that must appear in every C++ program.

The `main` function must appear in every C++ program because it is the entry point of the program.  
It is like the door of a house: the program always starts from `main`.

---

## 4. In the “Hello, World!” program, what is the purpose of the line `return 0;`?

In the Hello, World program, it does not seem to mean much because the `main` function is called by the system or operating system, so the return value is not directly used by the program itself.  
However, on some operating systems such as Unix or Linux, the return value is used to check whether the program ran successfully (`0`) or not (non-zero).

---

## 5. What is the purpose of the compiler?

Since our instructions are written in a human-readable language such as C++, they need to be translated into machine language.  
That is why we need a compiler: to translate C++ code into machine language such as binary instructions (for example, 0s and 1s).

---

## 6. What is the purpose of the `#include` directive?

The purpose of the `#include` directive is to include files or code declarations from other files into the current source file.

---

## 7. What does a `.h` suffix at the end of a file name signify in C++?

The `.h` suffix means header.  
A file with a `.h` suffix is a header file that contains declarations which will be used by the program, or it may represent a library interface.

---

## 8. What does the linker do for your program?

For example, in the Hello, World program, we use `iostream` and the statement `cout << "Hello, World\n";`.  
When we compile the program, the compiler produces separate results for our code and the library code.  
The purpose of the linker is to link the required libraries, such as `iostream`, with our program so that it can run correctly.

---

## 9. What is the difference between a source file and an object file?

A source file is where we write human-readable code.  
On the other hand, an object file contains machine code that will later be linked into the final program.

---

## 10. What is an IDE and what does it do for you?

IDE stands for Integrated Development Environment.  
It is a collection of tools used to develop programs, so developers do not need to switch between different programs or tools, because everything they need is already provided in one environment.

---

## 11. If you understand everything in the textbook, why is it necessary to practice?

Because programming is learned by practice, not just by reading theory.
