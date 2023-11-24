# 100 Days Of Code -  Progress Log

### This is a round 1 of my 100DaysOfCode challenge.


## Day 0: October 29, 2023 


**Today's Progress**:  Test-Driven Development, Python(The Docstring Module)

**Thoughts:**

- I started implementing the use of the `doctest module` to test my codes and I also discovered the `"unittest"`.
- There are a lot of flag options you can add to make the testing easier.
- I always write notes with sample codes as to help new learners and the future me as a reference.
- The link to the sample codes is down below
- Like usual, starting to learn something new is a bit challenging but with the right mindset, you can figure it out!
- Keep on coding ! 

**Link to work:** [TDD notes](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/13-TDD)



## Day 1: October 30, 2023 


**Today's Progress**: Data Encapsulation, Python 

**Thoughts:**

- When we talk about Data encapsulation, it is the bundling or wrapping of data(attributes) and methods into a single unit
- We can do this for medernization
- But most importantly, it is to ensure that the data is well handled
- This is an implementation of data abstraction
- I love this idea of handling data as python has no strict rules but trusts that programmers will adhere to it
- But it also makes me think that python wouldn't be the best for data encapsualtion

**Link to work:** [Data Encapsulation notes](https://github.com/hunterxcobby/Python-Projects/blob/main/lessons/exercises/12-OOP/9-encapsulation_demo.py)


## Day 2: October 31, 2023 


**Today's Progress**: A Simple Calculator that performs basic operations, C language

**Thoughts:**

- This is a step to get back to all my unfinished projects and it starts today
- I decided to visit all my old projects and finish them one after the other once at a time
- The project I am working on now is a simple calculator that performs the 4 basic operations
- I am having some few issues with the implementation of the mixed operations that involves me using a nested switch case statements 
- I intend to accomplish this by using a different function and later calling back for it
- I also made use of variadic functions 

**Link to project:** [Simple Calculator](https://github.com/hunterxcobby/C-Projects/tree/master/00-simple_calculator)


## Day 3: November 1, 2023 


**Today's Progress**: HackerRank Hello World challenge, C language

**Thoughts:**

- A friend introduced me to hackerrank and it is a platform for challenges
- I decided to start with some challenges in C language since it is the one I am
- most convenient with
- The challenge for today was an easy one that involved printing a string to display
- This is a basic implementation of the standard output function `printf` in C

**Link to work:** [Hello World](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x01-Hello_World)


## Day 4: November 2, 2023 


**Today's Progress**: Playing with Characters Challenge, C language

**Thoughts:**

- I solved a challenge today called playing with characters
- It invloves taking a character, a string an line of sentence as an input
- Then you print it to the standard output
- This involves the use of the `printf` and `scanf` function
- The scanf function would normally take input until it encounters a space
- The challenge today was about how to counter such problem
- It invloves the use of the scanset format specifiers in this form;

```C
  char s[MAX_LEN];
scanf("\n"); // Consume the newline character left in the buffer
scanf("%[^\n]%*c", s); // Use this to solve the problem
```
   - Explanation:
     - `%[^\n]` is a scanset format specifier. It tells `scanf` to read characters until it encounters a newline (`\n`).
     - `%*c` is used to read and discard the newline character.
   - Note: The `%*c` is needed to consume the newline character left in the input buffer after the previous `scanf`. If you omit it, the next `scanf` will not work correctly.

**Link to solution:** [Playing with characters](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x02-PLaying_with_characters)


## Day 5: November 3, 2023 


**Today's Progress**:  Hash Tables, C language

**Thoughts:**

- So from what I learnt today,
- There are basically two types of hashing
- The Open Hashing (closed addressing)
- The Closed Hashing (opened hashing)
- `Collosion` is when two different inputs (or keys) produce the same hash value .
- I learned we can use four techniques to solve collisions
- The separate chaining method
- Linear probing
- Quadratic probing
- Double hashing
- Hashing has a complexity of O(1)
- Which makes it faster
- Check the file below to see how to implement it

**Link to work:** [Hashing](https://github.com/hunterxcobby/C-Projects/tree/master/lessons/solutions/0x05-Hash-tables/introduction)


## Day 6: November 4, 2023 


**Today's Progress**:  The max challenge, C language

**Thoughts:**

- I solved a challenge today called max functions
- It has to do with taking four values as arguments to a function
- Comparing them after the other
- And returning the greatest of them
- My first intuiton was to use logical operators but apparently it was not logical enough ;)
- Check out the work to see how i handled it

**Link to solution:** [Max Challenge](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x04-functions_callenge)


## Day 7: November 5, 2023 


**Today's Progress**:  Pointers challenge, C language

**Thoughts:**

 - In simple terms,
 - A pointer is like a label that points to a location where some data is stored.
 - Pointers are very useful for tasks where you need to work with memory efficiently.
 - Use pointers when;
   - You need to allocate memory for data at runtime
   - When you want to modify a variable in a function and have that change reflected outside the function, you pass the variable's address (a pointer) instead of the value itself.
   - Implementing data structures like linked lists, trees, and graphs relies heavily on pointers for creating and navigating nodes.
- while pointers are powerful, they require careful handling to avoid issues like memory leaks and pointer arithmetic errors.
- Checkout the file below

**Link to work:** [Pointers](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x05-Pointers_challenge)  


## Day 8: November 6, 2023 


**Today's Progress**:  Inheritance, Python(Multiple Inheritance, Magic Methods)

**Thoughts:**

- I delved into the concept of inheritance in Python and explored the use of the `super()` function to leverage base class methods in subclasses effectively.
- There are several ways to implement inheritance, including single and multiple inheritance.
- I made sure to document my learning process with examples to serve as a valuable resource for both newcomers and my future self.
- For reference, you can find the sample codes in the link below.
- Embracing new concepts in programming can be a bit daunting initially, but with persistence and the right approach, it becomes much clearer.

**Link to notes:** [Inheritance](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/13-TDD)


## Day 9: November 7, 2023 


**Today's Progress**:  File Handling - Operating on a file, using JSON to work on a file

**Thoughts:**: 

- File handling in Python allows us to work with files on our computer's storage.
- We can perform various operations like reading, writing, and manipulating data within files.
- It's an essential aspect of programming to manage and process information stored in files.
- Python provides simple and effective ways to interact with files, making it a versatile tool for handling data.
- While Python excels in file handling, it's important to follow best practices to ensure data integrity and security.

**Link to notes:** [File Handling](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/15-file_handling)


## Day 10: November 8, 2023 


**Today's Progress**:  Conditonals and Loops(if and else), C language

**Thoughts:**: 

- Worked on the challenge involving conditional statements `if` and `else` in C.
- Gained a deeper understanding of how to use `if`, `else if`, and `else` to make decisions in a program.
- Practiced writing code to handle different scenarios based on specific conditions.
- Conditional statements are a fundamental part of programming and are crucial for controlling the flow of a program.
- It's important to consider all possible cases and plan the code accordingly to ensure the desired outcome.
- Taking the time to understand conditional statements in C will be valuable for more complex projects in the future.

**Link to work:** [Conditionals and loops](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x06-Conditionals_and_loops)


## Day 11: November 9, 2023 


**Today's Progress**:  **Python:** Positional and Keyword arguments, arbitrary arguments

**Thoughts:**: 

- Positional arguments are values passed to a function in the order that the function expects them.
- They are matched to the parameters of the function based on their position.
- The first argument is matched to the first parameter, the second argument to the second parameter, and so on.
- Keyword arguments are values passed to a function with an explicit keyword specifying which parameter they should be matched with.
- They are specified in the form parameter=value.
- Unlike positional arguments, they can be provided in any order, as long as their keyword matches a parameter name of the function.

 **Link to notes:** [Positonal and keyword arguments](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/16-args_n_kwargs) 



## Day 12: November 10, 2023 


**Today's Progress**:  Conditonals and Loops(for loops), C language

**Thoughts:**: 
- Employed for loops in tackling a challenge centered around conditional statements in C.
- Developed a nuanced understanding of utilizing for loops for efficient iteration through code segments.
- Engaged in the practical application of for loops to handle diverse scenarios and decision-making within the program.
- Recognized the inherent versatility of for loops in streamlining code execution and managing program flow.
- Check out my notes to see how i tackled this challenge.

**Link to work:** [Condtionals and loops](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x07-Conditionals_and_loops)


## Day 13: November 11, 2023 


**Today's Progress**:  Conditonals and Loops- Sum of Digits of a Five Digit Number , C language

**Thoughts:**: 
- The challenge involves using the modulo operator (%) to get the remainder of the division by 10
-  which gives the last digit of the number.
- It then updates the number by performing integer division by 10 to remove the last digit.
- This process is repeated to get each digit of the number.
- The sum of the digits is calculated and printed.

**Link to work:** [Condtionals and loops](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x08-Conditionals_and_loops)


## Day 14: November 12, 2023


**Today's Progress**:  Conditonals and Loops- Sum of Digits of a Five Digit Number , C language

**Thoughts:**
- The **"Length of the Last Word"** problem involves finding the length of the last word in a given string.
- This problem is commonly used as an introductory exercise in algorithmic problem-solving and is often encountered in coding interviews.

**Link to work:** [Length of last word](https://github.com/hunterxcobby/C-Solutions/tree/main/0-leetcode/0x04-len_of_lastword)


## Day 15: November 13, 2023


**Today's Progress**: Logical Bitwise Operators, C language  

**Thoughts:**
- This challenge involving bitwise operators provides a practical application for understanding their usage
- Working with bitwise AND, OR, and XOR operations within a specific context, such as finding maximum values
based on certain conditions, helps reinforce the understanding of these operators.
- They are commonly used in tasks like data manipulation, protocol implementations, 
and efficient memory management.
- when dealing with flags, masks, and compact data representations
- mastering bitwise operators enhances a programmer's toolkit, enabling more efficient and concise solutions to specific problems

**Link to work:** [will be updated soon]


## Day 16: November 14, 2023

**Today's Progress**: Printing Pattern Using loops, C language 

**Thoughts:**
- This pattern challenge involves creating a matrix with a specific numerical pattern based on the input value n. 
- we need to calculate the distance of each cell from the nearest border (top, bottom, left, or right).
- The challenge requires careful consideration of the pattern and how it changes based on the input. 
- It's a good exercise to practice nested loops and conditional statements in programming
- Use this distance to determine the value to be printed.
- It's a good exercise to practice nested loops and conditional statements in programming


**Link to work:** [Printing patterns](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x09-Printing_pattern_loops)



## Day 17: November 15, 2023

**Today's Progress**: Arrays and Strings,Dynamic Array Sum Challenge C language 

**Thoughts:**
- The challenge highlights the use of malloc to dynamically allocate memory for an array.
-  It involves reading values into an array, iterating through the array, and calculating the sum of its elements.
-  The algorithm for calculating the sum is straightforward, focusing more on the usage of dynamic arrays rather than complex computations.
-  this challenge is suitable for learners who want to solidify their understanding of dynamic memory allocation and array manipulation in C


**Link to work:** [Dynamic Array Sum](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/1D-Array)



## Day 18: November 16, 2023

**Today's Progress**: Loops,Squares of non-negative numbers challenge, Python

**Thoughts:**
- This challenge is straightforward and involves printing the squares of non-negative integers less than a given number `n`. 
- The task primarily focuses on basic input/output operations and looping through numbers up to `n`.
- It's a good exercise for practicing these fundamental concepts in programming.
- The challenge can be easily solved using a loop to iterate through the range of non-negative integers and printing the square of each

**Link to solution:** [Squares of non-negative integers](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/0-Loops)


## Day 19: November 17, 2023

**Today's Progress**: Functions, Leap Year Checker challenge, Python

**Thoughts:**
- The Leap Year challenge is a classic programming task that involves implementing a function to determine whether a given year is a leap year or not.
-  It's a fundamental problem that tests your understanding of basic conditions and logical operations.
-  It requires applying the given conditions for leap years and implementing them in a simple function
-   The challenge is beginner-friendly and helps reinforce fundamental concepts such as conditionals and mathematical operations.
-  it's a straightforward yet essential task for building a strong foundation in programming.

**Link to solution:** [Leap Year Checker](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/01-Leap_year_checker)


## Day 20: November 18, 2023

**Today's Progress**: IF-ELSE, Leap Year Checker challenge, Python

**Thoughts:**
- The "Number Classification" challenge is a straightforward problem that tests your understanding of conditional statements.
-  It requires you to classify a given number based on specific conditions.
-  The task provides an opportunity to practice implementing conditional logic in a programming language.
-   The conditions cover various cases, such as odd numbers and specific ranges of even numbers.
-   This challenge is suitable for beginners as it involves basic control flow concepts.

**Link to solution:** [Number Classification Challenge](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/02-If-Else)


## Day 21: November 19, 2023

**Today's Progress**: Sorting Algorithm, The Bubble Sort, C language

**Thoughts:**
- A sorting algorithm is a set of instructions or rules designed to arrange a collection of items in a specific order.
- The primary purpose of sorting algorithms is to organize data in a way that makes it easier to search, retrieve, and analyze.
- Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
- The pass through the list is repeated until the list is sorted.
-**Bubble Sort:**
   - **Algorithmic Paradigm:** Iterative.
   - **Time Complexity:** O(n^2) in the worst and average case.
   - **Space Complexity:** O(1) as it doesn't require additional space.
   - **Key Features:** Simple to implement, good for small datasets or nearly sorted data.

 **Link to notes**: [Bubble Sort](https://github.com/hunterxcobby/C-Projects/tree/master/lessons/solutions/0x06-Sorting_algorithm/01-bubble_sort)



## Day 22: November 20, 2023

**Today's Progress**: Sorting Algorithm, The Insertion, Quick and Merge Sort, C language

1.  Insertion Sort is a straightforward sorting algorithm that builds the final sorted array one item at a time.
- **Insertion Sort:**
  - **Algorithmic Paradigm:** Iterative.
  - **Time Complexity:** O(n^2) in the worst and average case.
  - **Space Complexity:** O(1) as it doesn't require additional space.
  - **Key Features:** Simple to implement, adaptive, stable, and efficient for small datasets or nearly sorted data.

2. Quick Sort:is a highly efficient sorting algorithm that follows the divide-and-conquer paradigm. It works by selecting a 'pivot' element from the array and partitioning the other elements into two sub-arrays according to whether they are less than or greater than the pivot.
- **Algorithmic Paradigm:** Divide and Conquer.
- **Time Complexity:**
  - Worst Case: O(n^2) - Occurs when the partitioning is consistently unbalanced.
  - Average Case: O(n log n) - Efficient for a wide range of inputs.
  - Best Case: O(n log n) - Occurs when the pivot divides the array into roughly equal halves.
  - Space Complexity: O(log n) - Recursive calls in the call stack.
- **Key Features:**
  - Efficient for large datasets.
  - In-place sorting - Doesn't require additional memory.
  - Unstable - Equal elements might not maintain their original order.
  - Adaptive - Performance can be improved with optimizations like choosing the median of     
  three elements as the pivot.

3. **Merge Sort:**
- **Algorithmic Paradigm:** Divide and Conquer.
-  **Time Complexity:** O(n log n) in the worst, average, and best cases. Merge Sort consistently maintains this efficiency across different scenarios.
- **Space Complexity:** O(n) additional space is required for the temporary storage during the merging process, making it less memory-efficient than Insertion Sort for large datasets.
- **Key Features:**
   - **Stability:** Merge Sort is a stable sorting algorithm, meaning that equal elements maintain their relative order in the sorted output.
   - **Efficiency:** It performs well on large datasets due to its consistent O(n log n) time complexity.
   - **Divide and Conquer:** The algorithm breaks the problem into smaller sub-problems, solving them independently, and then combines the solutions to solve the original problem.
   - **Adaptability:** Merge Sort's performance is not significantly affected by the initial order of the elements, making it suitable for a wide range of input scenarios.


**Link to notes**: [Insertion Sort, Quick Sort, Merge Sort](https://github.com/hunterxcobby/C-Projects/tree/master/lessons/solutions/0x06-Sorting_algorithm)


## Day 23: November 21, 2023

**Today's Progress**: Big O Notation, C language

**Thoughts:**
- Big O notation is a mathematical notation that describes the performance or complexity of an algorithm.
- It provides an upper bound on the growth rate of the algorithm's time or space requirements as the input size increases.
- Understanding Big O notation is crucial for evaluating and comparing the efficiency of algorithms.
- Common complexities include O(1) for constant time, O(log n) for logarithmic time, O(n) for linear time, O(n^2) for quadratic time, and so on.
- Efficient algorithms aim for lower Big O complexities to handle larger datasets more effectively.

**Link to notes**: [Big O Notation](https://github.com/hunterxcobby/C-Projects/tree/master/lessons/solutions/0x06-Big-O_notation)

## Day 24: November 22, 2023

**Today's Progress**: The Print Function on HackerRank, C language

**Thoughts:**
The Print Function
- method signature is below:

- print(*values, sep=' ', end='\n', file=sys.stdout)
- print(value1, value2, value3, sep=' ', end='\n', file=sys.stdout)
- Here, values is an array and *values means array is unpacked, you can add values separated by a comma too.
- The arguments sep, end, and file are optional, but they can prove helpful in formatting output without taking help from a string module.

- The argument definitions are below:
- sep defines the delimiter between the values.
- end defines what to print after the values.
- file defines the output stream.

**Link to solution**: [print function](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/03-print_function)


## Day 25: November 23, 2023

**Today's Progress**: loops and conditions, shell scripting

**Thoughts:**
- The for loop in shell scripting allows you to perform a set of commands for each value in a specified list.
- Here's a breakdown using a simple example:

```bash
# Example: Printing numbers from 1 to 5 using a for loop
for i in 1 2 3 4 5; do
  echo "Number: $i"
done
```
- **Arithmetic Operators:**

1. **`+`, `-`, `*`, `/` Operators:**
   - Purpose: Used for basic arithmetic operations.
   - Example:
     ```bash
     let "result = 5 + 3"
     ```

2. **`**` Operator (Exponentiation):**
   - Purpose: Raises a number to the power of another.
   - Example:
     ```bash
     let "z = 5**3"  # 5 * 5 * 5
     ```

3. **`%` Operator (Modulo):**
   - Purpose: Returns the remainder of an integer division operation.
   - Example:
     ```bash
     expr 5 % 3  # Returns 2 (remainder of 5/3)
     ```
   - Modulo finds use in generating numbers within a specific range, formatting program output, and even generating prime numbers.


**Link to notes**: [Loops_condtitions_parsing](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x04-loops_conditions_and_parsing)


## Day 26: November 24, 2023

**Today's Progress**: file test operators, shell scripting


**Link to notes**: [file test operators](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x04-loops_conditions_and_parsing/file_test_operators)
