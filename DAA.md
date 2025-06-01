1. Generic way of describing an algorithm without using any programming language-related notations - [Pseudocode] 
2. Characteristic of an algorithm indicates that the actions to be carried out must be rigorously and unambiguously specified - [Definiteness] 
3. Indicates the location of a variable relative to the first element in an array - [Index] 
4. General approach by which a variety of problems from different areas of computing can be solved algorithmicly - [Algorithm design techniques] 
5. Pertains to a common pseudocode notation that performs a loop that has a condition at the end - [Repeat-Until] 
6. How many phases does the design and analysis of algorithm contain - [Five] 
7. Implies that the solution per problem may vary because of the different algorithms that can be used in solving - [Algorithm Design Technique]  
8. Straightforward approach to solve a problem - [Brute Force] 
9. Pertains to the part of an algorithm that involves the determination of the computational complexity - [Analysis] 
10. Used to chain the data to be processed in a linked list - [Link] 
11. set of finite and detailed step-by-step instructions performed to complete specific tasks - [Algorithm]
12. data structures that allows programmers to create new place automatically to store data - [Linked List]
13. part of algorithm that involves math process - [Design]
14. finite set of elements and a finite set set of direct lines called branches - [Tree]
15. number of branches associated with a node - [Degree]
16. describes doubly-linked list - [where each node except for first and last contains pointers to both its successor and ancestor]
17. NOT one of common data structure used in designing and analyzing algo - [Numerical DS]
18. NOT a phase in algo design - [Analyzing the linear DS]
19. CORRECT about general tree - [tree in which each node can have unli outdegree]
20. NOT a type of problem encountered in DAA - [Linear Data Problem]
21.definiteness of an algo - [steps in the algo must be precisely defined]
22. NOT a quality to consider in algo analysis - [Interoperability]
23. describes circularly linkedlist - [You know this..]
24. text string - [comprise letters, numbers, and special chars]
25. root of a tree - [first node of a tree provided that the tree is not empty]
26. pertains to numerical problem - [involves math objects which are continuous]
27. describes an algo - [set of finite and detailed steps performed to complete a specific task]
28. describes the height of a tree - [level of the leaf from the longest path from the root + 1]
29.NOT considered a problem in DAA - [Undirected linked problems]
30. string processing problem - [deals with non numerical data]

