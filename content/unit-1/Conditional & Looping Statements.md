# Conditional Statements

## Simple if() Statement
**Definition** $\to$ Executes a block of code if a specified condition is true.

**Syntax**
```cpp
if (condition) {
    // code to be executed if condition is true
}
```

**Example**
```cpp
if (a > b) {
    cout << "a is greater than b";
}
```

## If()-else Statement
**Definition** $\to$ Executes one block of code if a condition is true and another block if it's false.

**Syntax**
```cpp
if (condition) {
    // code to be executed if condition is true
} else {
    // code to be executed if condition is false
}
```

**Example**
```cpp
if (a > b) {
    cout << "a is greater than b";
} else {
    cout << "b is greater than or equal to a";
}
```

## Nested if() Statement
**Definition** $\to$ An if statement inside another if statement to test multiple conditions.

**Syntax**
```cpp
if (condition1) {
    // code to be executed if condition1 is true
    if (condition2) {
        // code to be executed if condition2 is also true
    }
}
```

**Example**
```cpp
if (a > b) {
    if (a > c) {
        cout << "a is the greatest";
    }
}
```

## Switch() Statement
**Definition** $\to$ Selects one of many code blocks to be executed based on a variable's value.

**Syntax**
```cpp
switch(expression) {
    case constant1:
        // code block
        break;
    case constant2:
        // code block
        break;
    // ...
    default:
        // code block
}
```

**Example**
```cpp
switch (day) {
    case 1:
        cout << "Monday";
        break;
    case 2:
        cout << "Tuesday";
        break;
    default:
        cout << "Other day";
}
```

---
# Looping Statements (Iterative Statements)

## While
**Definition** $\to$ Executes a block of code as long as a specified condition is true.

**Syntax**
```cpp
while (condition) {
    // code to be executed
}
```

**Example**
```cpp
int i = 1;
while (i <= 5) {
    cout << i << " ";
    i++;
}
```

## do-while
**Definition** $\to$ Similar to `while` but tests the condition at the end, ensuring the code block is executed at least once.

**Syntax**
```cpp
do {
    // code to be executed
} while (condition);
```

**Example**
```cpp
int i = 1;
do {
    cout << i << " ";
    i++;
} while (i <= 5);
```

## for
**Definition** $\to$ Executes a block of code multiple times with an initial condition, a test condition, and an increment operation.

**Syntax**
```cpp
for (initialization; condition; increment/decrement) {
    // code to be executed
}
```

**Example**
```cpp
for (int i = 1; i <= 5; i++) {
    cout << i << " ";
}
```
