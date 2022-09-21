# Expressions and operators
- Expression: valid unit of code that resolves to a value, there are expressions that have side effects, and those that purely evaluate
- All comple expressions are joined by operators

# Operators
- Javascript has both binary and unary operators, and one special ternary operator, the conditional operator
- Binary operator requires two operancd
- Unary operator requires single operand, either before or after the operator
- Assignment operator assigns a value to its left operand based on the value of its right operand
- [Operator Examples](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#unary_operators)
- If an expression evaluates to an object, then the left hand side of an assignment expression may make assignments to properties of that expression
- [Read working with objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)
- If an expression does not evaluate to an object, then assignments to properties of that expression do not assign
- Destructuring assignment syntax is a javascript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals
- Javascript discourage chaining or nesting assignments.
- Chained expressions without parentheses are grouped right to left, but they are evaluated left to right.
- all assignment operator other than = itself, the resulting values are always based on the operands' values before the operation

# Comparison oeprators
- A comparison operator compares its operands and returns a logical value based on whether the comparison is true
- Strings are compared based on standard lexicographical ordering, using Unicode values.
- If the two operands are not of the same type, Javascript attempts to convert them to an appropriate type for the comparison
- The sole exceptions to type conversion within comparisons involve the \=== and \!== operators, which perform strict equality and inequality comparisons
- [Comparison operator reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#comparison_operators)


# Loops
- Loop is a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another
- The statements for loops provided in Javascript: for, do while, while, labeled, break, continue, for in, for of
- for (initial expression; condition expressions; increment expressions){statement}
- do statement while (condition);
-  while (condition) statement
- label: statement ; provides a statement with an identifier that lets you refer to it elsewhere in your program
- break; break without a label termiinates the innermost enclosing loop, break with a label it terminates the specified labeled statement
- continue statement can be used to restart a while, do while , for, or label statement
- continue without a label terminates the current iteration of the innermost enclosing and continues execution of the loop with the next interation; continue with a label applies to the looping statement identified with the label
- for in statement iterates a specified variable over all the enumerable properties of an object
- It is better use a traditional for loop with a numeric index when iterating over arrays, because the for in statement iterates over user defined properties in addition to the array elements, if you modify the array object
- for of statement creates a loop iterating over iterable objects invoking a custom iteration hook with statements to be executed for the value of each distinct property; for (const i in arr)
- [Loops and iteration references](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)