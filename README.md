# STUDY-OF-CONDITIONAL-LOOPS-IN-PYTHON-


#  EXPERIMENT NO: 6

# TITLE: Study of Conditional Statements in Python

**Name:** Amey Waghmare
**PRN:** 25070123009
**Batch:** A1
-

#  AIM

To study and implement various conditional statements in Python using `if`, `if-else`, and `if-elif-else` constructs for decision-making and logical problem solving.



#  THEORY 

Conditional statements are one of the most important concepts in programming. They allow a program to make decisions based on certain conditions. In Python, conditional statements evaluate a condition and execute a specific block of code depending on whether the condition is `True` or `False`.

In real-life situations, decision-making happens continuously. For example:

* If marks are greater than 40 → student passes.
* If a number is divisible by 2 → it is even.
* If income is above a certain limit → tax is applied.

Similarly, in programming, conditional statements help in controlling the flow of execution.



## 1️ The `if` Statement

The `if` statement executes a block of code only when the condition is true. If the condition is false, the block is skipped.

It is used when a single condition needs to be checked.

Example:

* Checking if a number is positive.
* Checking if a year is a leap year.

-

## 2️ The `if-else` Statement

The `if-else` statement is used when there are two possible outcomes.
If the condition is true, the `if` block executes.
If the condition is false, the `else` block executes.

Example:

* Checking if a number is even or odd.
* Checking pass or fail.



## 3️ The `if-elif-else` Ladder

When multiple conditions need to be checked, Python provides the `elif` (else-if) ladder.

Python checks conditions sequentially:

* If the first condition is true → it executes that block.
* If not, it checks the next `elif`.
* If none are true → `else` block executes.

Example:

* Checking positive, negative, or zero.
* Income tax slab calculation.
* Salary classification.



## 4️ Nested Conditional Statements

An `if` statement can be placed inside another `if` statement. This is called nested conditional statements.

Example:

* Date validation where:

  * First month is checked.
  * Then number of days is checked.
  * Then leap year condition is checked.



## 5️ Logical Operators in Conditional Statements

Logical operators combine multiple conditions:

* `and` → True if both conditions are True
* `or` → True if at least one condition is True
* `not` → Reverses the condition

Example:


if subject1 >= 40 and subject2 >= 40:


## 6️ Real-Life Applications in This Experiment

This experiment includes practical implementations such as:

* Number checking (positive/negative/zero)
* Odd-even detection using modulus operator
* Finding largest number
* Student result evaluation
* Date validation and increment
* Leap year detection
* Salary calculation using allowances
* Income tax calculation based on slabs

These programs demonstrate how conditional logic is used in real-world problem solving.

---

#  SYNTAX

## 1️ Simple if Statement

```python
if condition:
    statement



 2️ if-else Statement

```python
if condition:
    statement1
else:
    statement2

## 3️ if-elif-else Ladder

```python
if condition1:
    statement1
elif condition2:
    statement2
elif condition3:
    statement3
else:
    statement4


## 4️ Nested if Statement

```python
if condition1:
    if condition2:
        statement
    else:
        statement

## 5️Logical Operators

```python
if condition1 and condition2:
    statement

if condition1 or condition2:
    statement

if not condition:
    statement
```

---

#  CONCLUSION

Through this experiment, conditional statements in Python were successfully studied and implemented. Various practical programs were executed to understand decision-making structures. This experiment strengthened logical thinking and improved understanding of control flow in Python programming.



