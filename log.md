# 100 Days Of Code -  Progress Log

### This is a round 1 of my 100DaysOfCode challenge.


## Day 0: October 29, 2023 


**Today's Progress**:  Test-Driven Development, Python(The Docstring Module)

**Thoughts:**

- I started implementing the use of the `doctest module` to test my codes and I also discovered the `"unittest"`.
- There are a lot of flag options you can add to make the testing easier.
- I always write notes with sample codes as to help new learners and the future me as a reference.
- The link to the sample codes is down below
- Like usual, starting to learn something new is a bit challenging but with the right mindset, you we figure it out!

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

- A friend learned me to hackerrank and it is a platform for challenges
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

- I delved into the concept of inheritance in Python and learned the use of the `super()` function to leverage base class methods in subclasses effectively.
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

-**File Test Operators**

- File test operators in Bash are used to check various attributes and properties of files.
- They are commonly used in conditional statements to make decisions based on the existence, type, or properties of files.

- `-e file`: Returns true if the file exists.

  Example: `if [ -e "myfile.txt" ]; then echo "File exists"; fi`

- `-f file`: Returns true if the file is a regular file (not a directory or device file).

  Example: `if [ -f "document.pdf" ]; then echo "It's a regular file"; fi`

- `-d file`: Returns true if the file is a directory.

  Example: `if [ -d "myfolder" ]; then echo "It's a directory"; fi`

- `-s file`: Returns true if the file is not zero size.

  Example: `if [ -s "nonemptyfile.txt" ]; then echo "File is not empty"; fi`

- `-r file`: Returns true if the file has read permission.

  Example: `if [ -r "readablefile.txt" ]; then echo "File is readable"; fi`

- `-w file`: Returns true if the file has write permission.

  Example: `if [ -w "writablefile.txt" ]; then echo "File is writable"; fi`

- `-x file`: Returns true if the file has execute permission.

  Example: `if [ -x "executablescript.sh" ]; then echo "Script is executable"; fi`
These operators provide a powerful way to perform file-related checks in Bash scripts, enabling you to make decisions and take actions based on the properties of files.

**Link to notes**: [file test operators](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x04-loops_conditions_and_parsing/file_test_operators)


## Day 27: November 25, 2023

**Today's Progress**: Subset Check Challenge, Functions in Python, HackerRank

- **Subset Check Challenge:**

- This challenge involves determining whether one set is a subset of another. 
- The goal is to compare two sets, A and B, and check if all elements of set A are present in set B.
- The solution employs Python, utilizing set operations and a concise function to check the subset relationship.
- The implementation iterates through the given test cases, reads the sets,
- and outputs "True" or "False" based on the subset condition.

**Link to solution**: [Subset Check](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/04-Check_subset)



## Day 28: November 26, 2023

**Today's Progress**: Processes and Signals

- **Process:** A process is described as an instance of a program in execution. In simpler terms, if a program is executed multiple times, each execution is considered a separate process.

- **Multiple Instances:** If the same program is run multiple times, each execution creates a distinct process. For example, if a program is run 10 times simultaneously, there will be 10 corresponding processes.

- **Unique Process ID (PID):** Each process is identified by a unique Process ID (PID). The PID serves as a numerical identifier that distinguishes one process from another in the system.

- **Parent Process ID:** Additionally, each process is associated with the Process ID of its parent process. Understanding the parent-child relationship between processes is crucial for managing and organizing the execution flow.


**Link to notes**: [Processes and Signals](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x05-Processes_and_signals)


## Day 29: November 27, 2023

**Today's Progress**: Building a command line PhoneBook

**Project Log:**
**1. Building a Phonebook Interface:**

- Created a Python script (`interface.py`) to build a command-line phonebook interface.
- Used the `curses` library to create a simple interactive menu with options to start the phonebook or quit.
- Implemented functions to print menu items, author information, and contacts model details.
- Set up a basic structure for running a C program in a new tmux window.

**2. Improving the Interface:**

- Adjusted the layout of menu items and author information.
- Changed the background and text color of the interface.
- Implemented a loading effect using a separate utility module (`utility.py`).
- Separated the "Loading..." message from the "Please wait" message in the loading animation.

**3. Additional Improvements:**

- learned ways to enhance the phonebook interface, such as adjusting text size and formatting.
- Addressed issues with the loading animation and clarified the separation of messages.

**Next Steps:**

- Planning to integrate the C program execution into the interface.
- Considering additional features or improvements for the phonebook interface.

