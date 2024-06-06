## Leetcode questions I solved by topics with explanations.

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
|[88. Merge Sorted Array](https://github.com/JC01111/Leetcode_I_Solved/blob/d592565df0515f611eb58358fda5215e85cabdf2/88.Merge_Sorted_Array%20(Easy).md)|${\text{\color{ForestGreen}Easy}}$|[Link](https://leetcode.com/problems/merge-sorted-array/)|
|[27. Remove Element](https://github.com/JC01111/Leetcode_I_Solved/blob/57b83277e524b5c2a0ad3b70532a910f4a6a0582/27.Remove_Element%20(Easy).md)|${\text{\color{ForestGreen}Easy}}$|[Link](https://leetcode.com/problems/remove-element/)|
|[26. Remove Duplicates from Sorted Array](https://github.com/JC01111/Leetcode_I_Solved/blob/7dde1aa602a5ce396130e359d6ef118c1c75c929/26.Remove_Duplicates_from_Sorted_Array%20(Easy).md)|${\text{\color{ForestGreen}Easy}}$|[Link](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)|

<br>

---

### Two Pointers

Two pointers can save space complexit, because it only uses constant space complexity $O(1)$.

|Two Pointers|||
|---|---|---|
|[125. Valid Palindrome](https://github.com/JC01111/Leetcode_I_Solved/blob/675c5c4a58335442c2cd1ce938d2b60e323ffd28/125.Valid_Palindrome_Easy.md)|${\text{\color{ForestGreen}Easy}}$|[Link](https://leetcode.com/problems/valid-palindrome/)|
|[167. Two Sum II - Input Array Is Sorted](https://github.com/JC01111/Leetcode_I_Solved/blob/90374bc8e99477ed815ca4f25bc6e28a7dd350db/167.Two_Sum_II_Medium.md)|${\text{\color{Dandelion}Medium}}$|[Link](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)|

<br>

---

### Sliding Window

|Sliding Window|||
|---|---|---|
|[3. Longest Substring Without Repeating Characters](https://github.com/JC01111/Leetcode_I_Solved/blob/84a5b6484a2992556d19acda4aae08b6db5ac70f/3.Longest_Substring_Without_Repeating_Characters%20(Medium).md)|${\text{\color{Dandelion}Medium}}$|[Link](https://leetcode.com/problems/longest-substring-without-repeating-characters/)|
|[121. Best Time to Buy and Sell Stock](https://github.com/JC01111/Leetcode_I_Solved/blob/7dde1aa602a5ce396130e359d6ef118c1c75c929/121.Best_Time_to_Buy_and_Sell_Stock%20(Easy).md)|${\text{\color{ForestGreen}Easy}}$|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)|

<br>

---

### Matrix

|Matrix|||
|---|---|---|
|[36. Valid Sudoku](https://github.com/JC01111/Leetcode_I_Solved/blob/ec58433eb422a6791a4b41b026913225942f79c5/36.Valid_Sudoku%20(Medium).md)|${\text{\color{Dandelion}Medium}}$|[Link](https://leetcode.com/problems/valid-sudoku/)|

<br>

---
  
### Hashmap

In general, create a hashmap {} and store elements and their indices into the hashmap as the for-loop goes, then in the for loop we check if an element has already in the hashmap or not, or in the case we want to decrement the number of times we have seen an element in the hashmap.

|Hashmap|||
|---|---|---|
|[1. Two Sum](https://github.com/JC01111/Leetcode_I_Solved/blob/94b6d95ecacab8f50bd55471398de87632ca42eb/1.Two_Sum%20(Easy).md)|${\text{\color{ForestGreen}Easy}}$|[Link](https://leetcode.com/problems/two-sum/)|
|[219. Contains Duplicate II](https://github.com/JC01111/Leetcode_I_Solved/blob/29826247fb086ad0c1e016a9d407f6c0e4f44104/219.Contains_Duplicate_II%20(Easy).md)|${\text{\color{ForestGreen}Easy}}$|[Link](https://leetcode.com/problems/contains-duplicate-ii/)|
|[383. Ransom Note](https://github.com/JC01111/Leetcode_I_Solved/blob/f25d091d997890166c3d11c809198ac6624ff2de/383.Ransom_Note%20(Easy).md)|${\text{\color{ForestGreen}Easy}}$|[Link](https://leetcode.com/problems/ransom-note/)|

<br>

---

### Intervals

|Intervals|||
|---|---|---|
|[Insert Interval](https://github.com/JC01111/Leetcode_I_Solved/blob/b9c48608c0d838b93411f7d2dcd8b68f3099e0c4/57.Insert_Interval%20(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-interval/)|

<br>

---

### Stack

|Stack||
|---|---|
|[20. Valid Parentheses](https://github.com/JC01111/Leetcode_I_Solved/blob/c363d9a4395a2796b1613d8ac9504fc11fc62f90/20.Valid_Parentheses%20(Easy).md)|Easy|
|[155. Min Stack](https://github.com/JC01111/Leetcode_I_Solved/blob/d592565df0515f611eb58358fda5215e85cabdf2/155.Min_Stack%20(Medium).md)|Medium|

<br>

---

### Linked List

|Linked List||
|---|---|
|[141. Linked List Cycle](https://github.com/JC01111/Leetcode_I_Solved/blob/29826247fb086ad0c1e016a9d407f6c0e4f44104/141.Linked_List_Cycle%20(Easy).md)|Easy|
|[2. Add Two Numbers](https://github.com/JC01111/Leetcode_I_Solved/blob/29826247fb086ad0c1e016a9d407f6c0e4f44104/2.Add_Two_Numbers%20(Medium).md)|Medium|
|[21. Merge Two Sorted Lists](https://github.com/JC01111/Leetcode_I_Solved/blob/29826247fb086ad0c1e016a9d407f6c0e4f44104/21.Merge_Two_Sorted_Lists%20(Easy).md)|Easy|

<br>

---

### Binary Tree General

Binary Tree Problems usually can use Recursion to solve, start from the root, then recurse on its left subtree and right subtree.

|Binary Tree General||
|---|---|
|[104. Maximum Depth of Binary Tree](https://github.com/JC01111/Leetcode_I_Solved/blob/29826247fb086ad0c1e016a9d407f6c0e4f44104/104.Maximum_Depth_of_Binary_Tree%20(Easy).md)|Easy|
|[100. Same Tree](https://github.com/JC01111/Leetcode_I_Solved/blob/29826247fb086ad0c1e016a9d407f6c0e4f44104/100.Same_Tree%20(Easy).md)|Easy|
|[226. Invert Binary Tree](https://github.com/JC01111/Leetcode_I_Solved/blob/81870a2d4bb636f3104074f4535289859cc46d89/226.Invert_Binary_Tree_Easy.md)|Easy|

<br>

---

### 1D DP

|1D DP||
|---|---|
|[70. Climbing Stairs](https://github.com/JC01111/Leetcode_I_Solved/blob/29826247fb086ad0c1e016a9d407f6c0e4f44104/70.Climbing_Stairs%20(Easy).md)|Easy|

<br>

---

### Others

|Others|||
|---|---|---|
|[217. Contains Duplicate](https://github.com/JC01111/Leetcode_I_Solved/blob/7dde1aa602a5ce396130e359d6ef118c1c75c929/217.Contains_Duplicate%20(Easy).md)|Easy|[Link](https://leetcode.com/problems/contains-duplicate/)|
