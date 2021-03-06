1. **N Meetings in a room** : There is one meeting room in a firm. There are N meetings in the form of (start[i], end[i]) where start[i] is start time of meeting i and end[i] is finish time of meeting i.
What is the maximum number of meetings that can be accommodated in the meeting room when only one meeting can be held in the meeting room at a particular time?
Note: Start time of one chosen meeting can't be equal to the end time of the other chosen meeting.
Example:
Input:
N = 6
start[] = {1,3,0,5,8,5}
end[] =  {2,4,6,7,9,9}
Output: 
4

2. **Dam of Candies** : Geek wants to make a special space for candies on his bookshelf. Currently, it has N books, each of whose height is represented by the array height[] and has unit width.
Help him select 2 books such that he can store maximum candies between them by removing all the other books from between the selected books. The task is to find out the area between two books that can hold the maximum candies without changing the original position of selected books. 
Example:
Input: N = 3, height[] = {1, 3, 4}
Output: 1

3. **Factorial of large numbers** : Given an integer N, find its factorial.
Example:
Input: N = 5
Output: 120

4. **Kth Element of an array** : Given two sorted arrays arr1 and arr2 of size N and M respectively and an element K. The task is to find the element that would be at the k’th position of the final sorted array.
Example:
Input:
arr1[] = {2, 3, 6, 7, 9}
arr2[] = {1, 4, 8, 10}
k = 5
Output:
6

5. **Median of Sorted Array** : Given two sorted arrays array1 and array2 of size m and n respectively. Find the median of the two sorted arrays.
Example:
Input:
m = 3, n = 4
array1[] = {1,5,9}
array2[] = {2,3,6,7}
Output: 5

6. **Repeated Strinf Match** : Given two strings A and B, find the minimum number of times A has to be repeated such that B becomes a substring of the repeated A. If B cannot be a substring of A no matter how many times it is repeated, return -1.
Example:
Input: A = "abcd", B = "cdabcdab"
Output: 3

7. **Sort 012** : Given an array of size N containing only 0s, 1s, and 2s; sort the array in ascending order.\

8. **Sum of Queries** : You are given an array arr[] of n integers and q queries in an array queries[] of length 2*q containing l, r pair for all q queries. You need to compute the following sum over q queries.
Array is 1-Indexed.
Example:
Input: n = 4
arr = {1, 2, 3, 4}
q = 2
queries = {1, 4, 2, 3}
Output: 10 5

9. **Total Set Bits** : You are given a number N. Find the total count of set bits for all numbers from 1 to N(both inclusive).
Example:
Input: N = 4
Output: 5

10. **Check Tree Traversal** : Given Preorder, Inorder and Postorder traversals of some tree of size N. The task is to check if they are all of the same tree or not.
Example:
Input:
N = 5
preorder[] = {1, 2, 4, 5, 3}
inorder[] = {4, 2, 5, 1, 3}
postorder[] = {4, 5, 2, 3, 1}
Output: Yes

11. **Find Middle Element** : Given a singly linked list of N nodes.
The task is to find the middle of the linked list. For example, if the linked list is
1-> 2->3->4->5, then the middle node of the list is 3.
If there are two middle nodes(in case, when N is even), print the second middle element.
For example, if the linked list given is 1->2->3->4->5->6, then the middle node of the list is 4.

12. **Count Occurence of Anagrams** : Given a word pat and a text txt. Return the count of the occurences of anagrams of the word in the text.
Example 1:
Input:
txt = forxxorfxdofr
pat = for
Output: 3

13. **Largest Subarray** : Given an array having both positive and negative integers. The task is to compute the length of the largest subarray with sum 0.
Example:
Input:
N = 8
A[] = {15,-2,2,-8,1,7,10,23}
Output: 5

14. **Sort a Stack** : Given a stack, the task is to sort it such that the top of the stack has the greatest element.
Example:
Input:
Stack: 3 2 1
Output: 3 2 1

15. **Restricted Pacman** : In the game of Restricted Pacman, an infinite linear path is given. Pacman has to start at position 0 and eat as many candies as possible. In one move he can only jump a distance of either M or N.  If M and N are coprime numbers, find how many candies will be left on the board after the game is over.
Note: The result is always finite as after a point X every index in the infinite path can be visited. 
Example:
Input: M = 2, N = 5
Output: 2

16. **Vertical Travesal of Binary Tree** : Given a Binary Tree, find the vertical traversal of it starting from the leftmost level to the rightmost level.
If there are multiple nodes passing through a vertical line, then they should be printed as they appear in level order traversal of the tree.

17. **Check for BST** : Given the root of a binary tree. Check whether it is a BST or not.
Note: We are considering that BSTs can not contain duplicate Nodes.
A BST is defined as follows:
The left subtree of a node contains only nodes with keys less than the node's key.
The right subtree of a node contains only nodes with keys greater than the node's key.
Both the left and right subtrees must also be binary search trees.
