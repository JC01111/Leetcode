## Leetcode problems I solved by topics with explanations.

<!--
Template
|Topic|||
|---|---|---|
|[]()|Easy|[Link]()|
-->

### Contents
- [Array / String](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#array--string)
- [Two Pointers](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#two-pointers)
- [Sliding Window](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#sliding-window)
- [Matrix](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#matrix)
- [Binary Search](https://github.com/JC01111/Leetcode_I_Solved/tree/main?tab=readme-ov-file#binary-search)
- [Backtracking](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#backtracking)
- [Stack](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#stack)
- [Linked List](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#linked-list)
- [Binary Tree General](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#binary-tree-general)
- [Binary Tree BFS](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#binary-tree-bfs)
- [Binary Search Tree](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#binary-search-tree)
- [Graph General](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#graph-general)
- [Trie](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#trie)
- [Intervals](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#intervals)
- [Hashmap](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#hashmap)
- [Divide & Conquer]()
- [Kadane's Algorithm]()
- [Heap](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#heap)
- [Bit Manupulation]()
- [Math](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#math)
- [Greedy](https://github.com/JC01111/Leetcode_I_Solved#greedy)
- [1D DP](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#1d-dp)
- [2D DP](https://github.com/JC01111/Leetcode_I_Solved#2d-dp)
- [Multidimensional DP]()
- [Others](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#others)

<br>

___

### Array / String

General cases we want to replace element with non-repeating element in `nums`, so we set an index to keep track of repeating position.

|Array / String|||
|---|---|---|
|[88. Merge Sorted Array](./questions/88.Merge_Sorted_Array_(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-sorted-array/)|
|[27. Remove Element](./questions/27.Remove_Element_(Easy).md)|Easy|[Link](https://leetcode.com/problems/remove-element/)|
|[26. Remove Duplicates from Sorted Array](./questions/26.Remove_Duplicates_from_Sorted_Array_(Easy).md)|Easy|[Link](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)|
|[80. Remove Duplicates from Sorted Array II](./questions/80.Remove_Duplicates_from_Sorted_Array_II_(Medium).md)|Medium|[Link](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/)|
|[169. Majority Element](./questions/169.Majority_Element_(Easy).md)|Easy|[Link](https://leetcode.com/problems/majority-element/)|
|[189. Rotate Array](./questions/189.Rotate_Array_(Medium).md)|Mediun|[Link](https://leetcode.com/problems/rotate-array/)|
|[121. Best Time to Buy and Sell Stock](./questions/121.Best_Time_to_Buy_and_Sell_Stock_(Easy).md)|Easy|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)|
|[122. Best Time to Buy and Sell Stock II](./questions/122.Best_Time_to_Buy_and_Sell_Stock_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/)|
|[45. Jump Game II](./questions/45.Jump_Game_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/jump-game-ii/)|
|[14. Longest Common Prefix](./questions/14.Longest_Common_Prefix(Easy).md)|Easy|[Link](https://leetcode.com/problems/longest-common-prefix/)|
|[58. Length of Last Word](./questions/58.Length_of_Last_Word(Easy).md)|Easy|[Link](https://leetcode.com/problems/length-of-last-word/)|
|[151. Reverse Words in a String](./questions/151.Reverse_Words_in_a_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/reverse-words-in-a-string/)|
|[42. Trapping Rain Water](./questions/42.Trapping_Rain_Water(Hard).md)|Hard|[Link](https://leetcode.com/problems/trapping-rain-water/)|
|[6. Zigzag Conversion](./questions/6.Zigzag_Conversion(Medium).md)|Medium|[Link](https://leetcode.com/problems/zigzag-conversion/)|
|[68. Text Justification](./questions/68.Text_Justification(Hard).md)|Hard|[Link](https://leetcode.com/problems/text-justification/)|

<br>

---

### Two Pointers

Two pointers can save space complexity, because it only uses constant space complexity $O(1)$. Usually use `l, r` pointers and either increment `l` or decrement `r` depends on the current `sum` compare with `target` value.

|Two Pointers|||
|---|---|---|
|[125. Valid Palindrome](./questions/125.Valid_Palindrome_(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-palindrome/)|
|[167. Two Sum II - Input Array Is Sorted](./questions/167.Two_Sum_II_(Medium).md)|Medium|[Link](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)|
|[392. Is Subsequence](./questions/392.Is_Subsequence(Easy).md)|Easy|[Link](https://leetcode.com/problems/is-subsequence/)|
|[11. Container With Most Water](./questions/11.Container_With_Most_Water(Medium).md)|Medium|[Link](https://leetcode.com/problems/container-with-most-water/)|
|[15. 3Sum](./questions/15.3Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/3sum/)|

<br>

---

### Sliding Window

Sliding Window technique is similar to Two Pointers, usually use a left pointer as a "Pivot" to know where we start recently and then update `left += 1`. Sometimes we may need to use **hashmaps** to find substring.

|Sliding Window|||
|---|---|---|
|[3. Longest Substring Without Repeating Characters](./questions/3.Longest_Substring_Without_Repeating_Characters_(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-substring-without-repeating-characters/)|
|[121. Best Time to Buy and Sell Stock](./questions/121.Best_Time_to_Buy_and_Sell_Stock_(Easy).md)|Easy|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)|
|[53. Maximum Subarray](./questions/53.Maximum_Subarray_(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-subarray/)|
|[209. Minimum Size Subarray Sum](./questions/209.Minimum_Size_Subarray_Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-size-subarray-sum/)|
|[424. Longest Repeating Character Replacement](./questions/424.Longest_Repeating_Character_Replacement(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-repeating-character-replacement/)|
|[76. Minimum Window Substring](./questions/76.Minimum_Window_Substring(Hard).md)|Hard|[Link](https://leetcode.com/problems/minimum-window-substring/)|
|[239. Sliding Window Maximum](./questions/239.Sliding_Window_Maximum(Hard).md)|Hard|[Link](https://leetcode.com/problems/sliding-window-maximum/)|
|[567. Permutation in String](./questions/567.Permutation_in_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/permutation-in-string/)|

<br>

---

### Matrix

The trick is to use pointers to keep in track of the boundaries. Then we shrink the boundaries after we finish a traverse or something.

|Matrix|||
|---|---|---|
|[36. Valid Sudoku](./questions/36.Valid_Sudoku_(Medium).md)|Medium|[Link](https://leetcode.com/problems/valid-sudoku/)|[Link](https://leetcode.com/problems/valid-sudoku/)|
|[54. Spiral Matrix](./questions/54.Spiral_Matrix(Medium).md)|Medium|[Link](https://leetcode.com/problems/spiral-matrix/)|
|[48. Rotate Image](./questions/48.Rotate_Image(Medium).md)|Medium|[Link](https://leetcode.com/problems/rotate-image/)|
|[73. Set Matrix Zeroes](./questions/73.Set_Matrix_Zeroes(Medium).md)|Medium|[Link](https://leetcode.com/problems/set-matrix-zeroes/)|

<br>

---

### Binary Search
This is the approach when we are required to write an algorithm with $O(log\ n)$ runtime. Usually, we just need to define the left & right pointer, then we iteratively find the mid point by `(left + right) // 2`, and compare the mid point with `target`, if `target < m`, we update the `right` by `m - 1`, if `target > m`, we update `left` by `m + 1`. 

|Binary Search|||
|---|---|---|
|[704. Binary Search](./questions/704.Binary_Search_(Easy).md)|Easy|[Link](https://leetcode.com/problems/binary-search/)|
|[35. Search Insert Position](./questions/35.Search_Insert_Position_(Easy).md)|Easy|[Link](https://leetcode.com/problems/search-insert-position/)|
|[74. Search a 2D Matrix](./questions/74.Search_a_2D_Matrix_(Medium).md)|Medium|[Link](https://leetcode.com/problems/search-a-2d-matrix/)|
|[875. Koko Eating Bananas](./questions/875.Koko_Eating_Bananas(Medium).md)|Medium|[Link](https://leetcode.com/problems/koko-eating-bananas/)|
|[153. Find Minimum in Rotated Sorted Array](./questions/153.Find_Minimum_in_Rotated_Sorted_Array(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)|
|[33. Search in Rotated Sorted Array](./questions/33.Search_in_Rotated_Sorted_Array(Medium).md)|Medium|[Link](https://leetcode.com/problems/search-in-rotated-sorted-array/)|
|[162. Find Peak Element](./questions/162.Find_Peak_Element(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-peak-element/)|
|[34. Find First and Last Position of Element in Sorted Array](./questions/34.Find_First_and_Last_Position_of_Element_in_Sorted_Array(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)|
|[4. Median of Two Sorted Arrays](./questions/4.Median_of_Two_Sorted_Arrays(Hard).md)|Hard|[Link](https://leetcode.com/problems/median-of-two-sorted-arrays/)|

<!--
|[]()|Easy|[Link]()|
-->
<br>

---

### Backtracking

Backtracing is recursion with base case(s), we have to first find the base case(s), if the case satisfies the base case condition that we can `append` the desired answer then return, and continue the recursion by `i+1`.

|Backtracking|||
|---|---|---|
|[78. Subsets](./questions/78.Subsets_(Medium).md)|Medium|[Link](https://leetcode.com/problems/subsets)|
|[90. Subsets II](./questions/90.Subsets_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/subsets-ii/)|
|[39. Combination Sum](./questions/39.Combination_Sum_(Medium).md)|Medium|[Link](https://leetcode.com/problems/combination-sum/)|
|[40. Combination Sum II](./questions/40.Combination_Sum_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/combination-sum-ii/)|
|[216. Combination Sum III](./questions/216.Combination_Sum_III(Medium).md)|Medium|[Link](https://leetcode.com/problems/combination-sum-iii/)|
|[17. Letter Combinations of a Phone Number](./questions/17.Letter_Combinations_of_a_Phone_Number_(Medium).md)|Medium|[Link](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)|
|[77. Combinations](./questions/77.Combinations_(Medium).md)|Medium|[Link](https://leetcode.com/problems/combinations/)|
|[22. Generate Parentheses](./questions/22.Generate_Parentheses(Medium).md)|Medium|[Link](https://leetcode.com/problems/generate-parentheses/)|
|[46. Permutations](./questions/46.Permutations(Medium).md)|Medium|[Link](https://leetcode.com/problems/permutations/)|
|[79. Word Search](./questions/79.Word_Search(Medium).md)|Medium|[Link](https://leetcode.com/problems/word-search/)|
|[131. Palindrome Partitioning](./questions/131.Palindrome_Partitioning(Medium).md)|Medium|[Link](https://leetcode.com/problems/palindrome-partitioning/)|
|[51. N-Queens](./questions/51.N-Queens(Hard).md)|Hard|[Link](https://leetcode.com/problems/n-queens/)|
|[52. N-Queens II](./questions/52.N-Queens_II(Hard).md)|Hard|[Link](https://leetcode.com/problems/n-queens-ii/)|

<!--
|[]()|Medium|[Link]()|
-->

<br>

---

### Stack

|Stack|||
|---|---|---|
|[20. Valid Parentheses](./questions/20.Valid_Parentheses_(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-parentheses/)|
|[155. Min Stack](./questions/155.Min_Stack_(Medium).md)|Medium|[Link](https://leetcode.com/problems/min-stack/)|
|[150. Evaluate Reverse Polish Notation](./questions/150.Evaluate_Reverse_Polish_Notation(Medium).md)|Medium|[Link](https://leetcode.com/problems/evaluate-reverse-polish-notation/)|
|[22. Generate Parentheses](./questions/22.Generate_Parentheses(Medium).md)|Medium|[Link](https://leetcode.com/problems/generate-parentheses/)|
|[739. Daily Temperatures](./questions/73.Set_Matrix_Zeroes(Medium).md)|Medium|[Link](https://leetcode.com/problems/daily-temperatures/)|


<!--
|[]()|Easy|[Link]()|
-->
<br>

---

### Linked List

|Linked List||||
|---|---|---|---|
|Problems|Difficulty|Link|Languages|
|[141. Linked List Cycle](./questions/141.Linked_List_Cycle_(Easy).md)|Easy|[Link](https://leetcode.com/problems/linked-list-cycle/)|
|[21. Merge Two Sorted Lists](./questions/21.Merge_Two_Sorted_Lists_(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-two-sorted-lists/)|
|[2. Add Two Numbers](./questions/2.Add_Two_Numbers_(Medium).md)|Medium|[Link](https://leetcode.com/problems/add-two-numbers/)|
|[206. Reverse Linked List](./questions/206.Reverse_Linked_List(Easy).md)|Easy|[Link](https://leetcode.com/problems/reverse-linked-list/)|
|[92. Reverse Linked List II](./questions/92.Reverse_Linked_List_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/reverse-linked-list-ii/)|
|[138. Copy List with Random Pointer](./questions/138.Copy_List_With_Random_Pointer(Medium).md)|Medium|[Link](https://leetcode.com/problems/copy-list-with-random-pointer/)|
|[143. Reorder List](./questions/143.Reorder_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/reorder-list/)|
|[19. Remove Nth Node From End of List](./questions/19.Remove_Nth_Node_From_End_of_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)|
|[146. LRU Cache](./questions/146.LRU_Cache(Medium).md)|Medium|[Link](https://leetcode.com/problems/lru-cache/)|
|[25. Reverse Nodes in k-Group](./questions/25.Reverse_Nodes_in_k-Group(Hard).md)|Hard|[Link](https://leetcode.com/problems/reverse-nodes-in-k-group/)|Python|
|[61. Rotate List](./questions/61.Rotate_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/rotate-list/)|Python, C++|
|[23. Merge k Sorted Lists](./questions/23.Merge_k_Sorted_Lists(Hard).md)|Hard|[Link](https://leetcode.com/problems/merge-k-sorted-lists/)|Python, C++|

<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Binary Tree General

Binary Tree Problems usually can use Recursion to solve, start from the root, then recurse on its left subtree and right subtree to check three conditons: 1. if `not left and not right` (when both are None). 2. if `not left or not right` (when one of the node is None, not match). 3. if `left.val != right.val` (values are not the same, not match).

It is also convention to use **BFS** (queue), **DFS** (stack) to check each node with the above three conditions.

|Binary Tree General|||
|---|---|---|
|[104. Maximum Depth of Binary Tree](./questions/104.Maximum_Depth_of_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/maximum-depth-of-binary-tree/)|
|[100. Same Tree](./questions/100.Same_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/same-tree/)|
|[226. Invert Binary Tree](./questions/226.Invert_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/invert-binary-tree/)|
|[101. Symmetric Tree](./questions/101.Symmetric_Tree(Easy).md)|Easy|[Link](https://leetcode.com/problems/symmetric-tree/)|
|[105. Construct Binary Tree from Preorder and Inorder Traversal](./questions/105.Construct_Binary_Tree_from_Preorder_and_Inorder_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)|
|[106. Construct Binary Tree from Inorder and Postorder Traversal](./questions/106.Construct_Binary_Tree_from_Inorder_and_Postorder_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/)|
|[222. Count Complete Tree Nodes](./questions/222.Count_Complete_Tree_Nodes(Easy).md)|Easy|[Link](https://leetcode.com/problems/count-complete-tree-nodes/)|
|[112. Path Sum](./questions/112.Path_Sum(Easy).md)|Easy|[Link](https://leetcode.com/problems/path-sum/)|
|[236. Lowest Common Ancestor of a Binary Tree](./questions/236.Lowest_Common_Ancestor_of_a_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)|
|[124. Binary Tree Maximum Path Sum](./questions/124.Binary_Tree_Maximum_Path_Sum(Hard).md)|Hard|[Link](https://leetcode.com/problems/binary-tree-maximum-path-sum/)|


<!--
|[]()|Easy|[Link]()|
-->
<br>

---

### Binary Tree BFS

BFS uses `collections.queue()` and follows **FIFO**, DFS uses `stack()` and follows **LIFO**, both BFS and DFS can be implemented by `list()`.

|Binary Tree BFS|||
|---|---|---|
|[199. Binary Tree Right Side View](./questions/199.Binary_Tree_Right_Side_View_(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-right-side-view/)|
|[637. Average of Levels in Binary Tree](./questions/637.Average_of_Levels_in_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/average-of-levels-in-binary-tree/)|
|[102. Binary Tree Level Order Traversal](./questions/102.Binary_Tree_Level_Order_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-level-order-traversal/)|
|[103. Binary Tree Zigzag Level Order Traversal](./questions/103.Binary_Tree_Zigzag_Level_Order_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)|


<!--
|[]()|Easy|[Link]()|
-->
<br>

---

### Binary Search Tree

Binary Search Tree (BST) has property that the nodes on the left of the root are smaller than the root, the nodes on the right of the root are greater than the root. So, in many cases we can implement the **DFS** to perform **In-order traversal**: left -> root -> right.

|Binary Search Tree|||
|---|---|---|
|[530. Minimum Absolute Difference in BST](./questions/530.Minimum_Absolute_Difference_in_BST_(Easy).md)|Easy|[Link](https://leetcode.com/problems/minimum-absolute-difference-in-bst/)|
|[230. Kth Smallest Element in a BST](./questions/230.Kth_Smallest_Element_in_a_BST_(Medium).md)|Medium|[Link](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)|
|[98. Validate Binary Search Tree](./questions/98.Validate_Binary_Search_Tree_(Medium).md)|Medium|[Link](https://leetcode.com/problems/validate-binary-search-tree/)|
|[235. Lowest Common Ancestor of a Binary Search Tree](./questions/235.Lowest_Common_Ancestor_of_a_Binary_Search_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)|
|[700. Search in a Binary Search Tree](./questions/700.Search_in_a_Binary_Search_Tree(Easy).md)|Easy|[Link](https://leetcode.com/problems/search-in-a-binary-search-tree/)|
|[450. Delete Node in a BST](./questions/450.Delete_Node_in_a_BST(Medium).md)|Medium|[Link](https://leetcode.com/problems/delete-node-in-a-bst/)|

<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Graph General

[130, 147] require reverse-thinking to start running DFS on edges and add grids for some specific requirements. For other types of questions, we can run **DFS** or **BFS** iteratively to solve.

|Graph General||||
|---|---|---|---|
|Problems|Difficulty|Link|Languages|
|[200. Number of Islands](./questions/200.Number_of_Islands_(Medium).md)|Medium|[Link](https://leetcode.com/problems/number-of-islands/)|Python, C++|
|[695. Max Area of Island](./questions/695.Max_Area_of_Island(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-area-of-island/)|Python, Java|
|[207. Course Schedule](./questions/207.Course_Schedule_(Medium).md)|Medium|[Link](https://leetcode.com/problems/course-schedule/)|Python|
|[210. Course Schedule II](./questions/210.Course_Schedule_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/course-schedule-ii/)|Python|
|[130. Surrounded Regions](./questions/130.Surrounded_Regions(Medium).md)|Medium|[Link](https://leetcode.com/problems/surrounded-regions/)|Python|
|[417. Pacific Atlantic Water Flow](./questions/417.Pacific_Atlantic_Water_Flow(Medium).md)|Medium|[Link](https://leetcode.com/problems/pacific-atlantic-water-flow/)|Python|
|[133. Clone Graph](./questions/133.Clone_Graph(Medium).md)|Medium|[Link](https://leetcode.com/problems/clone-graph/)|Python|
|[399. Evaluate Division](./questions/399.Evaluate_Division(Medium).md)|Medium|[Link](https://leetcode.com/problems/evaluate-division/)|Python|
|[]()|Hard|[Link]()|


<!--
|[]()|Medium|[Link]()|
-->
<br>

___

### Trie
|Trie|||
|---|---|---|
|[208. Implement Trie (Prefix Tree)](./questions/208.Implement_Trie_(Medium).md)|Medium|[Link](https://leetcode.com/problems/implement-trie-prefix-tree)|


<!--
|[]()|Easy|[Link]()|
-->

<br>

---

### Intervals

|Intervals|||
|---|---|---|
|[57. Insert Interval](./questions/57.Insert_Interval_(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-interval/)|


<!--
|[]()|Easy|[Link]()|
-->

<br>

---
  
### Hashmap

In general, create a hashmap {} and store elements and their indices into the hashmap as the for-loop goes, then in the for loop we check if an element has already in the hashmap or not, or in the case we want to decrement the number of times we have seen an element in the hashmap.

|Hashmap|||
|---|---|---|
|[1. Two Sum](./questions/1.Two_Sum_(Easy).md)|Easy|[Link](https://leetcode.com/problems/two-sum/)|
|[219. Contains Duplicate II](./questions/219.Contains_Duplicate_II_(Easy).md)|Easy|[Link](https://leetcode.com/problems/contains-duplicate-ii/)|
|[383. Ransom Note](./questions/383.Ransom_Note_(Easy).md)|Easy|[Link](https://leetcode.com/problems/ransom-note/)|
|[242. Valid Anagram](./questions/242.Valid_Anagram(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-anagram/)|

<!--
|[]()|Easy|[Link]()|
-->

<br>

---

### Divide & Conquer

|Divide & Conquer|||
|---|---|---|
|[108. Convert Sorted Array to Binary Search Tree](./questions/108.Convert_Sorted_Array_to_Binary_Search_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)|
|[148. Sort List](./questions/148.Sort_List_(Medium).md)|Medium|[Link](https://leetcode.com/problems/sort-list/)|

<br>

---

### Kadane's Algorithm

|Kadane's Algorithm|||
|---|---|---|

<br>

---

### Heap

Create a minHeap, heapify the given array, `heapq.heappop()` until there are `k` elements in the minHeap. If we have `heapq.heappush()`, remember to keep the `k` elements by `pop()` out the same number of elements we `push()`. Finally, return the first element of the minHeap, which is the `k` largest element.

|Heap|||
|---|---|---|
|[703. Kth Largest Element in a Stream](./questions/703.Kth_Largest_Element_in_a_Stream_(Easy).md)|Easy|[Link](https://leetcode.com/problems/kth-largest-element-in-a-stream/)|
|[215. Kth Largest Element in an Array](./questions/215.Kth_Largest_Element_in_an_Array_(Medium).md)|Medium|[Link](https://leetcode.com/problems/kth-largest-element-in-an-array/)|


<!--
|[]()|Easy|[Link]()|
-->
<br>

---

### Bit Manipulation

For this type of question, we usually need to perform `&, |` (and, or) operation elementwise, and maybe need to shift bit by `n >> 1` or `n << 1` to move bits. Sometimes, we may need to start comparing two binary string **backward**, then return the reversed `[::-1]` version.

|Bit Manipulation|||
|---|---|---|
|[136. Single Number](./questions/136.Single_Number_(Easy).md)|Easy|[Link](https://leetcode.com/problems/single-number/)|
|[191. Number of 1 Bits](./questions/191.Number_of_1_bits_(Easy).md)|Easy|[Link](https://leetcode.com/problems/number-of-1-bits/)|
|[190. Reverse Bits](./questions/190.Reverse_Bits_(Easy).md)|Easy|[Link](https://leetcode.com/problems/reverse-bits/)|
|[67. Add Binary](./questions/67.Add_Binary_(Easy).md)|Easy|[Link](https://leetcode.com/problems/add-binary/)|


<!--
|[]()|Easy|[Link]()|
-->
<br>

---

### Math

|Math|||
|---|---|---|
|[9. Palindrome Number](./questions/9.Palindrome_Number_(Easy).md)|Easy|[Link](https://leetcode.com/problems/palindrome-number/)|
|[66. Plus One](./questions/66.Plus_One_(Easy).md)|Easy|[Link](https://leetcode.com/problems/plus-one/)|


<!--
|[]()|Easy|[Link]()|
-->
<br>

---

### Greedy
|Greedy|||
|---|---|---|
|[55. Jump Game](./questions/55.Jump_Game_(Medium).md)|Medium|[Link](https://leetcode.com/problems/jump-game/)|


<!--
|[]()|Easy|[Link]()|
-->
<br>

___

### 1D DP

Similar to 2D DP, in 1D DP we only create a dictionary {} for cache, save time complexity to check repeated cases.

|1D DP|||
|---|---|---|
|[70. Climbing Stairs](./questions/70.Climbing_Stairs_(Easy).md)|Easy|[Link](https://leetcode.com/problems/climbing-stairs/)|
|[10. Regular Expression Matching](./questions/10.Regular_Expression_Matching_(Hard).md)|Hard|[Link](https://leetcode.com/problems/regular-expression-matching/)|
|[198. House Robber](./questions/198.House_Robber_(Medium).md)|Medium|[Link](https://leetcode.com/problems/house-robber/)|
|[139. Word Break](./questions/139.Word_Break_(Medium).md)|Medium|[Link](https://leetcode.com/problems/word-break/)|

<br>

---

### 2D DP

In 2D DP, we usually need to create a dP table, then we start filling out the entries by bottom-up method taking sum or choosing the minimum entry from right, below, or diagonal. But before that, we need to find a pattern first, then apply pattern to the dP table.

|2D DP|||
|---|---|---|
|[62. Unique Paths](./questions/62.Unique_Paths_(Medium).md)|Medium|[Link](https://leetcode.com/problems/unique-paths/)|
|[72. Edit Distance](./questions/72.Edit_Distance_(Medium).md)|Medium|[Link](https://leetcode.com/problems/edit-distance/)|

<br>

___

### Multidimensional DP

|Multidimensional DP|||
|---|---|---|

<br>

---

### Others

|Others|||
|---|---|---|
|[217. Contains Duplicate](./questions/217.Contains_Duplicate_(Easy).md)|Easy|[Link](https://leetcode.com/problems/contains-duplicate/)|
|[239. Sliding Window Maximum](./questions/239.Sliding_Window_Maximum(Hard).md)|Hard|[Link](https://leetcode.com/problems/sliding-window-maximum/)|
|[287. Find the Duplicate Number](./questions/287.Find_the_Duplicate_Number(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-the-duplicate-number/)|

<!--
|[]()|Easy|[Link]()|
-->

<br> <br>

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt="CC BY-NC-SA" title="CC BY-NC-SA"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt="BY: credit must be given to the creator" title="BY: credit must be given to the creator"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt="NC: Only noncommercial uses of the work are permitted" title="NC: Only noncommercial uses of the work are permitted"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt="SA: Adaptations must be shared under the same terms" title="SA: Adaptations must be shared under the same terms">