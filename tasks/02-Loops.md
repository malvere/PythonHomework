
---

# Lesson 2: Loops and Iterators

## Introduction:

Loops are essential for executing a block of code repeatedly. In Python, there are two main types of loops: `for` and `while`. Additionally, iterators are objects that can be iterated (looped) one element at a time.

## Objective:

By the end of this lesson, you should be able to:

1. Understand the concept of loops and their necessity in programming.
2. Differentiate between `for` and `while` loops.
3. Utilize iterators to traverse sequences.

## Topics Covered:

1. **`for` Loops:**
    - Syntax and basic usage.
    - Iterating over sequences (lists, tuples, strings).

2. **`while` Loops:**
    - Syntax and basic usage.
    - Conditional loop execution.

3. **Iterators:**
    - Concept of iterators.
    - Using built-in functions like `range` and `enumerate`.

## Lesson Content:

### 1. `for` Loops:

#### Syntax:
```python
# Basic syntax
for variable in sequence:
    # Code block to be repeated
```

#### Example:
```python
# Iterating over a list
fruits = ['apple', 'banana', 'orange']
for fruit in fruits:
    print(fruit)
```

### 2. `while` Loops:

#### Syntax:
```python
# Basic syntax
while condition:
    # Code block to be repeated
```

#### Example:
```python
# Using a while loop to count from 1 to 5
count = 1
while count <= 5:
    print(count)
    count += 1
```

### 3. Iterators:

#### `range` Function:
```python
# Using range to iterate over a sequence of numbers
for number in range(1, 6):
    print(number)

# Iterating with a `step`
for number in range(1, 6, 2):
    print(number)
```

#### `enumerate` Function:
```python
# Using enumerate to iterate over a sequence with index
fruits = ['apple', 'banana', 'orange']
for index, fruit in enumerate(fruits):
    print(f"Index {index}: {fruit}")
```

## Exercises:

1. Write a `for` loop to calculate the sum of numbers in a given list.
2. Use a `while` loop to find the factorial of a number.
3. Iterate over a string and print each character.
4. Create a program using `range` to print even numbers from 2 to 10.
5. Explore `enumerate` to print the index and value of each element in a list.

## Conclusion:

Loops and iterators are powerful tools in programming, allowing you to automate repetitive tasks.

---