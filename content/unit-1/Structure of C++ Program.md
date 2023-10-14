# Structure of a Typical C++ Program

## Section 1 $\to$ Header File Declaration
- Lists header files used.
- Provides prototypes for library functions.
- User-defined header files can be included.
## Section 2 $\to$ Global Declaration
- Declares global variables.
- Can include structure, class, and variable declarations.
## Section 3 $\to$ Class Declaration
- Declares classes and defines methods of the class.
## Section 4 $\to$ Main Function
- Entry point for all functions.
- Objects of classes are created here.
- OS calls the main function automatically.

## Example - Introduction to C++ Program

```cpp
#include<iostream>
using namespace std;

int main()
{
    cout << "Welcome to C++ Program";
    return 0;
}
```

**OUTPUT**
```
Welcome to C++ Program
```
