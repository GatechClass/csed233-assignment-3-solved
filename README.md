# csed233-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSED233 Assignment #3 Solved](https://mantutor.com/product/csed233-programming-assignment-3-solved-2/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114097&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED233  Assignment #3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
○ Any submission using the containers in STL will be disregarded

File(s) you need to submit:

● Files you need to submit. (Do not change the filename.)

○ pa3.cpp

○ sort.cpp and sort.h

○ tree.cpp and tree.h

○ bst.cpp and bst.h

○ avl.cpp and avl.h

○ open_hash_function.cpp and open_hash_function.h

○ open_hash_table.cpp and open_hash_table.h

○ closed_hash_function.cpp and closed_hash_function.h

○ closed_hash_table.cpp and closed_hash_table.h

Any questions? Please use PLMS – Q&amp;A board.

1. Bubble Sort (2 pts)

a. Implement a function that sorts a given array using the Bubble Sort algorithm. (k: iteration, A[ ]: array) On path k, the k-th lowest key rises to k-th position. Iteratively swap the adjacent items if the below item has a lower key value. If there were no swap in the current iteration, the array is sorted. You can modify sort.cpp and sort.h files for this problem.

b. Input &amp; Output

Input: A sequence of commands

– (‘insertion’,integer): insert integer into the array (there will be no duplicated integers).

– (‘bubbleSort’,NULL): sort the array using the Bubble Sort algorithm.

Output:

– Print every value in the array whenever the k-th lowest key rises to k-th position, including the initial state, separating the values with white space. Please use a built-in function to print the array.

– We won’t test array size over 20 or array size of 0.

c. Example Input &amp; Output

Input Output

“[(‘insertion’,42), (‘insertion’,20), 42 20 17 13 28 14 (‘insertion’,17), (‘insertion’,13), 13 42 20 17 14 28

(‘insertion’,28), (‘insertion’,14), 13 14 42 20 17 28

(‘bubbleSort’,NULL)]” 13 14 17 42 20 28

13 14 17 20 42 28

13 14 17 20 28 42

“[(‘insertion’,17), (‘insertion’,20), 17 20 2 21 4

(‘insertion’,2), (‘insertion’,21), 2 17 20 4 21

(‘insertion’,4), (‘bubbleSort’,NULL)]” 2 4 17 20 21

“[(‘insertion’,7), 7 6 5 4 3 2 1

(‘insertion’,6),(‘insertion’,5), 1 7 6 5 4 3 2

(‘insertion’,4),(‘insertion’,3), 1 2 7 6 5 4 3

(‘insertion’,2), (‘insertion’,1), 1 2 3 7 6 5 4

(‘bubbleSort’,NULL)]” 1 2 3 4 7 6 5

1 2 3 4 5 7 6

1 2 3 4 5 6 7

d. Example execution

&gt;&gt; ./pa3.exe 1 “[(‘insertion’,42), (‘insertion’,20),

(‘insertion’,17), (‘insertion’,13), (‘insertion’,28),

(‘insertion’,14), (‘bubbleSort’,NULL)]”

[Task 1]

42 20 17 13 28 14

13 42 20 17 14 28

13 14 42 20 17 28

13 14 17 42 20 28

13 14 17 20 42 28 13 14 17 20 28 42

2. Non-recursive Merge Sort (2 pts)

a. Implement a function that sorts a given array using the Merge Sort algorithm in descending order using non-recursive merge sort. Start with the sorted segments of size 1 and do pairwise merging of these sorted segments as in the upward pass.

You can modify sort.cpp and sort.h files for this problem.

b. Input &amp; Output

Input : A sequence of commands

– (‘insertion’,integer): insert integer into the array.

– (‘mergeSort’,NULL): sort the array using the Merge Sort algorithm.

Output

– Starting from the initial state of the array, print all values of the array at each iteration step after performing the necessary sorting. Print the array values at the initial state and at each iteration step where sorting is performed.

– Separate the values in the array with a space for each iteration step.

– You don’t need to consider exceptional cases such as overflow or an empty array. We will not test such cases.

c. Example Input &amp; Output

Input Output

“[(‘insertion’,56),(‘insertion’,42), 56 42 20 17 13

(‘insertion’,20),(‘insertion’,17), 28 14

(‘insertion’,13),(‘insertion’,28), 56 42 20 17 28

(‘insertion’,14),(‘mergeSort’,NULL)]” 13 14

56 42 20 17 28

14 13

56 42 28 20 17

14 13

“[(‘insertion’,36), (‘insertion’,20), 36 20 17 13 14

(‘insertion’,17), (‘insertion’,13), 28 15 23 32

(‘insertion’,14), (‘insertion’,28), 36 20 17 13 28

(‘insertion’,15), (‘insertion’,23), 14 23 15 32

(‘insertion’,32),(‘mergeSort’,NULL)]” 36 20 17 13 28