# MIDTERM
1. performed n amount of times - [Linear]
2. Running complex programs is difficult compared to running simple programs - [Quality of the program implementing the algo]
3. how many parts does recursion have - [2]
4. algorithm may run faster in one machine but not in another - [Computer's Speed]
5. amount o memory used to store all the VARIABLES and CONSTANTS - [Data Space]
6. memory used to stotr s COMPILED VERSION - [Instruction Space]
7. operation takes the same amt of time no matter howm uch data is being dealt with - [Constant]
8. final step in substi  -[Solve constants]
9. visual representation - [Recursion Tree]
10. simplest, smallest instance of the problem - [Base Case]
11. second step in subsi - [Verify by math induction]
12. decomposes a larger instance of the problem into one or more smaller - [ Space Complexity]
13. amount of computer memory required by an algorithm - [Space complexity]
14. AKA guess n check - [Substi]
15. first step in substi - [guess the form]
16. best describe constant space complexity - [requires fixed amount of space for all values]
17. recursive fn - [function that repeatedly calculates smaller part]
18. n/2 mean - [size of subproblem]
19. highest time efficiency - [ Factorial - Exponential - Polynomial - Quadratic]
20. Cop means - [amount of computer time req for a single operation in each line]
21. linear time complexity - [time execution is directly proportional to the input size]
22. C(n) means - [amount of comp time required by each operation for all its repetitions]
23. T(n) - [amount of computer time required by each operation]
24. highest time eff - [ Factorial - Exponential - Polynomial - Quadratic]
25. constant time complex - [fixed amount of time for all input]
26. lowest time eff - [Log]


# PREFI
1. sorting algorithm that choose es the smallest element in an unsorted portion - [Selection]
2. find minimum matches in which the time of completion or cost of making all act by the number is minimized - [Hungarian]
3. referred to as linear search - [Sequential Search]
4. path that begins and ends at the same vertex - [Hamiltonian circuit]
5. process of finding the exact copy of patterns - [String matching]
6. AKA Matrix Reduction method - [Hungarian Method]
7. essentially generates a list of potential solutions - [Exhaustive Search]
8. goal is to find the least expensive or shortest way to visit throguh a given set of cities - [TSP]
9. AKA proff by exhaustion - [Brute Force]
10. in assignment problem, how many tasiks are assigned to each entity - [1]
11. compares the adjacent objects - [Bubble Sort]
12. examines a series of data objects one by one - [Sequential Search]
13. requires pairing of people to execute jobs to minimize - [Assignment Problem]
14. Arranges the items in a given list in ascending or descending - [Sorting]
15. method of mathematical proof in which the statement to be proved is split into a finite num of cases - [Brute Force Algo]
16. NOT TRUE about Brute Force - [a path that begins and ends at the same vertex]
17. first step in MINIMZATION using HUNGARIAN - [Identify the lowest value in each row]
18. NOT a rule in TSP - [Align the pattern at the beginning of the text]
19. advantage of Brute Force - [yields standard algorithms for graph traversal problems]
20. DOES NOT belong to the group - [Assignment Problem]
21. MAXIMIZATION , should be done next after identifying the highest value in each row - [Subtract each row value from each of the highest values]
22. MAXIMIZATION, should be done next after selecting the lowest entry in each row - [Subtract the lowest entry from every entry in that column]
23. DOES NOT belong to the group - [TSP]
24. second step of TSP - [List all the Hamilton Circuits with the chosen reference point]
25. third step of the TSP - [determine the cost or distance associated with each of these Hamilton circuits]
26. MINMIZATION, should be done next after selecting the lowest entry in each column - [ Select the lowest entry from every entry in that col]
27. first step of Brute Force String Matching - [Aligh the pattern at the beginning of the text]
28. NOT a rule of Brute Force String Matching - [Select the smallest element among all the uncovered elements]
29. first step of TSP - [Choose a ref point or a vertex where you want to start]
30. MAXIMIZATION, comes first in solving it - [Identify the highest value in each row]

# FINALS
### Divide and Conquer
    - general algorithm design technique that solves problem by dividing it into several smaller subproblems of the same type

    Importance of DNC 
    - Solving difficult problems
    - Algorithm efficiency 
    - Parallelism
    - Memory Access

### Merge Sort
type of sorting algo that repeatedly divides the data in half, sorts each half separately, and combines the sorted halves into one sorted array

### Quick Sort
type of sorting algo in which the main idea is to partition the array into 2 regions

### Binary Search
type of sorting algo that is used to locate an element in an ordered array. It is advisable to use it whenever the list starts to become larger

STEPS
1. Divide the array into 2 sub arrays about half as large
2. Divide (Solve) the sub-array by determining whether the target is in that sub-array
3. Obtain the solution to the array from the solution to the sub-array


### Binary Tree
type of tree DS in which no node can have more than 2 subtrees.

### Binary Tree Traversal
requires that each node of the tree be processed once and only once 

#### Depth-first Traversal
where the processing proceeds along a path from the root through one child to the most distant descendant of that first child before processing second child

PREORDER TRAVERSAL - root is visited first and successively moving to the left subtree until a leaf is reached.
INORDER TRAVERSAL - left node is visited first and subsequently visits the parent of that node then go to the child on the right
POSTORDER TRAVERSAL - the lestmost leaf is visited first then going up to the parent and down to the second leftmost leaf in the same branch

#### Breadth-first Traversal
where processing proceeds horizontally from the root to all of its children and so forth until all nodes have been processed.