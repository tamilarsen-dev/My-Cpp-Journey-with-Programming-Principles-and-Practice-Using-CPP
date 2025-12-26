# 📘 Learning C++ from *Programming: Principles and Practice Using C++*
*(Combining the 2nd and 3rd Editions)*

Welcome to my C++ learning repository.  
The main goal is simple: build a solid programming foundation using formal references rather than relying only on scattered, informal YouTube tutorials.  
This repository follows the structure of the book **"Programming: Principles and Practice Using C++" (PPP)** by Bjarne Stroustrup.

---

## 🎯 Learning Objectives
- Build a fundamental understanding of programming and problem-solving.
- Study C++ syntax and concepts step by step and systematically.
- Fill the knowledge gap from previously informal learning sources.
- Prepare a stable foundation for deeper topics such as OOP, STL, and real-world project development.

---

## 📂 Repository Structure
<pre>
Programming-Principles-and-Practice-Using-CPP
|
|- main.cpp                        # Entry point, includes chapter headers
|
|- chapter02/
|   |- drills/
|   |    |- drills.h               # Function declarations
|   |    |- drill_01.cpp           # Example: drill implementation
|   |    |- drill_02.cpp
|   |    |- README.md              # Notes / explanations for this subfolder
|   |
|   |- exercises/
|   |    |- exercises.h
|   |    |- exercise_01.cpp
|   |    |- exercise_02.cpp
|   |    |- README.md
|   |
|   |- review_questions/
|   |    |- review_questions.h
|   |    |- review_01.cpp
|   |    |- README.md
|   |
|   |- try_this/
|        |- try_this.h
|        |- try_01.cpp
|        |- try_02.cpp
|        |- README.md
|
|- chapter03/                      # Same structure as chapter02
|- chapter04/
|- chapter05/
... and so on
</pre>

---

## 🧩 How the Structure Works
- Each **chapter** contains subfolders: `drills`, `exercises`, `review_questions`, and `try_this`.
- Each subfolder includes:
  - `.cpp` files for the implementations
  - A `.h` header for function declarations
  - A `README.md` for documentation and explanation
- The `main.cpp` only needs to include the headers, for example:

```cpp
#include "chapter02/drills/drills.h"
#include "chapter02/exercises/exercises.h"

int main() {
    // Call functions declared and defined in subfolders
    run_drills();
    run_exercises();
    return 0;
}
```
This creates a clean structure rather than mixing all code in a single file.

---

## 🧱 Concepts Covered
- Variables, data types, arithmetic & basic operations  
- Input/Output (I/O) and data handling  
- Conditions & loops (control flow)  
- Functions & modular program design  
- Basics of Object-Oriented Programming (OOP)  
- Introduction to `std::vector`, `std::string`, and modern C++ standards  

---

## 📖 Learning Resources
| Source | Description |
|--------|-------------|
| PPP 2nd Edition | Core reference |
| PPP 3rd Edition | Updated concepts & C++23 adjustments |
| LearnCpp.com | Complementary reference for modern practice |
| Personal Experiments | Reinforcement through testing & mistakes |

---

## 🌱 Personal Note
I’m not memorizing for the sake of memorizing.  
I’m building understanding that can actually be applied.  
Every mistake, every compile error, every commit is part of progress.

---

## 🤝 Contributions
Not open for contributions yet.  
However, discussions, corrections, and insights via Issues or Pull Requests are appreciated.

---

## 🚀 Status
Active learning in progress.
