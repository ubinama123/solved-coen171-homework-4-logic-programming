Download Link: https://assignmentchef.com/product/solved-coen171-homework-4-logic-programming
<br>
In this assignment, you will write programs in Prolog, a logic programming language. Use either the Linux or OS X machines in the Computing Center for this project. The Prolog interpreter is gprolog. Choose any two of the following three programs.

<h1>1        Quicksort</h1>

In Prolog, write a program to sort a list using the <strong><em>quicksort </em></strong>sorting algorithm discussed previously. Call this program sort.pro. Your program should contain at least the following relations:

<ul>

 <li>quicksort(X,Y): Succeeds if Y can be unified with a list containing the sorted elements of X.</li>

</ul>

<strong>Goal:               </strong>To gain experience with list processing in a logical language.

<strong>Hints: </strong>Write a relation partition that partitions a list into two lists, one containing the elements below the pivot element, and another containing the elements above the pivot element.

<h1>2        BinarySearchTrees</h1>

As in the first assignment, a <strong><em>binarysearchtree </em></strong>is either empty, or it consists of a node with two binary search trees as subtrees. Each node holds an integer. In Prolog, write a program to implement binary search trees. Call your program tree.pro. Your program should contain at least the following relations:

<ul>

 <li>insert(X,Y,Z): Succeeds if Z can be unified to a tree that is the result of inserting the value X into Y.</li>

 <li>exists(X,Y): Succeeds if the integer value X is present in the tree Y.</li>

</ul>

<strong>Goal:            </strong>To represent structures as terms in Prolog.

<strong>Hints:                 </strong>A tree node can be represented using terms such as node/3 and empty/0.

<h1>3        The8-QueensProblem</h1>

Write a Prolog program to solve the <strong><em>8-queens problem </em></strong>from the second assignment. Your program should be capable of backtracking so that all possible solutions can be generated. Call this program queens.pro. Your program should contain at least the following relations:

<ul>

 <li>queens(X): Succeeds if X can be unified to a chessboard containing a solution to problem of placing eight queens on the board such that no queen can attack another.</li>

</ul>

<strong>Goal:            </strong>To learn how backtracking works in Prolog.

<strong>Hints: </strong>Representtheboardasalistofpositions. Eachpositionisatermconsistingoftherowandcolumnnumber of a queen such as R/C or piece(R,C). Since each queen must be placed in a different row, unify each row variable with its row number so that you need only solve for the column number.