Array to BST 

Given a sorted array. Convert it into a Height balanced Binary Search Tree (BST).
Height balanced BST means a binary tree in which the depth of the two subtrees of every node never differ by more than 1.

Example 1:

Input: nums = {1, 2, 3, 4}
Output: {2, 1, 3, 4}
Explanation: 
The preorder traversal of the following 
BST formed is {2, 1, 3, 4}:
     3
    /  \
   2    4
 /
1

Example 2:

Input: nums = {1,2,3,4,5,6,7}
Ouput: {4,2,1,3,6,5,7}
Explanation: 
The preorder traversal of the following
BST formed is {4,2,1,3,6,5,7} :
        4
       / \
      2   6
     / \  / \
    1   3 5  7
 

Your Task:
You don't need to read or print anything. Your task is to complete the function sortedArrayToBST() which takes nums as input paramater and returns the preorder traversal of height balanced BST.

Expected Time Complexity: O(n)
Expected Space Complexity: O(n)

Constraints:
1 ≤ |nums| ≤ 104
-104 ≤ nums[i] ≤ 104
 
