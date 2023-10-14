# Object Oriented Programming (OOP)

Object-Oriented Programming (OOP) is a programming **paradigm** based on the concept of "**objects**". This contrasts with procedural programming, where data and procedures are separate concepts.

Here are the core concepts and principles associated with OOP:

1. **Objects** 
2. **Classes** 
3. **Inheritance** 
4. **Polymorphism** 
5. **Encapsulation** 
6. **Abstraction** 
7. **Association**\* $\to$ It's a relationship where all objects have their own lifecycle and there's no owner.
8. **Aggregation**\* $\to$ Represents a "whole-part" relationship where the part can exist independently of the whole.
9. **Composition**\* $\to$ Also a "whole-part" relationship, but the part cannot exist independently of the whole.

| **Procedure Oriented Programming (POP)** | **Object Oriented Programming (OOP)**                               |
|------------------------------------------|---------------------------------------------------------------------|
| Follows Top Down Approach                | Follows Bottom Up Approach                                          |
| It is less secure                        | It is highly secure                                                 |
| It deals with Algorithms                 | It deals with data                                                  |
| Takes very less memory                   | Typically uses more memory due to overheads                         |
| No access specifier                      | Has access specifiers like private, public, protected               |
| Main focus on function and not on data security | Main focus is on objects and their security                       |
| No real world relation, more abstract    | Real-world entities can be modeled as objects                       |
| Difficult to manage when project size grows | Easier to manage with modularity and reusability in mind          |
| Does not support graphical programming   | Supports graphical programming and visual development                |
| Examples: C, FORTRAN                     | Examples: C++, Java, Python (OOP features)                          |

---
# Features of OOPs in C++

## 1. Object
- An entity with state and behavior.
- Active entity.
- Instance of a class.
- No memory allocated with class definition; memory allocated upon object creation.
- **Example**: Fruit is a class; Apple, orange, banana are objects of the class fruit.

## 2. Class
- Collection of objects, passive entity.
- User-defined data type with data members and member functions.
- **Example**: 
  ```cpp
  class Box
  {
      private:
          // data members like int, float, char...
      public: 
          // member functions like void area();
  } b1, b2, b3;
  ```
  Where `b1`, `b2`, `b3` are objects of the class `Box`.

## 3. Inheritance
- A class accesses properties (data members and member functions) of another class.
- **Example**: `Class A` (Super class/Base class/Parent Class) and `Class B` (Sub class/Derived class/Child Class).

## 4. Polymorphism
- A single task performed in multiple ways.
- **Example**: A person with roles like father, husband, and employee.
  - **Compile-time Polymorphism**: 
    - Function overloading 
    - Operator Overloading
  - **Run-time Polymorphism**: 
    - Virtual function

## 5. Abstraction
- Hide internal details while showing functionality.
- **Example**: Phone call process.

## 6. Encapsulation
- Binding or wrapping code and data together.
- **Example**: Capsule wrapped with different medicines.

## 7. Dynamic Binding
- Code execution in response to a function call is decided at run time.
- C++ uses the virtual function to support this.

## 8. Message Passing
- Objects communicate by sending and receiving information.

# Other Features of C++
## Tokens
- **Keywords**
- **Identifiers**
- **Comments**
- **Operators**
- **Statements**

## Keywords
- Each has a predefined purpose.
- Cannot use as *variable* and *constant* names
- Keywords covered in this class include: `bool, break, case, char, const` and so on.

## Identifiers
- It is name for *variables*, *constants*, *functions*, etc.
- Consist of a letter followed by a sequence of letters, digits, underscores.
- Case-sensitive.
- **Examples**: `First_name, age, y2000, y2k`
- **Invalid examples**: `2000y, X=Y, J-20, ~Ricky, *Michael`

## Comments
- Explanatory notes, ignored by compiler.
- Two ways: 
  - Single line: `// Comment`
  - Multi-line: `/* Comment */`

## Compiler Directives
- The `#include` directive tells the compiler to include certain C++ code.
- **Examples**: `#include <iostream>` (pre-defined) and `#include "my_lib.h"` (user-defined).

## Programming Style:
- Free-format language.
- Extra blanks, tabs, blank lines, and comments are ignored.
- Indenting and statement arrangements are flexible.