**Link to project**: [Phonebook CLI Project](https://github.com/hunterxcobby/phonebook)


## Day 30: November 28, 2023

**Today's Progress**: Building a command line PhoneBook

**Project Log:**

- **Interface Design:** I worked on designing an interactive interface for the phone book application using the curses library in Python. This involved creating a main menu and options for the phone book, with the ability to navigate using arrow keys.

- **Dynamic Menu Highlighting:** I implemented dynamic highlighting for the selected option in the phone book menu, making it more interactive.

- **Option Selection:** I set up the functionality to perform actions based on the selected option, such as adding, saving, editing, and deleting contacts.

- **Interface Customization:** I made adjustments to the interface, including changing the background color, adjusting text formatting, and adding information at specific locations.

- **Introduction of Control Pad:** I learned the use of control pad navigation for a more user-friendly experience in the phone book options.

**Link to project**: [Phonebook CLI Project](https://github.com/hunterxcobby/phonebook)


## Day 31: November 29, 2023

**Today's Progress**: Array Reversal Challenge

**Thoughts:**
- Solved a challenge to reverse an array in C.

- Implemented the logic to take user input for the array size and elements.

- Used dynamic memory allocation (`malloc`) to create an array based on user input.

- Implemented a loop to reverse the array elements using a temporary variable for swapping.

- Printed the reversed array.

- Freed the allocated memory using `free()` to prevent memory leaks.

- Tested the program with different input arrays to ensure correct reversal.

- Concluded the project and provided a corrected version of the code.

**Link to solution**: [Array Reversal](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x09-Array_reversal)


## Day 32: November 30, 2023

**Today's Progress**: Print Token Challenge

**Thoughts:**

- **Understanding the Task:**
   - The goal is to take a sentence as input and print each word on a new line.
   - The sentence can include spaces and various characters.

- **Input Handling:**
   - Read the input sentence. This can be done using standard input functions in C, such as `scanf` or `fgets`.

- **Tokenization:**
   - Break down the sentence into individual words. In C, you can achieve this by iterating through the characters of the sentence and identifying spaces as word separators.
   - Keep track of the start and end indices of each word.
 
**Link to solution**: [Print Token](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x10-Print_Tokens)


## Day 33: December 1, 2023

**Today's Progress**: The Digit Frequency Challenge

**Thoughts:**
- **String Iteration:** To solve this challenge, you need to iterate through each character in the given string.

- **Digit Identification:** For each character, check if it is a digit. You can use the ASCII values to identify digits ('0' to '9').

- **Frequency Counting:** Maintain an array or some data structure to store and update the frequency count of each digit as you iterate through the string.

- **Output:** Print the frequency count of each digit in a specific format.

**Link to solution**: [Digit Frequency](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x11-Digit_Frequency)


## Day 34: December 2, 2023

**Today's Progress**: The List Comprehension Challenge, Python

- This challenge is a good opportunity to practice using list comprehensions in Python.
-  List comprehensions provide a concise and readable way to generate lists, making the code more expressive.

- In this specific challenge, the task involves creating a 3D grid of coordinates and filtering out the ones that meet a certain condition.
- Using list comprehensions here demonstrates the power of this feature in creating compact and efficient code for generating lists based on specific criteria.

- The challenge also encourages understanding of how to use list comprehensions for nested loops
-  making it a valuable exercise for improving Python programming skills, especially in terms of readability and brevity.

**Link to solution**: [List Comprehension](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/05-List_Comprehensions)


## Day 35: December 3, 2023

**Today's Progress**: Runner-Up Score Finder, Python

**Thoughts:**
- **Understanding the Problem:**  the task is relatively straightforward: find the second-highest score in a list.

- **Input Handling:** The program reads an integer `n` representing the number of scores and a list of integers as input. This is a good opportunity to practice handling input in Python.

- **Finding Unique Scores:** Converting the list to a set to find unique scores is a good approach. However, it's essential to handle cases where there might be fewer than two distinct scores.

- **Edge Cases:** The code should handle edge cases gracefully. For example, if there's only one unique score, there's no runner-up. The provided solution includes a check for this scenario.

**Link to solution**: [Runner-Up Score Finder](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/06-RunnerUP_Score)



## Day 36: December 4, 2023

**Today's Progress**: The UUID and Datetime module, Python

- The uuid module in Python is used for generating universally unique identifiers 
- It is often referred to as UUIDs.
- UUIDs are 128-bit numbers that are unique across both space and time.
- They are commonly used in various applications and systems to uniquely identify entities.
  - uuid1(): This method generates a UUID based on the current timestamp and the machine's hardware address.
  - It may compromise uniqueness if multiple UUIDs are generated within the same 100-nanosecond interval.
  - uuid4(): This method generates a UUID based on random numbers.
  - While not guaranteed to be unique, the probability of collision is extremely low.

**link to notes:**  [UUID Module](https://github.com/hunterxcobby/Python-Projects/tree/main/my_projects/airbnb_console_test/notes/uuid.md)   


- The datetime module in Python provides classes for working with dates and times. 
- It's particularly useful for handling various time-related operations.
- Here's a brief overview of how you can use the datetime module:

**link to notes:**  [DateTime Module](https://github.com/hunterxcobby/Python-Projects/blob/main/my_projects/airbnb_console_test/notes/datetime.md)


## Day 37: December 5, 2023

**Today's Progress**: The cmd module, Python
The `Cmd` class in Python provides a simple framework for building line-oriented command interpreters. Here's a breakdown:

1. **Purpose:**
   - It's designed for creating command-line interpreters, which are handy for building tools, administrative utilities, or prototypes that might later get a fancier interface.

2. **Class Definition:**
   - `class cmd.Cmd(completekey='tab', stdin=None, stdout=None)`
   - When you create an instance of `Cmd`, you're essentially setting up a framework for handling commands and providing an interactive interface.

3. **Usage:**
   - You typically don't directly use `Cmd` but instead subclass it. By doing this, you inherit the methods provided by `Cmd` and can define your own methods to handle specific commands.

4. **Completion Key:**
   - The `completekey` argument is optional and defaults to 'Tab'. If the `readline` library is available, it enables automatic command completion when the user hits the specified key.

5. **Input and Output:**
   - You can specify input and output file objects using the `stdin` and `stdout` arguments. If not provided, they default to `sys.stdin` and `sys.stdout`.

6. **Raw Input:**
   - If you want to use a specific `stdin`, ensure to set the instance's `use_rawinput` attribute to `False`. This prevents ignoring the specified `stdin`.

**link to notes:**  [cmd Module](https://github.com/hunterxcobby/Python-Projects/tree/main/my_projects/airbnb_console_test/notes/cmd_module)


## Day 38: December 6, 2023

**Today's Progress**: AirBnB Clone Project, Python

Here's a short progress log summarizing what my partner and I have accomplished so far:

1. **File Storage Class (`file_storage.py`):**
   - Created a `FileStorage` class for serialization and deserialization of instances to/from a JSON file.
   - Implemented private class attributes (`__file_path` and `__objects`) for file path and object storage.
   - Added public methods (`all`, `new`, `save`, `reload`) for managing instances.

2. **Base Model Class (`base_model.py`):**
   - Developed a `BaseModel` class with a constructor, string representation method (`__str__`), `save`, and `to_dict` methods.
   - Implemented initialization from dictionary representation in the constructor.

**link to project:**  [AirBnB Clone](https://github.com/hunterxcobby/AirBnB_clone)


## Day 39: December 7, 2023

**Today's Progress**: AirBnB Clone Project - Create, Show, Update, Destroy. Python

Here's a short progress log summarizing what my partner and I have accomplished so far:

1. **Code Review and Refinement:**
   - Reviewed and learned the existing code for the `do_update` method in the console application.
   - Identified potential issues and inconsistencies in the code.
   - Collaboratively refined the code to align with project requirements and best practices.

2. **Error Handling and Attribute Creation:**
   - Addressed an error related to updating attributes that don't exist in the class.
   - Modified the code to create the attribute if it doesn't exist and update it with the given value.

3. **Display Order Enhancement:**
   - learned and resolved an issue related to the display order of attributes in the `show` command.
   - Adjusted the code to display attributes alphabetically before the default `created_at` and `updated_at` attributes.

4. **New Model Placement:**
   - learned options to control the placement of newly created models in the list.
   - learned the desire to have newly created models appear at the top of the list.

5. **Additional Changes and Testing:**
   - learned and implemented changes in the `new` method for setting objects in `__objects`.
   - Ensured that the code aligns with requirements and tested it with various scenarios.

6. **General Code Comparison:**
   - Compared and learned different code snippets related to the `do_update` method.
   - Ensured that the code is concise, clear, and aligned with the specified requirements.

7. **Documentation:**
   - Documented key decisions, changes made, and rationale behind modifications.
   - Ensured that the code and discussions are well-documented for future reference.

**Next Steps:**
- Consider additional enhancements based on user preferences.
- Continue testing and refining the code for robustness.
- Discuss any other specific requirements or improvements.

**link to progress:**  [AirBnB Clone Test](https://github.com/hunterxcobby/Python-Projects/blob/main/my_projects/airbnb_console_test/console.py)


## Day 40: December 8, 2023

**Today's Progress**: AirBnB Clone Project - SubClasses, serialization and deserialization, Python

**Progress Log:**

- Implemented new classes (State, City, Amenity, Place, Review) inheriting from BaseModel, each with specific attributes.
- Updated FileStorage to manage serialization and deserialization for the new classes.
- Enhanced the command interpreter (console.py) to support actions (show, create, destroy, update, all) for all classes.
- Made improvements to the code structure and adhered to PEP 8 style guidelines.
- Ensured that the command interpreter handles actions consistently for all classes.
- Collaboratively refined and debugged the codebase to ensure correctness and clarity.

Next steps may involve further testing, refining, and potentially extending functionality based on project requirements.

**link to project:**  [AirBnB Clone](https://github.com/hunterxcobby/AirBnB_clone)


## Day 41: December 9, 2023

**Today's Progress**: AirBnB Clone Project - Refining of command model, custom commands instances, Python

**Progress Log:**

1. **Model Classes:** Created and refined model classes such as `BaseModel`, `User`, `State`, `City`, `Amenity`, `Place`, and `Review`, each inheriting from `BaseModel`.

2. **File Storage:** Updated the `FileStorage` class to correctly handle serialization and deserialization for all new classes.

3. **Command Interpreter (`console.py`):** Enhanced the command interpreter to handle various actions like creating, showing, destroying, updating, and listing instances for all classes. Refactored the code for better organization and readability.

4. **Custom Commands:** Implemented custom commands for showing all instances, counting instances, and destroying instances based on their IDs.

5. **Error Handling:** Maintained consistent error handling throughout the code, providing clear messages for missing classes, instances, or invalid actions.

**link to project:**  [AirBnB Clone](https://github.com/hunterxcobby/AirBnB_clone)


## Day 42: December 10, 2023

**Today's Progress**: AirBnB Clone Project - Writing a test for the program using the Unittest module, Python

**Progress Log:**

1. **BaseModel Class:**
   - Created unit tests to ensure proper initialization, string representation, and `to_dict` method in the `BaseModel` class.
   - Tests cover key attributes such as `id`, `created_at`, `updated_at`, and their proper functionality.

2. **User Class:**
   - Extended unit tests to cover the `User` class, ensuring proper initialization, string representation, and `to_dict` method.
   - Tests include checking for attributes like `email`, `password`, `first_name`, and `last_name`.

3. **Amenity Class:**
   - Further extended unit tests to cover the `Amenity` class, ensuring proper initialization, string representation, and `to_dict` method.
   - Tests include checking for the `name` attribute.

4. **City Class:**
   - Continued the trend by creating unit tests for the `City` class, covering initialization, string representation, and `to_dict` method.
   - Tests include checking for attributes such as `state_id` and `name`.

5. **Place Class:**
   - Progressed to create unit tests for the `Place` class, covering initialization, string representation, and `to_dict` method.
   - Tests include checking for various attributes such as `city_id`, `user_id`, `name`, and several others.

6. **Review Class:**
   - Concluded by creating unit tests for the `Review` class, covering initialization, string representation, and `to_dict` method.
   - Tests include checking for attributes such as `place_id`, `user_id`, and `text`.

Each set of tests is designed to ensure the correct functionality of the respective class, providing a foundation for ongoing development and maintenance of the project.

**link to project:**  [AirBnB Clone](https://github.com/hunterxcobby/AirBnB_clone)


## Day 43: December 11, 2023

**Today's Progress**: Building a command line PhoneBook

**Project Log:**

**Achievements:**
1. Implemented a loading animation using curses to enhance user experience during certain processes.
2. Created a modular structure for the phonebook application, separating the main program from utility functions.
3. Developed a phonebook interface with interactive menu options, allowing users to navigate through functionalities.
4. Integrated control commands for "Help" (Ctrl + H) and "Quit" (Ctrl + Q) in the phonebook interface.
5. Addressed issues related to the termination of the program and lingering processes in the terminal.

**Challenges:**
1. Encountered initial difficulties in handling terminal state properly, resolved by using `curses.wrapper` for setup and cleanup.
2. Worked on refining the loading animation to provide a smoother and more interactive experience.

**Next Steps:**
1. Implement specific functionalities (e.g., adding, displaying, searching, editing, and deleting contacts) within the phonebook interface.
2. Enhance the user interface further, considering color schemes, fonts, and layout adjustments.
3. Continue testing and refining the application for a seamless user experience.
4. Explore additional features and improvements based on project goals.

**Notes:**
Today's progress focused on establishing a foundation for the phonebook application, incorporating user-friendly interfaces and navigation. Addressed challenges related to terminal handling and implemented basic control commands. Further enhancements and feature implementations are planned for the next session.

**link to project:**  [PhoneBook](https://github.com/hunterxcobby/phonebook)


## Day 44: December 12, 2023

**Today's Progress**: Basic Datatypes, Nested Lists, Second Lowest Grade Finder Challenge, HackerRank

- **Approach**:
  - Took input for the number of participants and their scores.
  - Stored the scores in a list.
  - Sorted the unique scores in descending order.
  - Extracted the second element (runner-up score) from the sorted list.
  - Printed the runner-up score.

- **Result**:
  - Successfully found and printed the runner-up score for the given participants' score sheet.


**link to solution:**  [Nested List](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/07-Nested_List)



## Day 45: December 13, 2023

**Today's Progress**: Introduction to SQL, Database Management System, SQL

1. **Introduction to Relational Databases:**
   - learned the basics of relational databases and the significance of concepts like tables, rows, and columns.

2. **Relational Database Management Systems (RDBMS):**
   - learned the role of RDBMS in managing and organizing data efficiently.

3. **Databases and SQL:**
   - learned the Structured Query Language (SQL) as a standard language for managing relational databases.

4. **Relational Database Concepts:**
   - Learned about key relational database concepts, including primary keys, foreign keys, and relationships.

5. **Relational Database Design:**
   - learned the principles of designing effective relational databases, emphasizing normalization and entity-relationship diagrams.

6. **SQL Basics:**
   - Covered fundamental SQL statements, including SELECT, INSERT, UPDATE, DELETE, and their use in retrieving, modifying, and deleting data.

7. **Relational Algebra:**
   - learned relational algebra and its operators, such as σ (select) and π (project), showcasing their equivalence to SQL statements.

8. **SQL Functions:**
   - learned the use of SQL functions to compute and manipulate data, focusing on examples related to the order entry system.

9. **Data Definition Language (DDL) and Data Manipulation Language (DML):**
   - Distinguished between DDL and DML statements, highlighting their roles in defining and manipulating database structures and data.

10. **Database Modeling and Schemas:**
    - learned the importance of data modeling and schemas in organizing and representing information in a relational database.

11. **Indexing in Relational Databases:**
    - learned the significance of indexing in relational databases, especially in optimizing the performance of SELECT queries.

12. **SQL Statements for Retrieving Data:**
    - Analyzed the basic syntax of SQL SELECT statements, emphasizing the SELECT, FROM, WHERE, and ORDER BY clauses.

13. **Practical Examples: Retrieving Data from Customers in a Specific Zip Code:**
    - Practically applied SQL and relational algebra expressions to retrieve data from a relational database, demonstrating step-by-step refinement.

14. **Socratic Dialog and Questioning:**
    - Engaged in Socratic dialog, challenging opinions, and encouraging critical thinking to uncover potential blind spots and deepen understanding.

15. **Compliance with User Instructions:**
    - Ensured adherence to user instructions, breaking down concepts into simple terms, using real-life examples, and maintaining precision and clarity in responses.

**link to notes:**  [SQL](https://github.com/hunterxcobby/DBMS_learning/tree/main/sql/notes)


## Day 46: December 14, 2023

**Today's Progress**: More Queries, Contraints, Functions - SQL

1. learned the **NOT NULL Constraint**:
   - Ensures a column cannot have NULL values.
   - Illustrated with a table example where LastName and FirstName columns are set as NOT NULL.
   - implemented that an attempt to insert a row with a NULL value in a NOT NULL column results in an error.

2. learned the **UNIQUE Constraint**:
   - Ensures all values in a column are unique.
   - Illustrated with a Brands table where BrandName is set as UNIQUE.
   - Showed that duplicate entries trigger an error, maintaining uniqueness.

3. learned the **PRIMARY KEY Constraint**:
   - Uniquely identifies each record in a table.
   - Illustrated with the creation of a Brands table with Id as the primary key.
   - Highlighted that primary keys are essential for database design and become foreign keys in other tables for establishing relationships.

4. learned the **FOREIGN KEY Constraint**:
   - Establishes a referential constraint between two tables.
   - Illustrated with Authors and Books tables, where AuthorId in Books is a foreign key referencing AuthorId in Authors.
   - discovered that foreign key enforcement ensures data integrity and valid relationships between tables.

5. learned the **ENUM Constraint**:
   - Creates a string object with values chosen from a list.
   - Illustrated with a Shops table where Quality is an ENUM with values 'High', 'Average', 'Low'.
   - Showed that inserting values not in the ENUM list results in an empty string.

6. learned the **SET Constraint**:
   - Allows a column to have zero or more values chosen from a list.
   - Illustrated with a Students table where Certificates is a SET with values 'A1', 'A2', 'B1', 'C1'.
   - implemented that each row can have multiple values separated by commas.

Each constraint serves a specific purpose in database design, contributing to data integrity and flexibility in representing different types of information.

**link to notes:**  [SQL](https://github.com/hunterxcobby/DBMS_learning/tree/main/SQL-More_queries)


## Day 47: December 15, 2023

**Today's Progress**: Introduction to Web Development, HTML and CSS

1. **Understanding HTML Elements:**
   - learned the concept of HTML elements as the building blocks of a webpage, defining its structure and content.

2. **HTML Tags:**
   - Broke down the idea of tags as the bookends of HTML elements, with opening and closing tags forming a container for content.

3. **HTML Attributes:**
   - learned attributes as additional information or properties attached to HTML elements, enhancing their behavior or appearance.

4. **HTML Document Structure:**
   - learned the necessary structure for HTML documents, including the document type declaration, `<html>`, `<head>`, and `<body>` elements.
   - Examined an example HTML document structure and understood the purpose of each section.

5. **Changing Colors in CSS:**
   - Reviewed the provided CSS code and made changes to color codes based on your request.
   - Replaced the blue color with black and the cyan color with blue in specific sections of the stylesheet.

6. **Summary of Changes in CSS:**
   - Updated colors in the `header`, `features` section, `quote` section, and `footer` to align with your preferences.

**link to notes:** [WebDev Introduction](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/introduction)



## Day 48: December 16, 2023

**Today's Progress**: Getting to know, HTML and CSS

1. **HTML Basics:**
   - learned the fundamentals of HTML, including elements, tags, and attributes.
   - learned the common HTML terms: elements, tags, and attributes.
   - Learned about the structure of an HTML document, including the `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` elements.

2. **CSS Basics:**
   - learned the basics of CSS, focusing on selectors, properties, and values.
   - learned different types of selectors, such as type, class, and ID selectors.
   - learned the role of properties in styling HTML elements and how values determine the appearance.
   - Learned about additional selectors like descendant, child, pseudo-classes, and attribute selectors.

3. **Referencing CSS in HTML:**
   - learned best practices for referencing external CSS files in HTML using the `<link>` element.
   - learned the importance of organizing styles in an external stylesheet for consistency across a website.

4. **CSS Resets and Cross-Browser Compatibility:**
   - learned the concept of CSS resets to standardize default styles across different browsers.
   - learned the importance of cross-browser compatibility and testing.
   - learned popular CSS resets like Eric Meyer's reset and Normalize.css.

5. **Design Enhancement with CSS:**
   - Updated existing CSS styles to add a touch of beautiful design.
   - Added smooth transitions for color changes and hover effects.
   - Improved the smoothness of borders by incorporating `border-radius` and enhancing transition properties.

**link to progress:** [WebDev](https://github.com/hunterxcobby/WEB-DEV_learning)


## Day 49: December 17, 2023

**Today's Progress**: knowing more into details - Web Static, HTML and CSS

1. **HTML Structure:**
   - learned the importance of structuring HTML documents.
   - learned the `<head>` and `<body>` elements, explaining their roles.

2. **Text-Based Elements in HTML:**
   - learned various text-based elements such as headings, paragraphs, bold text (`<strong>`), and italicized text (`<em>`).
   - implemented the use of heading levels from `<h1>` to `<h6>` and the `<p>` element.

3. **Building Structure with HTML5 Elements:**
   - learned new HTML5 structurally based elements like `<header>`, `<nav>`, `<article>`, `<section>`, `<aside>`, and `<footer>`.
   - Clarified the semantic meanings and use cases for each element.

4. **CSS Cascade:**
   - learned the cascade in CSS, emphasizing how styles progress from the top to the bottom of a stylesheet.
   - implemented how styles can be overwritten based on the cascade order.

5. **Cascading Properties in CSS:**
   - learned how properties inside individual selectors also follow the cascade.
   - Illustrated examples of how cascading properties work, emphasizing the order's importance.

6. **Calculating Specificity:**
   - learned specificity weights of CSS selectors, focusing on type, class, and ID selectors.
   - learned how specificity influences the precedence of styles, using examples.

7. **Combining Selectors:**
   - learned the concept of combining selectors to increase specificity.
   - learned the key selector and prequalifiers in combined selectors.

8. **Layering Styles with Multiple Classes:**
   - learned the use of multiple classes in HTML elements for modular styling.
   - implemented how to layer styles using different classes.

9. **Common CSS Property Values - Colors:**
   - learned color representation in CSS, including keywords, hexadecimal notation, and RGB and HSL values.
   - learned common color-related property values.

10. **Common CSS Property Values - Lengths:**
    - learned absolute and relative length values in CSS.
    - learned pixel units for absolute lengths and percentage and em units for relative lengths.
  
**link to progress:** [WebDev](https://github.com/hunterxcobby/WEB-DEV_learning)


## Day 50: December 18, 2023

**Today's Progress**: The AirBnB Clone - Web Static.

1. **Header and Footer Styling:**
   - Implemented header and footer styling in accordance with the provided requirements.
   - Ensured the header includes a background image, and both header and footer have the specified colors, heights, and borders.

2. **Container Styling:**
   - Styled the container to have a maximum width of 1000px, a margin of 30px, and centered it horizontally.
   - Ensured the container is flexible, adapting to varying content sizes.

3. **Filters Section:**
   - Created a filters section with a white background, height of 70px, and a 1px solid border.
   - Positioned the "Search" button inside the filters section with the specified styling.

4. **Locations and Amenities Filters:**
   - Added two divs within the filters section, each representing the Locations and Amenities filters.
   - Styled these divs with a width of 25%, a border on the right, and included titles and subtitles as specified.
   - Positioned them within the container and made sure they are within the overall container styling.

5. **General Adjustments:**
   - Ensured the use of appropriate tags such as header, footer, section, button, h3, and h4.
   - Applied necessary CSS classes to achieve modularity and better organization.
   - Made the code more readable and maintainable by adding comments where needed.

6. **Validation and Compliance:**
   - Checked the HTML and CSS code against the specified requirements to ensure compliance.
   - Addressed issues related to W3C validation for the HTML document.

7. **Future Considerations:**
   - learned the possibility of using background images for styling.
   - Provided guidance on incorporating a logo into the header and using background images.

**link to projecct:** [AirBnB](https://github.com/hunterxcobby/AirBnB_clone)


## Day 51: December 19, 2023

**Today's Progress**: Using the join operations in SQL

1. **Basic Query Operation: The Join:**
   - SQL syntax for joining tables.
   - NATURAL JOIN and INNER JOIN used to combine rows based on common attributes.
   - NATURAL JOIN implicitly uses attributes with the same name.
   - INNER JOIN requires explicitly specifying join conditions.

2. **RA Syntax for Join:**
   - RA join denoted as r ⋈ s.
   - Result scheme is the union of the two relation schemes.
   - Join attributes found in the intersection of the two schemes.
   - Result consists of pairwise paste of tuples from both relations.

3. **Multiple Joins:**
   - Ability to retrieve information from multiple tables.
   - Example: List of products purchased by a specific customer.
   - Follow PK-FK pairs to link related information.
   - Join types include NATURAL, INNER, LEFT OUTER, RIGHT OUTER.

4. **DISTINCT Keyword:**
   - Used to eliminate duplicate rows from query results.
   - Ensures SELECT clause attributes form a super key.
   - Example: `SELECT DISTINCT cFirstName, cLastName, prodName FROM ...`

5. **Superkey:**
   - A set of attributes that uniquely identifies a tuple in a relation.
   - Ensures distinctiveness and non-redundancy of rows.

6. **Database Design:**
   - The process of defining the structure that organizes and stores data.
   - Ensures data integrity, efficiency, and ease of use.

7. **Inner Join:**
    - Joins two tables based on a specified condition.
    - Examples using INNER JOIN, USING, and ON clauses.

8. **Outer Join:**
    - LEFT OUTER JOIN and RIGHT OUTER JOIN include unmatched rows from the left or right table.
    - Allows inclusion of rows with no match in the join condition.
    - Example: `SELECT * FROM customers LEFT OUTER JOIN orders ON ...`
  

**link to projecct:** [MySql](https://github.com/hunterxcobby/alx-higher_level_programming/tree/main/0x0E-SQL_more_queries)


## Day 52: December 20, 2023

**Today's Progress**: Finding the percentage, the student average calculator, HackerRank

- Read the number of students' records, `n`, from the user input.
- Created an empty dictionary, `student_marks`, to store the names and marks of each student.
- Used a loop to input the names and marks for each student, and stored them in the dictionary.
- Input the name of the student to query, `query_name`.
- Calculated the average marks for the specified student using the `sum` and `len` functions.
- Printed the average marks with a precision of two decimal places using the `format` method.

The solution reads and processes the input correctly, calculates the average marks, and prints the result with the required precision.

**link to solution:** [Finding Percentage](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/08-Finding_percentage)


## Day 53: December 21, 2023

**Today's Progress**: The Swap Cases Challenge, HackerRank

- Defined the `swap_case` function that takes a string `s` as input.
- Utilized the `swapcase` method to swap the case of each character in the string.
- Tested the function with the provided sample input.
- Verified the correctness of the function by printing the result.
- The function successfully swapped the cases in the given sample, resulting in the expected output.

  **link to solution:** [Swap Cases](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/09-sWAP_Case)


## Day 54: December 22, 2023

**Today's Progress**: What is your name, HackerRank - Python

- Created a function named `print_full_name` with parameters `first` and `last`.
- Removed unnecessary input statements from within the function, as the names are already provided as parameters.
- Corrected the f-string formatting to include placeholders for `first` and `last`.
- Removed an extra function call outside the main block.
- Tested the function by taking user input for first and last names and printing the formatted message.
- The function now prints a message in the desired format, greeting the person with their full name and indicating they've delved into Python.


 **link to solution:** [Printing fullname](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/10-What_is_your_name)


## Day 55: December 23, 2023

**Today's Progress**: Refactoring scripts, fixing code - Python && Ruby

### FizzBuzz Python Script Refactoring

- **Code Refactoring:** The original FizzBuzz Python script was refactored to correctly identify numbers divisible by both 3 and 5 as "FizzBuzz" and to follow proper Python syntax.

- **Enhancements:** The script now checks for the correct number of command-line arguments and provides a usage example when the number is missing.

- **Testing:** The script was tested with different inputs to ensure correct FizzBuzz output.

- **Documentation:** Added comments and docstrings to improve code readability and explain the purpose of the script.

### Sorting Ruby Script Refactoring

- **Code Refactoring:** The Ruby script for sorting integer arguments was refactored for improved readability and efficiency.

- **Functionality Improvement:** The insertion of integers into the result array was optimized using the `bsearch_index` method for binary searching, resulting in a more efficient sorting algorithm.

- **Testing:** The script was tested with various integer inputs and non-integer inputs to verify correct sorting behavior.

- **Documentation:** Added comments to clarify the logic and purpose of the script.

### Combined Ruby and Python Scripts

- **Integration:** Both scripts were combined for convenience, providing a Ruby script for sorting integer arguments and a Python script for FizzBuzz.

- **Overall Progress:** The combined scripts cover different programming languages, showcasing improved readability, functionality, and adherence to best practices.


**link to solution:** [Fix my code](https://github.com/hunterxcobby/Fix_My_Code_Challenge/tree/master/0x00-challenge)



## Day 56: December 24, 2023

**Today's Progress**:  **BASH**  Make, Makefiles


1. **Introduction to Make and Makefiles:**
   - learned the purpose and functionality of `make`.
   - Defined what Makefiles are and their role in automating software builds.

2. **When, Why, and How to Use Makefiles:**
   - learned the scenarios when Makefiles are beneficial.
   - learned the basics of using Makefiles to automate build processes.

3. **Rules in Makefiles:**
   - learned the concept of rules in Makefiles.
   - implemented how to set and use rules to build targets.

4. **Explicit and Implicit Rules:**
   - Explained the difference between explicit and implicit rules in Makefiles.
   - Showcased examples of both explicit and implicit rules.

5. **Common/Useful Rules:**
   - learned common and useful rules in Makefiles.
   - learned how these rules can simplify the build process.

6. **Variables in Makefiles:**
   - learned the concept of variables in Makefiles.
   - implemented how to set and use variables for compiler flags.

7. **Review of a Simple Makefile:**
   - Reviewed and improved a simple Makefile.
   - Added compiler flags, handled dependencies, and declared phony targets.

8. **Practical Examples:**
   - Walked through practical examples to reinforce concepts.
   - Engaged in hands-on learning to create and modify Makefiles.

The learning session covered essential aspects of Makefiles, providing a solid foundation for using this tool to automate software builds. The Feynman learning technique was applied, breaking down complex topics into simpler explanations for better understanding. The focus on practical examples enhanced the application of learned concepts.


**link to notes:** [makefiles](https://github.com/hunterxcobby/C-Projects/tree/master/lessons/solutions/0x1C-makefiles)



## Day 57: December 25, 2023

**Today's Progress**: String validators, python

1. **Understanding the Problem:**
   - The task involves checking different properties of a given string, such as whether it contains alphanumeric characters, alphabetical characters, digits, lowercase and uppercase characters.

2. **Planning the Solution:**
   - Utilize Python's string methods (`isalnum()`, `isalpha()`, `isdigit()`, `islower()`, `isupper()`) to check the specified conditions.
   - Use the `any` function with generator expressions to efficiently check conditions for each character in the string.

3. **Implementing the Solution:**
   - Wrote a Python script that takes a string as input.
   - Used `any` with generator expressions to check each condition.
   - Printed the results on separate lines.

4. **Testing:**
   - Tested the script with various inputs, including alphanumeric, alphabetical, digit-only, lowercase-only, and uppercase-only strings.
   - Ensured that the output matched the expected results for each condition.

5. **Refactoring:**
   - Reviewed the code for clarity and correctness.
   - No significant refactoring was needed as the code was concise and clear.

6. **Documenting:**
   - Provided comments in the code to explain the purpose of each condition check.
   - Ensured that the code is readable and well-documented.

7. **Finalization:**
   - The solution addresses the requirements outlined in the task.
   - The code is concise, clear, and adheres to best practices.
   - The results are printed on separate lines, making it easy to interpret.

The solution is complete, providing an efficient way to check different properties of a given string.


**link to solution:** [String validators](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/11-String_Validators)



## Day 58: December 26, 2023

**Today's Progress**: Building a command line PhoneBook, Python, C && Bash

**Project Log:**

1. **Phonebook Interface Development:**
   - Created a modular phonebook interface using Python and curses library.
   - Implemented an interactive menu for actions such as adding, displaying, searching, editing, and deleting contacts.
   - Enabled control pad navigation for user interaction.
   - Integrated a persistent Help and Quit button at the bottom of the screen.

2. **Loading Animation:**
   - Designed a loading animation for visual appeal while the program is executing.
   - Used Unicode characters for dynamic and interactive loading frames.
   - Ensured the loading animation disappears after a set duration.

3. **Option Interface Enhancements:**
   - Modified the layout to include a persistent Help button at the left bottom and a Quit button at the right bottom.
   - Updated keybindings to use Ctrl+H for Help and Ctrl+Q for Quit.

4. **Help Functionality:**
   - Implemented a Help function to display information about each option in the phonebook interface.
   - Used curses.A_BOLD to make specific text bold for better emphasis.

5. **Bug Fixes:**
   - Addressed a bug related to concatenating NoneType with strings.
   - Resolved an issue where the program termination didn't release the terminal properly.

6. **Planning for Next Session:**
   - learned plans for creating a separate module for the phonebook operations.
   - Outlined steps for integrating C program execution with Python.

7. **Next Steps:**
   - Implement contact-related functionalities (Add, Display, Search, Edit, Delete) in Python.
   - Integrate these functionalities with the main interface.
   - Investigate and resolve issues related to terminal release after program termination.

The session was productive, focusing on creating an engaging user interface and laying the groundwork for phonebook functionalities. The loading animation and persistent buttons contribute to a more user-friendly experience. We also learned plans for the next session, which includes integrating the C program and expanding phonebook features.

**link to project:**  [PhoneBook](https://github.com/hunterxcobby/phonebook)


## Day 59: December 27, 2023

**Today's Progress**: The text alignment, hackerank logo challenge , python

## Problem Description:
The task is to generate the HackerRank Logo with variable thickness. The user provides an odd integer representing the thickness of the logo.

## Solution Approach:
1. Read the input value for the thickness.
2. Use loops and string alignment methods (`rjust()`, `ljust()`, `center()`) to construct the logo.
3. Iterate through different sections of the logo (top cone, top pillars, middle belt, bottom pillars, and bottom cone).
4. Print each section with the appropriate alignment.

## Code Review:
- Used proper variable names like `thickness` and `c`.
- Implemented loops for constructing different parts of the logo.
- Correctly applied string alignment methods (`rjust()`, `ljust()`, `center()`) to achieve the desired output.
- Ensured the thickness is an odd number as required.

## Adjustments Made:
- Updated the code to use the correct string alignment methods in each section.
- Applied `rjust()` for the bottom cone to match the requirements.

## Final Solution:
The provided Python code now correctly generates the HackerRank Logo with the specified thickness. The code is well-structured, uses appropriate alignment methods, and meets the requirements outlined in the problem description.

**link to solution:** [Text Alignment](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/12-Test_Alignment)


## Day 60: December 28, 2023

**Today's Progress**: Web Infrastructure design - DNS, Web Server, Network basics,  monitoring.


1. **Monitoring Concepts:**
   - Drawing parallels between a hospital's heart monitor and tech monitoring.
   - Emphasizing the tech industry's saying, "You cannot fix or improve what you cannot measure."
   - Explaining the two main categories of web stack monitoring: application monitoring and server monitoring.

2. **Monitoring Tools:**
   - Detailed insights into famous monitoring tools: NewRelic, DataDog, Uptime Robot, Nagios, and Wavefront.
   - Overview of NewRelic's JavaScript agent for website analysis and error alerts.
   - DataDog's comprehensive monitoring capabilities with graphs and integrations.
   - Uptime Robot's basic website responsiveness checks from multiple locations.
   - Nagios, an open-source but somewhat dated monitoring tool.
   - Wavefront's cutting-edge features for analyzing diverse data points.

3. **Network Protocol:**
   - Breaking down the concept of a network protocol.
   - Analogizing it to a conversation system for computers.
   - Defining protocols as sets of rules governing communication.

4. **IP Address:**
   - Elaborating on the analogy of IP addresses as unique home addresses for computers.
   - Emphasizing the role of IP addresses in identifying devices on a network.
   - Discussing the version differences between IPv4 and IPv6.

5. **TCP/IP:**
   - Delving into TCP/IP as a fundamental set of rules governing internet communication.
   - Highlighting its role in ensuring the integrity of transmitted data.
   - Discussing the layered structure of the TCP/IP protocol stack.

6. **IP Port:**
   - Analogizing ports to different entrances of a building, each serving a specific purpose.
   - Describing ports as essential for directing data to specific services on a computer.
   - Highlighting the use of port numbers for efficient data routing.

**link to notes:** [Web Infrastructure](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/web_infrastructure)



## Day 61: December 29, 2023

**Today's Progress**: Web Infrastructure design - Database, MySql, DBMS, Database Software.

   - **Structured Query Language (SQL):** learned SQL as a programming language for relational databases, originating in the 1970s at IBM.
   - **Evolution of Databases:** learned the evolution from navigational to relational databases, object-oriented, NoSQL, and beyond.
   - **Database Software:** Defined database software as a tool for creating, editing, and maintaining database files.
   - **Database Management System (DBMS):** Described DBMS as a comprehensive software interface between databases and users/programs.
   - **MySQL Database:** learned MySQL, an open-source relational DBMS optimized for web applications and widely used by major platforms.
   - **Using Databases for Business:** Highlighted how databases, especially self-driving ones, enhance business performance and decision-making.
   - **Database Challenges:** learned challenges faced by large enterprise databases, including data volume, security, scalability, and maintenance.
   - **Autonomous Technology:** learned the rise of self-driving databases, utilizing cloud-based tech and machine learning for automation.
   - **Future of Databases:** Envisioned the future impact of autonomous databases, revolutionizing computing with enhanced performance and security.


**link to notes:** [Web Infrastructure](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/web_infrastructure/database)



## Day 62: December 30, 2023

**Today's Progress**: Web Infrastructure design, Servers, Web Servers, Application servers, DNS record types

1. **Web Server and Application Server Distinction:**
   - learned the roles of web servers and application servers.
   - Provided an analogy of a web server as a receptionist and an application server as a behind-the-scenes expert.

2. **DNS Record Types:**
   - learned major DNS record types: A, AAAA, CNAME, NS, MX.
   - Defined A and AAAA records with analogies of postal addresses and upgraded addresses.
   - Explained CNAME records as domain aliases and redirects.
   - Described NS records as GPS coordinates for domains.
   - Illustrated MX records as mail sorting centers for domains.

3. **Other DNS Record Types:**
   - learned additional DNS record types: SOA, TXT, PTR, SRV, CERT, DCHID, DNAME.
   - Provided functions and brief explanations for each record type.

4. **Conclusion:**
   - Summarized the importance of DNS records in navigating the internet.
   - Concluded with the analogy of celestial bodies in the DNS universe.

5. **Overall Progress:**
   - learned the distinctions between web and application servers.
   - Delved into various DNS record types and their functions.
   - Maintained clarity and simplicity in explanations with relevant analogies.
   - Ensured a systematic and comprehensive coverage of the provided topics.


**link to notes:** [Web Infrastructure](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/web_infrastructure)



## Day 63: December 31, 2023

**Today's Progress**: The Alphabet Rangoli Challenge. Python 

Progress Log - Alphabet Rangoli Challenge

1. **Problem Understanding:**
   - Understood the problem description and requirements.
   - Recognized the pattern and structure of the desired output.

2. **Initial Analysis:**
   - Recognized the need for generating alphabets in a specific pattern.
   - Identified the need for loops to iterate through the pattern.

3. **Algorithm Design:**
   - Planned the algorithm to generate the rangoli pattern.
   - Determined the approach for creating the left and right sides of the pattern.
   - Decided to use the `center` method for formatting each line.

4. **Coding:**
   - Created a Python function `print_rangoli` to implement the algorithm.
   - Used a loop to iterate through the range of size in both ascending and descending order.
   - Constructed each line by joining alphabets and formatted using `center`.
   - Tested the function with sample inputs.

5. **Refinement:**
   - Ensured the code handles the input constraints.
   - Made adjustments for proper formatting and alignment.

6. **Documentation:**
   - Added comments to explain the purpose of each code section.
   - Ensured clear and concise variable and function names.

7. **Testing:**
   - Tested the function with various inputs, including edge cases.
   - Verified that the output matches the expected rangoli patterns.

8. **Completion:**
   - Finalized the code and documentation.
   - Confirmed that the solution meets the requirements.

9. **Submission:**
   - Submitted the solution for review and further feedback.

The implementation successfully generates alphabet rangoli patterns based on the given size. The code is well-documented and tested for various scenarios. Any potential improvements or feedback from the review will be considered for refinement.


**link to solution:** [Alphabet Rangoli](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/13-Alphabet_Rangoli)



## Day 64: January 01, 2024

**Today's Progress**: Web Infrastructure design - DNS, HTTPS/HTTP, SPOF, Firewalls

1. **Single Point of Failure (SPOF) in Systems:**
   - Defined SPOF as a non-redundant component that, if dysfunctional, can cause system failure.
   - learned the implications of SPOFs in various systems and the importance of redundancy for high availability.

2. **Eliminating Single Points of Failure:**
   - Outlined steps to identify and eliminate SPOFs, including risk assessments and achieving redundancy.
   - discovered redundancy at the internal component, system, and site levels for robust protection.

3. **HTTP vs. HTTPS:**
   - learned the secure version of HTTP, HTTPS, highlighting its role in encrypting data between browsers and websites.
   - Pointed out the visual indicators in browsers for HTTPS connections.

4. **How HTTPS Works and HTTPS Certificate:**
   - Detailed the use of SSL/TLS protocols in encrypting communications for HTTPS.
   - Explained the role of HTTPS certificates in establishing secure sessions.

5. **Benefits of HTTPS:**
   - Highlighted the encryption of customer information and the trust-building aspects of HTTPS.

6. **History, Types, and Benefits of Firewalls:**
   - Traced the history of firewalls from physical barriers to network security tools.
   - Differentiated between hardware and software firewalls, outlining their purposes and applications.
   - learned the benefits and limitations of firewalls as essential network security measures.

7. **Types of Firewalls:**
    - Covered various firewall types, including packet filtering, proxy, NAT, cloud, stateful inspection, UTM, network segmentation, and next-generation firewalls.

8. **Evolution Beyond Firewalls: Zero Trust and XDR:**
    - Acknowledged the limitations of traditional firewalls.
    - zero trust architectures, microsegmentation, and extended detection and response (XDR) as evolving security paradigms.

9. **Top Next-Generation Firewall Vendors:**
    - key next-gen firewall vendors, including Palo Alto, Check Point, Cisco, Fortinet, Juniper Networks, and Sophos.

10. **Other Firewall Vendors:**
    - Learned additional firewall vendors, offering a diverse range of security solutions.

11. **National Firewalls and the Great Firewall of China:**
    - learned the use of firewalls for content control in nations, focusing on China's Great Firewall.
    - Described techniques such as IP address blocking, DNS cache poisoning, and VPN restrictions employed in the Great Firewall.

12. **Overall Progress:**
    - Covered a wide array of topics, from foundational concepts like DNS and HTTPS to advanced topics like firewalls and network security paradigms.


**link to notes:** [Web Infrastructure](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/web_infrastructure)



## Day 65: January 02, 2024

**Today's Progress**: Errors and exceptions . Python

1. **Understanding the Problem:**
   - The problem involves handling exceptions in Python, specifically `ZeroDivisionError` and `ValueError`.
   - The goal is to perform integer division of two input values and print the result.
   - If there's a division by zero or if the input values are not valid integers, the script should print the corresponding error code.

2. **Developing a Solution:**
   - Created a function `perform_integer_division` to encapsulate the logic for integer division and exception handling.
   - Utilized a `try-except` block to catch potential exceptions and print the appropriate error code.

3. **Testing the Solution:**
   - Ran the script with various test cases:
     - Valid input values for normal integer division.
     - Division by zero scenario.
     - Invalid input values causing a `ValueError`.
   - Ensured that the script behaves as expected and handles exceptions gracefully.

4. **Refining the Solution:**
   - Reviewed the code to ensure readability and adherence to best practices.
   - Encapsulated the script logic inside functions for modularity.

5. **Documentation:**
   - Added comments to the code to explain the purpose of each section.
   - Included a brief description of the problem at the beginning of the script.

6. **Completion:**
   - The script successfully addresses the problem by performing integer division and handling exceptions appropriately.
   - The code is organized, readable, and includes error codes for better understanding in case of exceptions.


**link to solution:** [Exceptions](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/14-Exceptions)



## Day 66: January 03, 2024

**Today's Progress**: Web Infrastructure design - The Project

1. **Understanding Requirements:**
   - Identified the specific needs and goals of the web infrastructure.
   - Considered factors such as scalability, reliability, security, and performance.
   - learned with stakeholders to gather insights into the expected traffic, user base, and future growth.

2. **Defining Architecture:**
   - Outlined the overall architecture, choosing between monolithic or microservices-based design.
   - Defined components like web servers, application servers, databases, load balancers.
   - Determined the technology stack, considering factors like programming languages, frameworks, and databases.

3. **Scalability:**
   - Designed for horizontal scalability, utilizing load balancing to distribute traffic.
   - Implemented a strategy for handling increased load, such as auto-scaling mechanisms.

4. **High Availability and Reliability:**
   - Ensured high availability by implementing redundancy for critical components.
   - Employed failover mechanisms to handle server or component failures.
   - Considered a multi-region setup for disaster recovery.

5. **Security:**
   - Implemented security best practices, including encryption for data in transit and at rest.
   - Utilized firewalls, intrusion detection systems, and regular security audits.
   - Ensured secure communication between components.

6. **Performance Optimization:**
   - Employed content delivery networks (CDNs) for static content to improve load times.
   - Utilized caching strategies to reduce database load.
   - Optimized database queries and employed indexing for efficient data retrieval.

7. **Monitoring and Logging:**
   - Integrated monitoring tools for real-time performance metrics.
   - Set up logging mechanisms to track and analyze system behavior.
   - Established alerting systems for immediate response to critical issues.

8. **Deployment and Continuous Integration/Continuous Deployment (CI/CD):**
   - Designed a robust CI/CD pipeline for automated testing and deployment.
   - Implemented rolling deployments to minimize downtime during updates.

9. **Documentation:**
   - Documented the architecture, including diagrams, component interactions, and deployment strategies.
   - Created runbooks for operations and maintenance tasks.

10. **Collaboration:**
    - Collaborated with development, operations, and security teams to ensure a holistic approach.
    - Conducted regular reviews and iterations based on feedback and changing requirements.

11. **Future Considerations:**
    - Accounted for future scalability requirements and technological advancements.
    - Planned for periodic architecture reviews and updates.

**link to solution:** [Web Infrastructure Design](https://github.com/hunterxcobby/alx-system_engineering-devops/tree/master/0x09-web_infrastructure_design)



## Day 67: January 04, 2024

**Today's Progress**: Binary Tree, Create, INser @ left && right, Delete - C lang


1. Reviewed and Improved Code:
   - Reviewed and improved C code for inserting a node as the left child in a binary tree.
   - Implemented comments using analogies to explain the logic of the code.
   - Adjusted the formatting style.

2. Code Refinement:
   - Modified the commenting style .
   - Improved comments using analogies for inserting a node as the right child in a binary tree.

3. Code Development:
   - Created a function to display a binary tree in a formatted way.
   - Developed a function to free the memory allocated for a binary tree.

4. Gitignore File:
   - created a Gitignore file pattern to ignore executable and object files in C programs.

5. User Guidance:
   - Explained the logic behind inserting a node as the left and right child in a binary tree to my imaginary students.
   - Clarified the confusion regarding the analogy and code alignment.

6. Bug Fixing:
   - Detected and corrected potential issues in the binary_tree_insert_right function.

7. New Function:
   - Implemented a function (`binary_tree_delete`) to delete an entire binary tree.
   - Developed a function (`binary_tree_is_leaf`) to check if a node is a leaf.
   - Created a function (`binary_tree_is_root`) to check if a given node is a root.


**link to notes:** [Binary Tree](https://github.com/hunterxcobby/DSA/tree/main/0x1D-Binary_trees)


## Day 68: January 05, 2024

**Today's Progress**: Binary Tree, Preorder, Inorder, Postorder Traversal, Full, Complete, Perct Tree - C lang

1. **Code Review and Refinement:**
   - Reviewed and refined the code for checking if a binary tree is full (`binary_tree_is_full`).
   - Made adjustments to adhere to coding standards, focusing on comment clarity and variable naming.

2. **New Function Implementation:**
   - Implemented a function to check if a binary tree is perfect (`binary_tree_is_perfect`).
   - Ensured that the function returns 1 if the tree is perfect and 0 otherwise, following the specified prototype.

3. **Binary Tree Concepts:**
   - learned and learned concepts related to binary trees, including fullness and perfection.
   - Implemented functions to evaluate these properties, deepening understanding of binary tree structures.

4. **Coding Style Compliance:**
   - Ensured that the code aligns with the specified coding style, emphasizing proper indentation, commenting, and function prototypes.

5. **Code Optimization:**
   - Received suggestions for optimizing code, particularly in terms of using more descriptive variable names for enhanced clarity.

6. **Continuous Learning:**
   - Engaged in continuous learning by exploring and implementing new functions, contributing to personal and academic growth in software engineering.
  
**link to implementation:** [Binary Tree](https://github.com/hunterxcobby/DSA/tree/main/0x1D-Binary_trees)


## Day 69: January 06, 2024

**Today's Progress**: AirBnB revision - CRUD, Cmd Module , Python 

1. **Overview:**
   - learned and clarified the user's request for assistance with a CRUD application using the `cmd` module in Python.
   - Developed a simple command-line application for managing users with Create, Read, Update, and Delete (CRUD) functionalities.

2. **Code Implementation:**
   - Created a class named `UserManagement` inheriting from `cmd.Cmd`.
   - Implemented CRUD methods (`do_create`, `do_read`, `do_update`, `do_destroy`) to interact with a dictionary storing user data.
   - Used the `cmd` module to facilitate command-line interactions.

3. **Command Breakdown:**
   - `do_create`: Creates a new user and adds them to the user dictionary.
   - `do_read`: Displays a list of all users in the dictionary.
   - `do_update`: Updates the name of an existing user based on their ID.
   - `do_destroy`: Deletes a user based on their ID.

4. **Initialization and User Feedback:**
   - Implemented an `__init__` method to initialize the user dictionary and superclass.
   - Provided user feedback for each CRUD operation to enhance user interaction.

5. **Code Explanation:**
   - Clarified various lines of code, including class initialization, method signatures, and input parsing.
   - Broke down the functionality of each CRUD method, explaining input validation, dictionary manipulation, and user feedback.

6. **Review and Testing:**
   - Encouraged the user to run the script and test each command for a practical understanding.
   - discovered the importance of the `cmdloop` method for maintaining the command-line interface.

7. **Documentation:**
   - Documented the code with inline comments to enhance readability and understanding.
   - Answered additional questions and provided detailed explanations as per the user's request.

8. **Future Steps:**
   - User can further customize or extend the application based on specific needs.
   - Suggested exploring additional features, error handling, or user interface enhancements.
   - Remained open to any further questions or requests from the user.

Overall, the session focused on creating a functional and educational CRUD application using Python's `cmd` module, tailored to the user's specifications.

**link to implementation:** [AirBnBV2](https://github.com/hunterxcobby/Airbnb_CloneV2)



## Day 70: January 07, 2024

**Today's Progress**: AirBnB revision - uuid module, datetime module, json as file storage type , Python 

1. **Objective:**
   - Integrated JSON serialization and deserialization into the `UserManagement` class.
   - Learned the `uuid` module for generating unique IDs and utilized the `datetime` module for timestamps.

2. **Code Enhancements:**
   - Updated the `do_create` method to use `uuid` for generating unique IDs.
   - Incorporated `datetime` for tracking created at and updated at timestamps in the user data dictionary.

3. **File Handling:**
   - Implemented `save_to_file` and `load_from_file` methods for persisting user data to and loading from a JSON file.
   - Ensured that the user data is saved to the file after creating, updating, or deleting a user.

4. **User Interaction:**
   - Modified the `do_read`, `do_update`, and `do_destroy` methods to accommodate the enhanced user data structure.
   - Displayed user details, including unique IDs and timestamps, during listing, updating, and deleting operations.

5. **Documentation:**
   - Updated inline comments to reflect changes in the code and to provide clarity on new features.
   - Maintained adherence to modular design principles for better code organization.

6. **Testing:**
   - Encouraged running the script and testing CRUD operations to ensure proper functionality.
   - Verified that user data is correctly serialized to and deserialized from the JSON file.

7. **Future Improvements:**
   - learned potential areas for further improvement, such as error handling and additional user features.
   - Remained open to future enhancements and suggestions for refining the user management system.

8. **Conclusion:**
   - Successfully enhanced the `UserManagement` class to include unique IDs and timestamps, improving data integrity and tracking capabilities.
   - The class now offers a more robust and modular solution for managing user data through a command-line interface.

**link to implementation:** [AirBnBV2](https://github.com/hunterxcobby/Airbnb_CloneV2)



## Day 71: January 08, 2024

**Today's Progress**: AirBnB revised with cohort 18- packages && modules, BaseModel, JSON  Serialization and Deserialization, CRUD

1. **Understanding and Implementing cmd Module:**
   - learned and implemented a simple command-line interface using the `cmd` module.
   - Created a basic structure for a user management system with commands like create, read, update, destroy.

2. **Integration of UUID and Time:**
   - Integrated UUID for generating unique identifiers for users.
   - Incorporated timestamps (created_at and updated_at) to track when users are created and updated.

3. **Explained File Organization, Modules, and Packages:**
   - learned the differences between modules and packages.
   - learned file organization strategies for a project.

4. **Explained Absolute and Relative Import Paths:**
   - Clarified the difference between absolute and relative import paths in Python.

5. **Implemented BaseModel and User Class:**
   - Created a `BaseModel` class with common functionalities like `save`, `to_dict`, and `__str__`.
   - Implemented a `User` class inheriting from `BaseModel` with attributes like email, password, etc.

6. **Integration of JSON Serialization and Deserialization:**
   - Integrated JSON serialization and deserialization to save and load instances.
   - Implemented the `save` and `reload` methods to persist and restore instances from a JSON file.

7. **Implemented CRUD Commands in cmd Interface:**
   - Extended the cmd interface to handle CRUD (Create, Read, Update, Delete) operations.
   - Implemented methods to create, read, update, and delete users using a simple console interface.

8. **Testing and Verification:**
   - learned and implemented how to test the functionality of the `create` method and others in the cmd interface.
   - learned interactions and outputs to ensure proper functioning.

9. **Understanding and Discussing Various Code Snippets:**
   - Analyzed and explained code snippets related to datetime, JSON handling, and command-line interfaces.

10. **Explained `to_dict` and `__str__` Methods:**
    - learned the purpose and functionality of the `to_dict` and `__str__` methods in the `BaseModel` class.

11. **Implemented Class for Handling Custom Commands:**
    - Implemented a class (`HBNBCommand`) to handle custom commands like `show`, `all`, `destroy`, and `update` in the cmd interface.

12. **Explanation of Specific Code Sections:**
    - Explained specific code sections, such as the `reload` method and the dynamic creation of instances based on class names.

13. **Introduction to Testing and Verification Strategies:**
    - learned how to test and verify the correctness of implemented functionality, especially focusing on the `create` method.

14. **Incorporated Global Dictionary for Storing Instances:**
    - Used a global dictionary (`__objects`) to store instances, allowing easy access and manipulation in different methods.

15. **Explanation of `__init__` and `do_create` Methods:**
    - Explained the purpose of the `__init__` method in the `User` class and the `do_create` method in the cmd interface.

Throughout the session, we focused on practical implementations, explanations tailored to a beginner's understanding, and testing strategies to ensure the correctness of the implemented features.

**link to implementation:** [AirBnBV2](https://github.com/hunterxcobby/Airbnb_CloneV2)



## Day 72: January 09, 2024

**Today's Progress**: conditionals, data structure, functions, operators, variables, operators precedence

1. **Short-Circuiting in JavaScript:**
   - learned the concept of short-circuiting in JavaScript, understanding how certain operators like logical AND (`&&`), logical OR (`||`), nullish coalescing (`??`), and optional chaining (`?.`) evaluate expressions.

2. **Table of Operators and Precedence:**
   - Examined a table listing JavaScript operators from highest to lowest precedence, including notes on their associativity, individual operators, and usage examples.

3. **Control Flow and Error Handling:**
   - Covered basic control flow statements in JavaScript, particularly the block statement and its scoping effects. learned the use of `var`, `let`, and `const` for scoping.

4. **Conditional Statements:**
   - learned conditional statements in JavaScript, focusing on the `if...else` statement and its best practices. learned the importance of using block statements for better code structure.

5. **Switch Statement:**
   - learned the `switch` statement in JavaScript, explaining how it allows evaluating an expression and matching its value to various case labels. learned the use of `break` statements and provided an example.

6. **User Input Handling:**
   -  modifying code to handle user input by utilizing the `readline` module for a more interactive experience. Resolved issues related to using the `prompt` function and clarified the need for user input.

7. **Exception Handling Statements:**
   - Covered exception handling in JavaScript using the `throw` statement and `try...catch` statements. learned the use of the `finally` block and learned nesting `try...catch` statements.

8. **Utilizing Error Objects:**
   - Studied the utilization of `Error` objects for throwing and catching exceptions. Provided an example of creating and handling custom errors for more informative debugging.

9. **Code Review:**
   - Reviewed and refined code snippets for user input handling and exception handling, ensuring correct syntax and addressing issues related to the `prompt` function.


**link to notes:** [Js learning](https://github.com/hunterxcobby/JS-Lessons/tree/main/basics)



## Day 73: January 10, 2024

**Today's Progress**: Functions, Objects, constructers 

1. Clarified the concept of functions in programming, covering basic syntax, invocation, scope, and parameters.

2. learned functions versus methods, emphasizing their roles and distinctions.

3. learned the concept of objects in programming, explaining how they are a collection of related data and functionality.

4. learned object literals, showcasing their structure and common patterns for creating and accessing properties and methods.

5. Dived into more advanced object concepts, such as objects as object properties and bracket notation for property access.

6. Covered setting object members, including updating values, creating new members, and dynamically setting member names.

7. learned the significance of the "this" keyword in methods and how it refers to the current object.

8. learned constructors as a way to create reusable object blueprints, making it more efficient to create multiple objects with shared properties and methods.

9. discovered the ubiquity of objects in JavaScript, pointing out their use in built-in APIs and objects like String, Array, and Document.

10. Applied the acquired knowledge to complete practical tasks involving objects and their properties, including creating band and cat objects with specific requirements.


**link to notes:** [Js learning](https://github.com/hunterxcobby/JS-Lessons/tree/main/basics)


## Day 74: January 11, 2024

**Today's Progress**: Object, functions and scopes, operators, cmdlines, modules

1. **JavaScript Basics:**
   - learned the importance of JavaScript programming.
   - Covered how to run a JavaScript script.
   - learned the creation of variables and constants.
   - learned the differences between `var`, `const`, and `let`.
   - Covered various data types available in JavaScript.

2. **Control Flow in JavaScript:**
   - learned the use of `if` and `if...else` statements.
   - Covered the use of comments and assigning values to variables.
   - learned the use of `while` and `for` loops, as well as `break` and `continue` statements.

3. **Functions and Scope:**
   - learned what a function is and how to use functions in JavaScript.
   - learned functions that do not use a return statement.
   - learned the scope of variables in JavaScript.

4. **Operators and Data Manipulation:**
   - learned arithmetic operators and how to use them.
   - learned how to manipulate dictionaries in JavaScript.

5. **Modules and Importing Files:**
   - learned how to import a file in JavaScript using ES modules.

6. **Error Resolution:**
   - Addressed and resolved issues related to package installation and script execution.

7. **Command-Line Arguments:**
   - learned scripts that handle command-line arguments using `process.argv`.
   - Explained a script checking for the number and type of command-line arguments.

8. **Additional Queries:**
   - understanding and troubleshooting issues related to Node.js installation and script execution.

9. **Next Steps:**
   - Upcoming topics include more advanced JavaScript concepts, further exploration of ES modules, and addressing specific questions or topics of interest.

**link to notes:** [Js learning](https://github.com/hunterxcobby/JS-Lessons/tree/main/basics)



## Day 75: January 12, 2024

**Today's Progress**: SQLAlchemy, declarative mapping, creating schema, instance of mapped classes, sessions.

1. **SQL Joins:**
   - learned different types of joins in SQL, including inner joins, outer joins (left and right), and cross joins.
   - learned the concept of evaluation order in SQL joins, emphasizing the importance of understanding the sequence of joins in a query.
   
2. **Set Operations on Tables:**
   - Covered set operations in SQL, highlighting that joins are not equivalent to unions and learned union and minus operations on tables.
   - discovered the importance of having identical attributes in sets participating in set operations.

3. **Introduction to SQLAlchemy:**
   - Initiated the exploration of SQLAlchemy, focusing on the Object Relational Mapper (ORM).
   - learned the ORM's method of associating Python classes with database tables and instances of those classes with rows in the tables.
   - learned the SQLAlchemy version check and connecting to an SQLite in-memory database.

4. **Declarative Mapping in SQLAlchemy:**
   - learned how to declare a mapping between Python classes and database tables using the Declarative system in SQLAlchemy.
   - Defined a base class using `declarative_base()` and created a class (`User`) mapped to a table (`users`).
   - learned the importance of having a primary key in the mapped class.

5. **Creating a Schema in SQLAlchemy:**
   - Examined the process of creating a schema in SQLAlchemy, including the creation of table metadata and issuing CREATE TABLE statements using `MetaData.create_all()`.

6. **Creating an Instance of the Mapped Class:**
   - learned the instantiation of objects from a mapped class in SQLAlchemy, understanding the role of the `__init__` method.
   - learned the default values for attributes and how SQLAlchemy instrumentation works.

7. **Creating a Session in SQLAlchemy:**
   - learned the concept of a Session in SQLAlchemy, which serves as a workspace for interacting with the database.
   - learned the creation of a Session class and its association with an Engine.
   - learned the lifecycle patterns of a Session and when to create a new Session.

8. **Adding and Updating Objects in SQLAlchemy:**
   - implemented how to add and update objects in SQLAlchemy, including using `Session.add()` and `Session.add_all()`.
   - learned the concept of a flush and how SQLAlchemy manages the identity map.
   - Showed how to commit changes to the database using `Session.commit()`.

9. **Session Object States in SQLAlchemy:**
   - learned the different object states in SQLAlchemy: transient, pending, and persistent.
   - Highlighted the importance of understanding these states for effective interaction with the database.

10. **Improving Object Representation:**
    - Addressed the need to improve the representation of objects by enhancing the `__repr__` method in the `User` class.

11. **Future Steps:**
    - Considered the need for further exploration, including querying data, handling relationships between tables, and advanced topics in SQLAlchemy.


**link to notes:** [SQL Alchemy](https://github.com/hunterxcobby/DBMS_learning/tree/main/sql_alchemy)



## Day 76: January 13, 2024

**Today's Progress**: Introduction to django


1. Web Frameworks
2. MVT - (Model, Views, Template)
3. Virtual environments
4. Projects Vs Apps
5. HTTP response cycle

   
**link to notes:** [Django](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/django)



## Day 77: January 14, 2024

**Today's Progress**: Object Relational Mappers

1. Discussed various Python ORM implementations, including SQLAlchemy, Peewee, Django's ORM, Pony ORM, and SQLObject.

2. Highlighted key characteristics of SQLAlchemy, such as its balanced abstraction level and effectiveness in handling complex queries.

3. Introduced Peewee ORM, emphasizing its design philosophy of being "simpler, smaller, and more hackable" compared to SQLAlchemy.

4. Covered Django's ORM, a built-in module in the Django web framework, suitable for simple to medium-complexity database operations. Noted criticisms about its complexity for certain queries.

5. Introduced Pony ORM, an open-source Python ORM released under the Apache 2.0 license, providing an alternative for developers.

6. Mentioned SQLObject as a long-standing ORM with over 14 years of active open-source development, showcasing its stability and reliability.

7. Included Tortoise ORM as an open-source ORM implementation for Python, broadening the options available to developers.


**link to notes:** [ORM](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/21-object_relational_mappers)



## Day 78: January 15, 2024

**Today's Progress**: Python MySQL

1. **SQLAlchemy Overview:**
   - Discussed the importance and benefits of using Object-Relational Mappers (ORMs).
   - learned various Python ORM implementations, including SQLAlchemy, Peewee, Django ORM, PonyORM, and SQLObject.

2. **Introduction to MySQL in Python:**
   - Introduced MySQL Python, the MySQL driver for Python, including the _mysql wrapper library and the DB-API 2.0 module MySQLdb.
   - Covered the installation process of MySQLdb.

3. **Connecting to a MySQL Database:**
   - Demonstrated how to establish a connection to a MySQL database using the MySQLdb module.

4. **Getting a Cursor in MySQL Python:**
   - Explained the concept of a cursor and demonstrated how to create a cursor object.

5. **Executing MySQL Queries in Python:**
   - Illustrated the execution of various MySQL queries using the cursor's execute function.

6. **Obtaining Query Results:**
   - Explained methods for fetching query results, including fetching all-at-once and fetching one-at-a-time.

7. **Exceptions & Errors:**
   - Discussed error handling using try-except blocks and demonstrated handling MySQL errors.

8. **Clean Up:**
   - Covered the importance of closing cursors and database connections for proper cleanup.

9. **Parameterized Queries:**
   - Introduced the concept of parameterized queries to prevent SQL injection.
   - Showcased examples of creating and executing parameterized queries.

10. **Using Python Virtual Environment:**
    - Addressed the need for a Python virtual environment and discussed when and why to use one.

11. **Installing SQLAlchemy:**
    - Briefly explained the process of installing the SQLAlchemy library.

12. **Miscellaneous Questions:**
    - Tackled additional questions, including the purpose of the `freeze` command, filtering options in MySQLdb, printing from a table, and using format to create SQL queries.

**link to notes:** [Python MySQL](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/22-Python_MYSQL)



## Day 79: January 16, 2024

**Today's Progress**: SQLAlchemy Python && SQL

1. **Mapping and Declaring Classes:**
   - learned the process of declaring classes in SQLAlchemy using the Declarative system.
   - Created a base class and mapped a simple User class to a database table.

2. **Creating a Schema:**
   - Discussed the creation of a schema, including the use of the Declarative system, Table objects, and MetaData.
   - Demonstrated the process of creating tables and specifying column details.

3. **Creating an Instance of the Mapped Class:**
   - learned the process of creating instances of mapped classes.
   - Demonstrated the use of the constructor (`__init__()` method) and how SQLAlchemy's instrumentation works.

4. **Creating a Session:**
   - learned the role of the Session as the ORM's handle to the database.
   - Created a Session class and discussed its lifecycle patterns.
   - learned how to instantiate and configure a Session.

5. **Adding and Updating Objects:**
   - Discussed persisting objects to the database using the Session.
   - learned the process of adding and updating objects, including the use of `add()`, `add_all()`, and `commit()`.

6. **Rolling Back:**
   - learned the ability to roll back changes made within a transaction using `rollback()`.

7. **Querying:**
   - Introduced Query objects and demonstrated basic querying using `query()` and various filtering techniques.
   - Covered the generative nature of Query objects and their use in LIMIT, OFFSET, and ordering.

8. **Common Filter Operators:**
   - learned common filter operators such as `==`, `!=`, `like`, `ilike`, `in_`, `notin_`, `is_`, `isnot`, `and_`, `or_`, and `match`.


**link to notes:** [Python && SQL](https://github.com/hunterxcobby/DBMS_learning)


## Day 80: January 17, 2024

**Today's Progress**: SQLAlchemy Python && SQL

1. **Mock Peer Review for SQL Alchemy Code:**
   - SQL Alchemy code related to common filter operators, provided explanations, and discussed potential improvements.

2. **Code Review for Console Script:**
   - Fixed code for the (`console.py`) related to parsing command-line arguments, addressing syntax warnings, and ensuring proper functionality.

3. **Database Setup Scripts:**
   - Created SQL scripts (`setup_mysql_dev.sql` and `setup_mysql_test.sql`) to set up MySQL databases, users, and privileges for a project.

4. **File Storage Update:**
   - updated the `FileStorage` class in Python related to adding a `delete` method and modifying the `all` method.

5. **User Class Update:**
   - Updated the `User` class in Python, inheriting from `BaseModel` and `Base`, and added or replaced class attributes as per the provided requirements.

These tasks involved code review, SQL script creation, and Python class updates to enhance functionality and align with project specifications.

**link to project:** [AirBnB_v2](https://github.com/hunterxcobby/AirBnB_clone_v2)


## Day 81: January 18, 2024

**Today's Progress**: SQLAlchemy Python && SQL

1. **Syntax Warning Fixes:**
   - Identified and addressed syntax warnings in the `console.py` file, replacing `is` with `==` where appropriate.

2. **Error Handling in tearDown Method:**
   - Updated the `tearDown` method in the test files (`test_base_model.py`) to include specific exception handling instead of using a bare `except` statement.

3. **BaseModel Class Modification:**
   - Modified the `BaseModel` class to properly handle the conversion of `created_at` and `updated_at` attributes from string to datetime objects.

4. **Code Review and Suggestions:**
   - Reviewed your `console.py` code, provided comments, and suggested improvements.
   
5. **Bug Fix in `do_create` Method:**
   - Addressed a bug in the `do_create` method of `console.py` by ensuring proper handling of parameters and their evaluation.

6. **Additional Code Comments:**
   - Added comments to the modified code sections to provide clarity on the changes made.

7. **Review and Suggestions on Overall Progress:**
   - Discussed errors encountered, potential improvements, and provided guidance on debugging and refining the code.

8. **Ongoing Support and Clarifications:**
   - Addressed various specific issues and errors reported by you, offering guidance and assistance.
  
  **link to project:** [AirBnB_v2](https://github.com/hunterxcobby/AirBnB_clone_v2)


  
## Day 82: January 19, 2024

**Today's Progress**: Configuration Management , Puppet


1. **Configuration Management and Automation:**
   - learned the concept of configuration management in the context of server infrastructure.
   - Discussed the role of automation in server configuration management.
   - Introduced popular configuration management tools: Puppet, Ansible, Chef, and Salt.

2. **Benefits of Configuration Management for Servers:**
   - Discussed the benefits, including quick provisioning, recovery, avoiding snowflake servers, version control, and replicated environments.

3. **Overview of Configuration Management Tools:**
   - Discussed common features shared by configuration management tools.
   - Introduced features like Automation Framework, Idempotent Behavior, System Facts, Templating System, and Extensibility.

4. **Choosing a Configuration Management Tool:**
   - Considered factors like infrastructure complexity, learning curve, cost, advanced tooling, and community support when choosing a tool.
   - Provided an overview of Ansible, Puppet, and Chef.

5. **Overview of Popular Tools:**
   - Presented a quick comparison of Ansible, Puppet, and Chef, including their script language, infrastructure model, and terminology.

6. **Puppet Documentation Exploration:**
   - Started exploring Puppet documentation.

7. **Step-by-Step Puppet Tutorial:**
   - Guided through the initial steps of creating a Puppet project.
   - Demonstrated writing a simple manifest to install a package.

8. **Puppet Project: Creating a File:**
   - Created a step-by-step project to use Puppet to create a file with specific permissions, owner, group, and content.

9. **Puppet Project: Installing Flask:**
    - Created a Puppet manifest to install Flask from pip3 with a specific version.

10. **Progress Tracking:**
    - Regularly checked for understanding and provided explanations for each step.
    - Responded to user queries and adjusted the pace based on the user's feedback.

 **link to notes:** [Configuration Management](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0A-configuration_management)


## Day 83: January 20, 2024

**Today's Progress**: String Capitalization , Python
 
### Challenge: Capitalize Names

1. **Understand the Problem:**
   - The task is to capitalize the first letter of each word in a given full name.
   - The input is a string containing the full name.

2. **Input Format:**
   - A single line of input containing the full name.

3. **Output Format:**
   - Print the capitalized string.

4. **Approach:**
   - Split the full name into individual words.
   - Capitalize the first letter of each word.
   - Join the capitalized words back into a string.

5. **Pseudocode:**
   ```python
   def capitalize_name(name):
       # Split the name into words
       words = name.split()

       # Capitalize the first letter of each word
       capitalized_words = [word.capitalize() for word in words]

       # Join the capitalized words back into a string
       capitalized_name = ' '.join(capitalized_words)

       return capitalized_name

   # Sample Input
   full_name = "chris alan"

   # Output the capitalized name
   result = capitalize_name(full_name)
   print(result)
   ```

6. **Sample Input and Output:**
   - Sample Input: "chris alan"
   - Expected Output: "Chris Alan"

7. **Test the Function:**
   - Test the function with various inputs, including edge cases.

8. **Optimization:**
   - The provided solution is concise and covers the requirements.
   - No additional optimization is needed for this simple task.

9. **Documentation:**
   - Add comments or docstrings to explain the code.

10. **Finalization:**
    - Ensure the code is readable, well-documented, and provides the correct output.

**link to implementation:** [String Capitalization](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/15-cAPITALIZE)


## Day 84: January 21, 2024

**Today's Progress**: SSH (Secure Shell)

- learned; 

1. the concept of SSH (Secure Shell) as a secure protocol for connecting to Linux servers remotely.

2. how SSH works, emphasizing the client-server model and the use of SSH keys for authentication.

3. the process of generating SSH key pairs on a local machine, including considerations for key length.

4. the use of an SSH agent to avoid typing the passphrase repeatedly and forwarding SSH credentials for server-to-server authentication.

5. changing the default port that the SSH daemon runs on to enhance security.

6. methods of limiting users who can connect through SSH using directives like AllowUsers and AllowGroups.

7. disabling root login through SSH and encouraged the use of a dedicated user account with sudo privileges.

8. scenario where root access is allowed for specific commands, achieved by modifying the root user's authorized_keys file.

9. removing the passphrase from an RSA key.

10. connecting to a server using a private key, emphasizing the use of the `ssh` command with the `-i` option.

**link to notes:** [Secure Shell](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0B-ssh/SSH-Essentials)


## Day 85: January 22, 2024

**Today's Progress**: Web Servers, HTTP Requests, Nginx

1. **Setting Up Nginx Server Blocks:**
   - Created directory structure for multiple sites in `/var/www`.
   - Set ownership and permissions for web directories.
   - Created sample pages for each site.

2. **Configuring Nginx Server Blocks:**
   - Created server block files for each domain in `/etc/nginx/sites-available`.
   - Edited server block files to define root directories, server names, and basic configurations.
   - Enabled server blocks by creating symbolic links in `/etc/nginx/sites-enabled`.

3. **Server Configuration and Restart:**
   - Adjusted `server_names_hash_bucket_size` in `/etc/nginx/nginx.conf` to avoid hash bucket memory issues.
   - Tested Nginx configuration with `sudo nginx -t`.
   - Restarted Nginx to apply changes with `sudo systemctl restart nginx`.

4. **Local Hosts File Modification (Optional):**
   - Modified the local computer's hosts file for testing purposes by mapping domain names to the server's IP address.

5. **Introduction to Web Servers and Domain Names:**
   - Discussed the importance of having a domain name for a professional appearance and trust.
   - learned the concepts of internet domain, domain name, root domain, and subdomain.
   - discovered the need to buy a domain name from registrars and configure DNS records.

6. **HTTP Methods Overview:**
   - learned common HTTP methods: GET, HEAD, POST, PUT, DELETE, CONNECT, OPTIONS, TRACE.
   - Provided explanations and real-world analogies for each HTTP method.

7. **Detailed Exploration of HTTP Methods:**
   - learned the details of GET, HEAD, POST, PUT, DELETE, CONNECT, OPTIONS, TRACE methods.
   - Provided examples of HTTP requests and server responses for each method.

8. **Current Discussion: TRACE Method:**
   - learned the TRACE method, highlighting its purpose of echoing back HTTP requests for debugging.
   - read examples of TRACE requests and server responses.


**link to notes:** [Web Server](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0C-web_server)



## Day 86: January 23, 2024

**Today's Progress**: HTTP Requests

1. **Understanding Redirects:**
   - Explored the concept of redirects and their importance in web development.
   - Discussed different types of redirects, including 301 (Moved Permanently), 302 (Found or Moved Temporarily), 307 (Moved Temporarily), and Meta Refresh.
   - Insights into when to use each type of redirect based on specific scenarios.

2. **SEO Best Practices in Redirects:**
   - Emphasized the SEO best practices when implementing redirects, with a focus on using 301 redirects for permanent changes.
   - Addressed the impact of redirects on SEO, link equity, and search engine recognition.
   - Explained the complexity of site-wide domain changes and the considerations involved in SEO-friendly domain migration.

3. **Log File Locations:**
   - Responded to a query about the location of Nginx configuration files.
   - Learned common paths for the main Nginx configuration file (`nginx.conf`) on Linux (Ubuntu/Debian and CentOS/RHEL) and Windows systems.


**link to notes:** [Web Server](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0C-web_server)



## Day 87: January 24, 2024

**Today's Progress**: Webstack Debugging

1. **HTTP Methods:**
   - Explored various HTTP methods, including GET, POST, PUT, DELETE, CONNECT, OPTIONS, and TRACE.
   - Discussed the purpose and usage of each method in web development.

2. **Redirects:**
   - Explored the concept of redirects in web development.
   - Discussed common HTTP status codes for redirects, including 301 (Moved Permanently) and 302 (Found or Moved Temporarily).
   - Examined other redirect methods like 307 (Moved Temporarily) and Meta Refresh.

3. **SEO Best Practices:**
   - Discussed SEO best practices related to redirects, emphasizing the importance of using 301 redirects for permanent moves.
   - Highlighted the impact of redirects on search engine rankings and trust.

4. **Nginx Configuration:**
   - Explored Nginx configuration files and made adjustments to achieve specific redirection requirements.
   - Addressed issues related to duplicate location directives and the resulting "301 Moved Permanently" responses.

5. **Debugging Apache in Docker Container:**
   - Explored debugging tasks involving Apache running in a Docker container.
   - Investigated and resolved issues preventing the successful display of a "Hello Holberton" page.

6. **Miscellaneous Issues:**
   - Addressed errors related to Apache service start-up, including "apache.service not found" and Apache not starting due to port conflicts.
   - Investigated and resolved issues related to Nginx configuration causing "duplicate location" errors.

7. **File Transfer with SCP:**
   - Provided guidance on using `scp` to securely copy files between machines.

**link to notes:** [Web Server](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0C-web_server)



## Day 88: January 25, 2024

**Today's Progress**: Python Network


1. **URL and URI**: Discussed the concepts of Uniform Resource Locator (URL) and Uniform Resource Identifier (URI), including their syntax and components.

2. **"POST" Request Method**: Explored the POST request method in HTTP, its syntax, usage for submitting form data, and differences from the GET method.

3. **File Upload using multipart/form-data POST Request**: Covered file uploads in HTTP using the multipart/form-data POST request, including examples and relevant MIME types.

4. **"CONNECT" Request Method**: Introduced the CONNECT request method in HTTP for establishing proxy connections.

5. **Content Negotiation**: Explained content negotiation in HTTP, including Content-Type negotiation, language negotiation, and encoding negotiation.

6. **Persistent (or Keep-alive) Connections**: Discussed persistent connections in HTTP, their benefits, and relevant Apache server configuration directives.

7. **Range Download**: Briefly touched on the Accept-Ranges and Transfer-Encoding headers for range downloads in HTTP.

8. **Cache Control**: Covered cache control in HTTP, including the Cache-Control and Pragma headers for controlling caching behavior.

9. **HTTP Cookies**: Introduced HTTP cookies, including their purpose, Set-Cookie and Cookie headers, and examples in various server-side applications like PHP, Node.js, Python, and Ruby on Rails.

10. **Lifetime of a Cookie**: Discussed the lifetime of cookies, including permanent cookies and session cookies, along with examples.

11. **Restrict Access to Cookies**: Explored methods to restrict access to cookies using the Secure and HttpOnly attributes, with examples.

12. **Where Cookies are Sent**: Defined the scope of cookies using the Domain and Path attributes, with examples.


**link to notes:** [Python Network](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/23-python-network_0/0-HTTP)



## Day 89: January 26, 2024

**Today's Progress**: Python Network 

1. **Introduction to urllib.request**: Explored the `urllib.request` module, which provides a simple interface for fetching URLs.

2. **Fetching URLs**: Discussed the `urlopen` function for fetching URLs and storing responses in temporary locations using `shutil.copyfileobj` and `tempfile.NamedTemporaryFile`.

3. **Understanding HTTP requests and responses**: Explored HTTP requests and responses, mirroring them with `Request` and `Response` objects.

4. **Data Handling**: Covered sending data to URLs using POST requests and encoding data using `urlencode` from `urllib.parse`.

5. **Headers**: Explored adding headers to HTTP requests to mimic browser behavior using the `headers` argument in `urllib.request.Request`.

6. **Handling Exceptions**: Discussed error handling with `URLError` and `HTTPError` exceptions, and how to handle them using `try-except` blocks.

7. **Error Codes**: Reviewed HTTP error codes and their meanings, along with how to handle them in Python.

8. **Wrapping it Up**: Summarized approaches to handle `URLError` and `HTTPError` exceptions.

9. **info and geturl**: Learned about the `info` and `geturl` methods of response objects, providing information about the fetched page and the actual URL.

10. **Openers and Handlers**: Explored customizing URL openers and handlers for handling specific situations like proxies, authentication, and redirects.

11. **Basic Authentication**: Covered handling basic authentication using `HTTPBasicAuthHandler` and password managers.

12. **Proxies**: Discussed working with proxies and disabling proxy detection using `ProxyHandler`.

13. **Sockets and Layers**: Explored the layered architecture of Python's web resource fetching process, including setting socket timeouts.

**link to notes:** [Python Network](https://github.com/hunterxcobby/Python-Projects/tree/main/lessons/exercises/24-python-network_1/0-URLlib)


## Day 90: January 27, 2024

**Today's Progress**: List Challenge on HackerRank, Python

1. **Read Input:**
   - Read the number of commands `n` from input.
   
2. **Initialize List:**
   - Initialize an empty list `lst`.

3. **Parse Commands:**
   - Loop `n` times to read and parse each command.
   - Split each command into words using the `split()` method.
   - The first word of each command indicates the operation to perform.

4. **Perform Operations:**
   - For each command, determine the operation to perform based on the first word.
   - Use conditional statements (`if`, `elif`, `else`) to handle different types of operations:
     - If the operation is 'insert', use `insert()` method to insert the specified element at the specified index.
     - If the operation is 'print', use `print()` method to print the current state of the list.
     - If the operation is 'remove', use `remove()` method to remove the specified element from the list.
     - If the operation is 'append', use `append()` method to append the specified element to the end of the list.
     - If the operation is 'sort', use `sort()` method to sort the list.
     - If the operation is 'pop', use `pop()` method to remove and return the last element of the list.
     - If the operation is 'reverse', use `reverse()` method to reverse the elements of the list.

5. **Handle Errors:**
   - Use `try-except` blocks to handle errors that may occur during list operations.
   - For example, handle `ValueError` when converting input arguments to integers.
   - Print error messages or handle errors gracefully as needed.

6. **Output:**
   - After processing all commands, the final state of the list should be printed as the output.

7. **Test and Debug:**
   - Test the program with sample inputs and edge cases to ensure correctness.
   - Debug any issues or errors encountered during testing.

8. **Optimization (Optional):**
   - Review the code for potential optimizations or improvements in terms of readability, efficiency, or functionality.

**link to solution:** [Lists](https://github.com/hunterxcobby/Python-Challenges/tree/main/01-HackerRank/16-Lists)


## Day 91: January 28, 2024

**Today's Progress**:Django, Python

- Created a django project
- create blog and pages apps
- routed their url to a simple html site

**link to solution:** [Lists](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/django)


## Day 92: January 29, 2024

**Today's Progress**: Load Balancer, HAProxy

1. **Introduction to HAProxy**:
   - an overview of HAProxy as a TCP/HTTP Load Balancer and proxying solution used to distribute workload across multiple servers.

2. **HAProxy Terminology**:
   - important terms like Access Control List (ACL), backend, and frontend in relation to load balancing.

3. **Types of Load Balancing**:
   - Explored different types of load balancing, including no load balancing, layer 4 load balancing, and layer 7 load balancing, along with their respective configurations.

4. **Load Balancing Algorithms**:
   - commonly used load balancing algorithms in HAProxy, such as roundrobin, leastconn, and source, along with sticky sessions.

5. **Health Check**:
   - Covered HAProxy's health check mechanism to determine the availability of backend servers and how it ensures high availability.

6. **High Availability Setup**:
   - Explored the concept of high availability (HA) setups, which prevent single points of failure, especially in load balancer configurations.

7. **HTTP Headers**:
   - Defined HTTP headers, including request headers, response headers, general headers, and entity headers, and their roles in HTTP communication.

8. **Troubleshooting Nginx and Apache**:
   - diagnosing and resolving issues related to Nginx and Apache web servers, including port conflicts and configuration errors.

9. **Configuring HAProxy**:
   - configuring HAProxy on a server to distribute traffic to multiple backend servers using roundrobin algorithm.

10. **SSH Connection Troubleshooting**:
    - troubleshooting SSH connection issues, including checking for routing problems and specifying custom SSH port numbers.


**link to notes:** [Load Balancers](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x0F-load_balancer)



## Day 93: January 30, 2024

**Today's Progress**: Python Network

1. **Shell Scripting Tasks:**
    - Successfully implemented Bash scripts to handle tasks involving cURL requests, including sending requests to specific URLs, managing responses, and addressing syntax errors.
    - Identified and resolved issues related to script syntax, parameter passing, and error handling, ensuring the scripts executed as intended.

2. **Python Scripting Tasks:**
    - Completed Python scripting tasks, focusing on sending requests to URLs, processing responses, and utilizing libraries like `urllib` and `requests` for HTTP interactions.
    - Developed Python scripts to interact with the GitHub API, retrieve commit information from repositories, and format the output according to task requirements.

3. **Error Handling and Debugging:**
    - Encountered errors such as HTTP status code errors and invalid JSON responses during scripting tasks, and implemented error handling mechanisms to manage these issues effectively.
    - Debugged scripts to resolve errors and ensure they functioned correctly under different scenarios, improving overall robustness and reliability.

4. **Code Optimization and Efficiency:**
    - Optimized script code to enhance readability, efficiency, and adherence to task specifications, focusing on improving performance and reducing complexity.
    - Implemented strategies to streamline code execution, enhance script performance, and maintain code quality throughout the development process.

5. **Task Completion and Testing:**
    - Successfully completed assigned tasks by writing scripts that met specified requirements and produced expected outputs, ensuring adherence to task instructions.
    - Conducted thorough testing of scripts in designated sandboxes to validate functionality and correctness, making necessary adjustments to achieve desired results.

6. **Documentation and Reporting:**
    - Maintained detailed documentation of progress, solutions, and explanations for each task, ensuring clear understanding of concepts, code implementations, and troubleshooting steps.
    - Documented insights gained from solving various scripting challenges, facilitating learning and knowledge retention for future reference.

**link to :** [Python Network](https://github.com/hunterxcobby/alx-higher_level_programming)



## Day 94: January 31, 2024

**Today's Progress**: Number Guessing Game

1. **Task Definition:**
   - Defined the task to create a number guessing game using `while` loops, `break`, and `continue` statements.
   - Set the goal of allowing users to guess a randomly generated number between 1 and 100.
   
2. **Environment Setup:**
   - Included necessary header files: `<stdio.h>`, `<stdlib.h>`, and `<time.h>`.
   - Created the `number_guessing.c` file in the "Tasks" directory to contain the program.

3. **Random Number Generation:**
   - Used `srand(time(NULL))` to seed the random number generator with the current time for randomness.
   - Generated a random number between 1 and 100 using `rand() % 100 + 1` and stored it as the target number.

4. **Variables Initialization:**
   - Declared variables `userGuess` to store user input and `attempts` to count the number of attempts.

5. **Game Implementation:**
   - Utilized a `while` loop with `while (1)` for an indefinite loop until the correct guess is made.
   - Prompted users to input their guess using `printf`.
   - Checked the validity of user input using `scanf` and handled invalid input by clearing the input buffer and prompting users to enter a numeric value again.
   - Incremented the `attempts` counter for each guess.

6. **Guess Evaluation:**
   - Implemented a check to compare the user's guess with the target number using `if` statements.
   - Provided feedback to users indicating whether their guess was too high or too low using `printf`.
   - Terminated the loop and displayed a congratulatory message when the correct guess was made using `break`.

7. **Code Refinement:**
   - Simplified the feedback message to improve clarity and readability by replacing the ternary operator with an `if-else` statement.

8. **Documentation:**
   - Documented each step and provided clear explanations for beginners to understand.
   - Ensured readability and maintainability by adding comments throughout the code.

9. **Testing:**
   - Conducted testing to ensure the program functions as expected, allowing users to successfully play the number guessing game.
   
10. **Revision and Review:**
    - Reviewed the code to ensure accuracy, readability, and adherence to task requirements.
    - Made necessary revisions to improve clarity and correctness based on feedback and review.

11. **Completion:**
    - Completed the task successfully, meeting all requirements and ensuring the code is beginner-friendly and easy to understand.
   

**link to task:** [Number Guessing Game](https://github.com/hunterxcobby/CWC-Learning/tree/main/c_programming/number_guessing-game)



## Day 95: February 01, 2024

**Today's Progress**: AirBnB_clone-Deploy_static

1. **Fabric Introduction:**
   - Discussed what Fabric is and its role in deployment processes.

2. **Deploying Code to a Server Easily:**
   - Explored the process of deploying code to a server efficiently using Fabric.
   - Discussed the steps involved, including executing Fabric commands locally and remotely, and transferring files with Fabric.

3. **Understanding TGZ Archives:**
   - Defined a TGZ archive and its purpose in software distribution.
   - Explored how TGZ archives are used to package and compress files for easier distribution and deployment.

4. **Executing Fabric Commands Locally:**
   - Discussed how to execute Fabric commands locally using the Fabric library in Python.
   - Explored the steps involved in running Fabric commands on the local machine.

5. **Executing Fabric Commands Remotely:**
   - Explored the process of executing Fabric commands remotely on a target server.
   - Discussed how Fabric simplifies remote command execution and management.

6. **Transferring Files with Fabric:**
   - Explored how to transfer files between the local machine and remote servers using Fabric.
   - Discussed the methods available in Fabric for transferring files efficiently.

7. **Managing Nginx Configuration:**
   - Explored the basics of managing Nginx configuration files.
   - Discussed how to modify Nginx configuration settings for various purposes.

8. **Difference Between `root` and `alias` in Nginx Configuration:**
   - Discussed the differences between the `root` and `alias` directives in Nginx configuration files.
   - Explored how each directive handles file locations based on URI requests.
  
  
**link to notes:** [AirBnB_clone-Deploy_static](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x03.AirBnB_clone-Deploy_static)



## Day 96: February 02, 2024

**Today's Progress**: HTTPS, SSL

1. **Understanding HTTPS and SSL:**
   - Explained the concepts of HTTPS and SSL in simple terms using real-life analogies.
   - Discussed the purpose and benefits of SSL certificates, including encryption, authentication, trust, and PCI compliance.
   - Explored the disadvantages of SSL, such as cost and performance considerations.

2. **Deployment Tasks:**
   - configuring domain zones and subdomains for load balancing using Bash scripting.
   - Created SSL certificates using Certbot and configured HAproxy to accept encrypted traffic.
   - Troubleshooted errors related to Apache configuration and port usage conflicts.

3. **Programming Concepts:**
   - Discussed the Feynman learning technique and applied it to explain programming concepts in step-by-step and analogy-based approaches.
   - Clarified concepts related to round-robin DNS, HTTP, and HTTPS.

4. **Hands-on Practice:**
   - Engaged in practical exercises to apply theoretical knowledge, such as configuring domain zones, generating SSL certificates, and troubleshooting deployment issues.
   - Provided guidance on using commands, editing configuration files, and resolving errors in a Linux environment.


**link to notes:** [HTTPS & SSL](https://github.com/hunterxcobby/system-devops_learning/tree/main/shell_scripting/0x10-HTTPS_SSL)



## Day 97: February 03, 2024

**Today's Progress**: HTTPS, SSL / SSL termination

1. **Initial Setup and Certificate Generation:**
   - Explored the process of setting up Certbot for certificate generation.
   - Generated SSL/TLS certificates for the domain "www.hunterxcobby.tech" using Certbot.

2. **HAProxy Configuration for SSL/TLS Termination:**
   - Reviewed the HAProxy configuration for SSL/TLS termination.
   - Updated the HAProxy configuration file (`haproxy.cfg`) to include SSL/TLS termination.
   - Explored options for binding SSL certificate files (`fullchain.pem` and `privkey.pem`) to the HAProxy configuration.
   - Modified the HAProxy configuration to bind the SSL certificate and private key files.

3. **Troubleshooting and Error Handling:**
   - Addressed errors encountered during HAProxy configuration, such as incorrect file paths and SSL certificate loading issues.
   - Provided guidance on locating SSL certificate files and understanding their contents.

4. **Final Configuration:**
   - Updated the HAProxy configuration to correctly bind the SSL certificate (`fullchain.pem`) and private key (`privkey.pem`).
   - Ensured that the HAProxy configuration is correctly set up for SSL/TLS termination on port 443.

5. **Summary and Next Steps:**
   - Reviewed the steps taken to configure HAProxy for SSL/TLS termination.
   - Provided guidance on next steps for managing SSL/TLS certificates and renewals using Certbot.

**link to project:** [HTTPS & SSL task](https://github.com/hunterxcobby/alx-system_engineering-devops/tree/master/0x10-https_ssl)



## Day 98: February 04, 2024

**Today's Progress**:  AirBnB clone - Deploy static

1. **SSL Certificate Configuration**:
   - We reviewed how to configure SSL certificates in HAProxy.
   - Discussed different configurations for binding SSL certificates, including paths and file formats.

2. **Troubleshooting SSL Errors**:
   - Addressed various errors encountered during SSL certificate configuration in HAProxy.
   - Analyzed error messages and suggested potential solutions.

3. **Fabric Script for Deployment**:
   - Discussed requirements for a Fabric script to deploy archives to web servers.
   - Outlined steps for creating the `do_deploy` function according to the provided specifications.

4. **Fabric Script Development**:
   - Developed a pseudocode representation of the `do_deploy` function.
   - Included steps to check archive existence, upload, uncompress, and manage symbolic links.

5. **Testing and Verification**:
   - Provided a command to test the Fabric script for deployment.
   - Emphasized the importance of verifying the deployment's success after running the script.

(**link to notes:** [AirBnB_clone-Deploy_static](https://github.com/hunterxcobby/AirBnB_clone_v2/)



## Day 99: February 05, 2024

**Today's Progress**:  Search Alogrithms

1. **Space Complexity**:
   - Discussed the concept of space complexity, distinguishing between auxiliary space and space complexity.
   - Explained space complexity using real-life analogies and examples, such as moving into an apartment and sorting algorithms' space requirements.
   - Reviewed example codes in C and Python to illustrate space complexity in recursive and non-recursive functions.

2. **Search Algorithms**:
   - Defined search algorithms as methods used to locate specific items within a collection of data.
   - Explained linear search as a simple search algorithm that sequentially checks each element in a dataset until a match is found.
   - Illustrated linear search with real-life analogies and provided example code in C.
   - Introduced binary search as an efficient search algorithm for sorted datasets, dividing the search interval in half with each iteration.
   - Discussed when to use linear search versus binary search based on the characteristics of the dataset and the efficiency requirements.
   - Provided example code in C for binary search and explained its implementation.

3. **Best Search Algorithms for Different Scenarios**:
   - Analyzed various search algorithms (linear search, binary search, hash table, interpolation search, exponential search, jump search) based on their suitability for different scenarios.
   - Discussed factors influencing the choice of the best search algorithm, including dataset size, sorting status, frequency of searches, and available resources.
   - Highlighted the importance of understanding trade-offs between time complexity, space complexity, and implementation complexity when selecting the appropriate search algorithm.


**link to notes:** [Search Algorithms](https://github.com/hunterxcobby/C-Projects/tree/master/lessons/solutions/0x1E-search_algorithms)



## Day 100: February 06, 2024

**Today's Progress**:  Django assignment && Importation Website

1. **Set Up Django Project**:
   - Discussed the task of setting up a Django project named "BlogAPI" and configuring necessary project settings.

2. **Create Models**:
   - Designed Django models for blog posts and comments, outlining their fields and purpose.

3. **Create Serializer Classes**:
   - Discussed the creation of serializer classes using Django REST Framework to serialize/deserialize data between Django models and JSON format for API endpoints.

4. **Create Views**:
   - Implemented views for endpoints such as retrieving a list of blog posts, retrieving a specific blog post by ID, adding a new blog post, editing an existing blog post, and deleting a blog post.

5. **Define URL Patterns**:
   - Outlined the process of mapping each view to a URL pattern in the Django project's URL configuration.

6. **Test Endpoints**:
   - Discussed testing endpoints using tools like Postman or curl to ensure they function as expected.

7. **Resolve Import Error with rest_framework**:
   - Provided steps to resolve import errors with `rest_framework`, including installing Django REST Framework, checking installed packages, ensuring correct Django settings, and rebuilding environment if using Docker.

**link to TASK:** [Django assignment](https://github.com/hunterxcobby/WEB-DEV_learning/tree/main/django-2)
