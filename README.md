# Experiment-5-if_else-

1. if-else Statement in C++

The if-else statement is used to execute code based on a condition. If the condition is true, a block of code is executed; otherwise, another block runs.

Syntax:
if (condition) {
    // code to execute if condition is true
}
else {
    // code to execute if condition is false
}
To check multiple conditions, the if-else-if ladder is used.

Example:
int a = 10, b = 20;
if (a > b) {
    cout << "a is greater";
}
else {
    cout << "b is greater";
}
The if-else structure supports all data types and complex conditions such as comparisons and logical operations.

2. switch-case Statement in C++

The switch statement is used when you have multiple possible values for a variable and want to execute different code for each value. It is more readable than using many if-else statements when checking for equality.

Syntax:
switch (expression) {
    case value1:
        // code for value1
        break;
    case value2:
        // code for value2
        break;
    default:
        // code if no case matches
}
Example:
int choice = 2;
switch (choice) {
    case 1:
        cout << "Option 1 selected";
        break;
    case 2:
        cout << "Option 2 selected";
        break;
    default:
        cout << "Invalid choice";
}
The switch expression must be of type int, char, or enum. Each case must have a constant value. The break statement prevents fall-through to the next case.

Difference Between if-else and switch:

if-else works with any condition and data type; switch only checks for equality and uses integer-compatible expressions.

switch is better for fixed options; if-else is better for ranges or complex logic.

if-else is more flexible; switch is more structured and readable for menu-type logic.