23 15 14 32

36 28 23 20 17

15 14 13 32

36 32 28 23 20

17 15 14 13

“[(‘insertion’,1), 1 2 3 4 5 6 7

(‘insertion’,2),(‘insertion’,3), 2 1 4 3 6 5 7

(‘insertion’,4),(‘insertion’,5), 4 3 2 1 7 6 5

(‘insertion’,6), (‘insertion’,7), 7 6 5 4 3 2 1

(‘mergeSort’,NULL)]”

d. Example execution

&gt;&gt; ./pa3.exe 2 “[(‘insertion’,56),(‘insertion’,42),

(‘insertion’,20),(‘insertion’,17),

(‘insertion’,13),(‘insertion’,28),

(‘insertion’,14),(‘mergeSort’,NULL)]”

[Task 2]

56 42 20 17 13 28 14

56 42 20 17 28 13 14

56 42 20 17 28 14 13 56 42 28 20 17 14 13

3. BST Insertion / Deletion / Summation (3pts)

a. Implement functions that inserts and deletes an element into a binary search tree (BST). Also you should find the sum of nodes that is larger than specific node value, and print the pre-order and in-order of the tree. You can modify bst.cpp and bst.h files for this problem. – Input of nodes are integers from 1 to 99

b. Input &amp; output of BinarySearchTree::insertion

Input:

– (‘insertion’,integer): Key of the element to be inserted. The key has a positive integer value.

Output:

– Return the -1 if the key already exists in the tree, 0 otherwise.

(If the key already exists, do not insert the element)

c. Input &amp; output of BinarySearchTree::deletion

Input:

– (‘deletion’,integer): Key of the element to be deleted.

Output:

– Return -1 if the key does not exist in the tree, 0 otherwise. If the key does not exist, do not delete any element.

Note that replace the smallest key in right subtree when delete the node with degree 2

d. Input &amp; output of BinarySearchTree::sum

Input:

– (‘sum’,integer): Sum of the nodes greater than the integer.

Output:

– Return the sum of nodes that is larger than the key value.

e. task_3 prints

i. the return for each insertion/deletion for command (‘insertion’, integer)/

(‘deletion’, integer) and ii. the return summation of nodes that is larger than a specific node value for command (‘sum’, integer) and

iii. the results of preorder and inorder traversal of the constructed tree for command (‘print’, NULL).

