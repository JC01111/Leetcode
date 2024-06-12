## Leetcode problems I solved by topics with explanations.

<!--
Template
|Topic|||
|---|---|---|
|[]()|Easy|[Link]()|
-->

<br>

### Array / String

General cases we want to replace element with non-repeating element in `nums`, so we set an index to keep track of repeating position.

|Array / String|||
|---|---|---|
|[88. Merge Sorted Array](88.Merge_Sorted_Array_(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-sorted-array/)|
|[27. Remove Element](27.Remove_Element_(Easy).md)|Easy|[Link](https://leetcode.com/problems/remove-element/)|
|[26. Remove Duplicates from Sorted Array](26.Remove_Duplicates_from_Sorted_Array_(Easy).md)|Easy|[Link](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)|

<br>

---

### Two Pointers

Two pointers can save space complexit, because it only uses constant space complexity $O(1)$.

|Two Pointers|||
|---|---|---|
|[125. Valid Palindrome](125.Valid_Palindrome_(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-palindrome/)|
|[167. Two Sum II - Input Array Is Sorted](167.Two_Sum_II_(Medium).md)|Medium|[Link](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)|

<br>

---

### Sliding Window

|Sliding Window|||
|---|---|---|
|[3. Longest Substring Without Repeating Characters](3.Longest_Substring_Without_Repeating_Characters_(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-substring-without-repeating-characters/)|
|[121. Best Time to Buy and Sell Stock](121.Best_Time_to_Buy_and_Sell_Stock_(Easy).md)|Easy|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)|

<br>

---

### Matrix

|Matrix|||
|---|---|---|
|[36. Valid Sudoku](36.Valid_Sudoku_(Medium).md)|Medium|[Link](https://leetcode.com/problems/valid-sudoku/)|[Link](https://leetcode.com/problems/valid-sudoku/)|

<br>

---
  
### Hashmap

In general, create a hashmap {} and store elements and their indices into the hashmap as the for-loop goes, then in the for loop we check if an element has already in the hashmap or not, or in the case we want to decrement the number of times we have seen an element in the hashmap.

|Hashmap|||
|---|---|---|
|[1. Two Sum](1.Two_Sum_(Easy).md)|Easy|[Link](https://leetcode.com/problems/two-sum/)|
|[219. Contains Duplicate II](219.Contains_Duplicate_II_(Easy).md)|Easy|[Link](https://leetcode.com/problems/contains-duplicate-ii/)|
|[383. Ransom Note](383.Ransom_Note_(Easy).md)|Easy|[Link](https://leetcode.com/problems/ransom-note/)|

<br>

---

### Intervals

|Intervals|||
|---|---|---|
|[57. Insert Interval](57.Insert_Interval_(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-interval/)|

<br>

---

### Stack

|Stack|||
|---|---|---|
|[20. Valid Parentheses](20.Valid_Parentheses_(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-parentheses/)|
|[155. Min Stack](155.Min_Stack_(Medium).md)|Medium|[Link](https://leetcode.com/problems/min-stack/)|

<br>

---

### Linked List

|Linked List|||
|---|---|---|
|[141. Linked List Cycle](141.Linked_List_Cycle_(Easy).md)|Easy|[Link](https://leetcode.com/problems/linked-list-cycle/)|
|[2. Add Two Numbers](2.Add_Two_Numbers_(Medium).md)|Medium|[Link](https://leetcode.com/problems/add-two-numbers/)|
|[21. Merge Two Sorted Lists](21.Merge_Two_Sorted_Lists_(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-two-sorted-lists/)|

<br>

---

### Binary Tree General

Binary Tree Problems usually can use Recursion to solve, start from the root, then recurse on its left subtree and right subtree.

|Binary Tree General|||
|---|---|---|
|[104. Maximum Depth of Binary Tree](104.Maximum_Depth_of_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/maximum-depth-of-binary-tree/)|
|[100. Same Tree](100.Same_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/same-tree/)|
|[226. Invert Binary Tree](226.Invert_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/invert-binary-tree/)|

<br>

---

### Binary Tree BFS

BFS uses `collections.queue()` and follows **FIFO**, DFS uses `stack()` and follows **LIFO**, both BFS and DFS can be implemented by `list()`.

|Binary Tree BFS|||
|---|---|---|
|[199. Binary Tree Right Side View](199.Binary_Tree_Right_Side_View_(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-right-side-view/)|
|[637. Average of Levels in Binary Tree](637.Average_of_Levels_in_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/average-of-levels-in-binary-tree/)|

<br>

---

### Binary Search Tree

Binary Search Tree (BST) has property that the nodes on the left of the root are smaller than the root, the nodes on the right of the root are greater than the root. So, in many cases we can implement the **DFS** to perform **in-order** traversal.

|Binary Search Tree|||
|---|---|---|
|[530. Minimum Absolute Difference in BST](530.Minimum_Absolute_Difference_in_BST_(Easy).md)|Easy|[Link](https://leetcode.com/problems/minimum-absolute-difference-in-bst/)|
|[230. Kth Smallest Element in a BST](230.Kth_Smallest_Element_in_a_BST_(Medium).md)|Medium|[Link](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)|
|[98. Validate Binary Search Tree](98.Validate_Binary_Search_Tree_(Medium).md)|Medium|[Link](https://leetcode.com/problems/validate-binary-search-tree/)|

<br>

---

### 1D DP

|1D DP|||
|---|---|---|
|[70. Climbing Stairs](70.Climbing_Stairs_(Easy).md)|Easy|[Link](https://leetcode.com/problems/climbing-stairs/)|

<br>

---

### Others

|Others|||
|---|---|---|
|[217. Contains Duplicate](217.Contains_Duplicate_(Easy).md)|Easy|[Link](https://leetcode.com/problems/contains-duplicate/)|



<p xmlns:cc="http://creativecommons.org/ns#" >This work by <span property="cc:attributionName">Jiawei Chen</span> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p>
