
0x1D. C - Binary trees
Project Overview
This is a group project in the field of algorithms and data structures, assigned to be completed by teams of two people. The project is led by Alexandre Gautier, and your team consists of Yusuf Yahaya. The project involves working with binary trees, focusing on concepts such as tree traversal, binary search trees, and related data structures.

Project Details
Project Start: November 27, 2023, 5:00 AM
Project End: December 1, 2023, 5:00 AM
Checker Release: November 28, 2023, 5:00 AM
Auto Review: An automated review will be launched at the deadline.
Learning Objectives
By the end of this project, you are expected to understand and explain the following concepts without external assistance:

What is a binary tree?
The difference between a binary tree and a Binary Search Tree.
Time complexity compared to linked lists.
Depth, height, and size of a binary tree.
Different traversal methods for a binary tree.
Complete, full, perfect, and balanced binary trees.
Copyright - Plagiarism
Plagiarism is strictly prohibited. You are required to come up with solutions independently. Publishing any content of this project is not allowed and may result in removal from the program.

Requirements
General
Editors: vi, vim, emacs
Compilation: Ubuntu 20.04 LTS, using gcc with the options -Wall -Werror -Wextra -pedantic -std=gnu89
Files: All files should end with a new line.
README.md: A mandatory file at the root of the project folder.
Code Style: Your code should follow the Betty style, checked using betty-style.pl and betty-doc.pl.
Global Variables: Not allowed.
Functions per File: No more than 5 functions per file.
Standard Library: You are allowed to use the standard library.
Header File: Prototypes of all functions should be included in a header file named binary_trees.h.
Header Files: Include guarded.
GitHub: One project repository per group. Cloning/forking a repository with the same name before the second deadline may result in a 0% score.
Data Structures
Please use the following data structures and types for binary trees. Include them in your header file:

Basic Binary Tree

c
Copy code
struct binary_tree_s {
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
Binary Search Tree

c
Copy code
typedef struct binary_tree_s bst_t;
AVL Tree

c
Copy code
typedef struct binary_tree_s avl_t;
Max Binary Heap

c
Copy code
typedef struct binary_tree_s heap_t;
Print Function
A print function is provided for visualization purposes. It should not be pushed to the repository and may not be used during the correction.

Compilation and Testing
Editors: vi, vim, emacs
Compilation: Use gcc on Ubuntu 20.04 LTS with the options -Wall -Werror -Wextra -pedantic -std=gnu89.
Main Files: Examples of main.c files are provided. You can use them for testing, but it's not mandatory to push them to your repository. The correction will use its own main.c files.
Task Specifics
Tasks 0 to 23 involve working with simple binary trees. They are not Binary Search Trees (BSTs), so they don't follow any specific rule.

Note
Please adhere to the project requirements and guidelines to ensure a smooth evaluation process. Good luck with your project!
