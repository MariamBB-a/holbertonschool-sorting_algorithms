                                            This is a joint project between / Mariam Almaleki / and / Reem Alyamani /

                                                          C - Sorting algorithms & Big O Notation
____________________________________________________________________________________________________________________________________________________

                                                                     # TABLE OF CONTENTS #
                                                            # Time Complexity (Big-O Notation)
                                                            # Common Types of Big-O Time Complexities
                                                            # Project Requirements
                                                            # GitHub Repository Rules
                                                            # Files in This Project


-----------------------------------------------------------------------------------------------------------------------------------

# Time Complexity (Big-O Notation)

## What is Time Complexity?

**Time Complexity** is a way to describe how long an algorithm takes to run as the size of the input increases.

Instead of measuring time in seconds, we measure **how fast the number of operations grows** with respect to the input size `n`.

This is done using **Big-O Notation**.

---

## Why Big-O Notation?

Big-O helps us:
- Compare algorithms
- Predict performance for large inputs
- Write efficient and scalable code
- Focus on algorithm efficiency, not hardware speed


---

##  Common Types of Big-O Time Complexities:

#1# ¢ (1) - Constant Time
- Time does not depend on input size
- Always takes the same amount of time

#2# O(log n) -  Logarithmic Time
- Input is cut in half each step

#3# O(n) -  Linear Time
- Time grows directly with input size

#4# O(n log n) -  Linearithmic Time
- Combination of linear and logarithmic
- Common in efficient sorting

#5# O(nÂ²) - Quadratic Time
- Nested loops
- Slow for large inputs

#6# O(2n)  Exponential Time
- Work doubles with each new input
- Very slow

#7# O(n!) - Factorial Time
- Tries all possible combinations
- Very slow
_________________________________________________________________________________________________________

## Requirements:

### General
- Allowed editors: `vi`, `vim`, `emacs`
- All files are compiled on **Ubuntu 20.04 LTS**
- All files must end with a **new line**
- A `README.md` file at the root of the project is **mandatory**
- Code must follow the **Betty style**
- Checked using `betty-style.pl` and `betty-doc.pl`
- **Global variables are not allowed**
- No more than **5 functions per file**
- The **standard library is forbidden**
- Functions like `printf`, `puts`, etc. are not allowed
- Provided `main.c` files are **for testing only**
- Do **not** push them to the repository
- We will use our **own `main.c` files** during grading
- All function prototypes must be declared in `sort.h`
- All header files must be **include guarded**
- A list or array does **not** need to be sorted if its size is less than 2

----------------------------------------------------------------------------------------------

## GitHub Repository Rules:

One repository shared 
- Repository name: holbertonschool-sorting_algorithms

----------------------------------------------------------------------------------------------
## Files in This Project:
1- README.md - Project documentation
2- sort.h  - Header file with all prototypes 
3- 0-O - contains the Big-O time complexities of the Bubble Sort algorithm for first file - 0-bubble_sort.c
4- 1-O - contains the Big O time complexities of the Insertion Sort algorithm for a doubly linked for second file - 1-insertion_sort_list.c
----------------------------------------------------------------------------------------------


