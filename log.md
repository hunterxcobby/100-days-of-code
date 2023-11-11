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


## Day 12: November 10, 2023 


**Today's Progress**:  Conditonals and Loops- Sum of Digits of a Five Digit Number , C language

**Thoughts:**: 


**Link to work:** [Condtionals and loops](https://github.com/hunterxcobby/C-Solutions/tree/main/1-HackerRank/0x08-Conditionals_and_loops)