(If empty tree, don’t return preorder or inorder traveral results

f. Example Input &amp; Output

Input Output

[(‘insertion’,4), (‘insertion’,6), 0 (‘insertion’,6), (‘insertion’,7), 0

(‘deletion’,7), (‘print’, NULL)] -1

0

0

4 6

4 6

[(‘insertion’,4), (‘insertion’,2), (‘sum’, 0 1), (‘insertion’,10), (‘insertion’,9), 0

(‘insertion’,15), (‘insertion’,1), 6

(‘deletion’,1), (‘deletion’,4), 0

(‘deletion’,10), (‘sum’, 5), (‘print’, NULL)] 0 0

0

0

0

0

24

9 2 15

2 9 15

[(‘deletion’, 3),(‘insertion’, -1

10),(‘deletion’, 10), (‘sum’,2), 0

(‘print’,NULL)] 0

0

g. Example execution

4. Duplicate Letter Counting Problem (4 pts)

Example of left rotation to resolve RR imbalance

a. Implement a class ‘AVLTree’ to efficiently count and report the frequency of each alphabet letter in a string using AVL tree operations. This involves handling imbalances that might occur during insertions and deletions, as well as ensuring that alphabet letters are counted accurately. As the string is received, insert each letter sequentially from the beginning to the end into the AVL tree.

b. AVL Tree Implementations  Modify or implement functions in the ‘AVLTree’ class that insert and delete elements (letters in this case).

z Implement functions in the ‘AVLTree’ class that print the all node information in pre-order, in-order, and reverse-in-order manner.

z Ensure the AVL tree can resolve imbalances (LL, LR, RL, RR) that might occur after modifications.

z You can modify ‘avl.cpp’ and ‘avl.h’ files, and if needed, add public members to the ‘Node’ class implemented in ‘tree.h’.

c. Details of the process  Sequentially insert each letter from the string. If a node for that letter already exists, delete the existing node, increment the count, and re-insert the node.

z During the deletion process, if a node has both children, use the replacement method where you find the minimum in the right subtree to replace the node

z If counts are equal, prioritize based on the lexicographical order of the letters. For example, (c, 1) &lt; (a, 4) &lt; (b, 4).

d. Input &amp; Output:

z Input: A string consisting of at least one alphabetical letter. You don’t need to consider any other input cases and uppercase and lowercase of letters are same.

z Output: (1) Frequency counts of letters, displayed from the most to the least frequent. If multiple letters have the same frequency, they should be displayed in lexicographical order.

z Output: (2) The results of the preorder and inorder traversal of the constructed AVL tree after all operations.

e. task_4 prints

i. The results of reverse-inorder, inorder, preorder traversal of the constructed tree.

ii. The format of node for printing is “(letter, count)”

f. Example Input &amp; Output

Input Output

“aAbbbcccc” Frequencies of alphabetic letters in the given string (c, 4) (b, 3) (a, 2)

Inorder

(a, 2) (b, 3) (c, 4)

Preorder

(b, 3) (a, 2) (c, 4)

“a” Frequencies of alphabetic letters in

the given string

(a, 1)

Inorder

(a, 1)

Preorder

(a, 1)

“aabbbccccddDDd” Frequencies of

alphabetic letters in the given string (d, 5) (c, 4) (b, 3)

(a, 2)

Inorder

(a, 2) (b, 3) (c, 4)

(d, 5)

Preorder

(b, 3) (a, 2) (c, 4)

(d, 5)

g. Example execution

5. Open hash table (1 pts)

M which is the size of the hash table, insertions, and deletions of integers are given as instructions. First, for each insertion, record if a collision occurred. A collision occurs when a key is inserted into a non-empty slot. After all operations are complete, print the total number of collisions that occurred and the length of the longest chain in the hash table. You don’t need to consider a deletion of an unseen key and multiple insertions of the same key.

You can modify open_hash_function.cpp, open_hash_table.cpp, open_hash_function.h and open_hash_table.h files for this problem.

b. Input &amp; Output

Input: A sequence of commands

– (‘M’,integer): the size of a hash table.

– (The first command should always be ‘M’)

– (‘insertion’,integer): insert integer into the hash table.

– (‘deletion’,integer): delete integer from the hash table.

Output: For each slot of the hash table, print out

– the number of collisions occurred during execution.

– the length of the longest chain in the final table.

c. Example Input &amp; Output

Input Output

[(‘M’,4), (‘insertion’,32615)] 0 1

[(‘M’,4), (‘insertion’,32615), 1 2

(‘insertion’,315), (‘insertion’,6468),

(‘insertion’,94833)]

[(‘M’,4), (‘insertion’,32615), 1 1

(‘insertion’,315), (‘insertion’,6468),

(‘insertion’,94833), (‘deletion’,32615),

(‘deletion’,6468)]

d. Example execution

6. Closed hash table (3 pts)

a. Implement insertion of a closed hash table with rehashing implementation. This hash table is used with integer keys and hashing into a table of size M. This hash table uses pseudo-random probing as a collision handling method. The index of the key ݇ after ݅-th collision, ݄௜(݇), is:

ܯ ݀݋݉ (௜݀ + (݇)݄) = (݇)௜݄

where ݄(݇) is the digit-folding method hash function. It works same with the hash function in task 5.

݀ଵ, ݀ଶ, … , ݀ெିଵ is a pseudo-random permutation of integers 1, … , M-1 and it is generated by shift-register sequence. Please refer to slide “Example:

Given M, k, ݀ଵ for the shift-register sequence and inserted integers, print the result hash table. If the hash table is full or the collision cannot be resolved, stop the insertion, and print results of the insertions made up to that point, then print FAIL. Refer to instruction b &amp; c for more detail.

You don’t need to consider a deletion of a key, multiple insertions of the same key. You can modify closed_hash_function.cpp, closed_hash_table.cpp, closed_hash_function.h and closed_hash_table.h files for this problem.

b. Input &amp; Output

Input: A sequence of commands

– (‘M’,integer): the size of a hash table.

(The first command is always ‘M’)

– (‘k’,integer): a constant used for shift-register sequence.

(The second command is always ‘k’)

– (‘d’,integer): the first probing offset for the shift-register sequence .

(The third command is always ‘d’)

– (‘insertion’,integer): insert integer into the hash table.

Output:

For each slot of the hash table, print out – the value, if the state of the slot is occupied.

– ‘EMPTY’ if the state of the slot is empty.

‘FAIL’ if the hash table is full or the collision cannot be resolved.

c. Example Input &amp; Output

Input Output

[(‘M’,4), (‘k’,3), (‘d’,2), 0: 6468

(‘insertion’,32615), (‘insertion’,315), 1: 32615

(‘insertion’,6468), (‘insertion’,94833)] 2: 94833

3: 315

[(‘M’,4), (‘k’,3), (‘d’,2), (‘insert’,32615), 0: 6468

(‘insertion’,315), (‘insertion’,6468), 1: 32615

(‘insertion’,94833), (‘insertion’,22)] 2: 94833

3: 315

FAIL

[(‘M’,5), (‘k’,3), (‘d’,2), (‘insertion’,2), 0: EMPTY

(‘insertion’,7), (‘insertion’,11), 1: 11 (‘insertion’,20), (‘insertion’,18)] 2: 2

3: EMPTY

4: 7

FAIL

d. Example execution
