## Leetcode problems I solved by topics with explanations

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
- [Advanced Graph (Shortest Path)](https://github.com/JC01111/Leetcode?tab=readme-ov-file#advanced-graph-shortest-path)
- [Trie](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#trie)
- [Intervals](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#intervals)
- [Hashmap](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#hashmap)
- [Divide & Conquer](https://github.com/JC01111/Leetcode_I_Solved/tree/main?tab=readme-ov-file#divide--conquer)
- [Greedy](https://github.com/JC01111/Leetcode_I_Solved#greedy)
- [Kadane's Algorithm](https://github.com/JC01111/Leetcode_I_Solved/tree/main?tab=readme-ov-file#kadanes-algorithm)
- [1D DP](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#1d-dp)
- [2D DP](https://github.com/JC01111/Leetcode_I_Solved#2d-dp)
- [Heap](https://github.com/JC01111/Leetcode?tab=readme-ov-file#heap--priority-queue)
- [Bit Manupulation](https://github.com/JC01111/Leetcode_I_Solved/tree/main?tab=readme-ov-file#bit-manipulation)
- [Math](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#math)
- [Others](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#others)

<br>

___

### Array / String

General cases we want to replace element with non-repeating element in `nums`, so we set an index to keep track of repeating position.

|Array / String|||||
|---|---|---|---|---|
|LeetCode 150|||
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
|[1380. Lucky Numbers in a Matrix](./questions/1380.Lucky_Numbers_in_a_Matrix(Easy).md)|Easy|[Link](https://leetcode.com/problems/lucky-numbers-in-a-matrix/)|Python|Cisco|
|[274. H-Index](./questions/274.H-Index(Medium).md)|Medium|[Link](https://leetcode.com/problems/h-index/)|
|[13. Roman to Integer](./questions/13.Roman_to_Integer(Easy).md)|Easy|[Link](https://leetcode.com/problems/roman-to-integer/)|
|[12. Integer to Roman](./questions/12.Integer_to_Roman(Medium).md)|Medium|[Link](https://leetcode.com/problems/integer-to-roman/)|
|[28. Find the Index of the First Occurrence in a String](./questions/28.Find_the_Index_of_the_First_Occurrence_in_a_String(Easy).md)|Easy|[Link](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/)|
|[380. Insert Delete GetRandom O(1)](./questions/380.Insert_Delete_GetRandom_O(1)(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-delete-getrandom-o1/)|
|[135. Candy](./questions/135.Candy(Hard).md)|Hard|[Link](https://leetcode.com/problems/candy/)|
|Blind 75|||
|[217. Contains Duplicate](./questions/217.Contains_Duplicate_(Easy).md)|Easy|[Link](https://leetcode.com/problems/contains-duplicate/)|
|[1. Two Sum](./questions/1.Two_Sum_(Easy).md)|Easy|[Link](https://leetcode.com/problems/two-sum/)|Python|Amazon|
|[49. Group Anagrams](./questions/49.Group_Anagrams(Medium).md)|Medium|[Link](https://leetcode.com/problems/group-anagrams/)|
|[347. Top K Frequent Elements](./questions/347.Top_K_Frequent_Elements(Medium).md)|Medium|[Link](https://leetcode.com/problems/top-k-frequent-elements/)|Python|Amazon|
|[692. Top K Frequent Words](./questions/692.Top_K_Frequent_Words(Medium).md)|Medium|[Link](https://leetcode.com/problems/top-k-frequent-words/)|Python|Amazon|
|[271. Encode and Decode Strings](./questions/271.Encode_and_Decode_Strings(Medium).md)|Medium|[Link](https://leetcode.com/problems/encode-and-decode-strings/)|
|[238. Product of Array Except Self](./questions/238.Product_of_Array_Except_Self(Medium).md)|Medium|[Link](https://leetcode.com/problems/product-of-array-except-self/)|
|[128. Longest Consecutive Sequence](./questions/128.Longest_Consecutive_Sequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-consecutive-sequence/)|
|LeetCode 75|||||
|[1768. Merge Strings Alternately](./questions/1768.Merge_Strings_Alternately(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-strings-alternately/)|
|[1071. Greatest Common Divisor of Strings](./questions/1071.Greatest_Common_Divisor_of_Strings(Easy).md)|Easy|[Link](https://leetcode.com/problems/greatest-common-divisor-of-strings/)|
|[1431. Kids With the Greatest Number of Candies](./questions/1431.Kids_With_the_Greatest_Number_of_Candies(Easy).md)|Easy|[Link](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/)||Easy Not worthy to redo|
|[605. Can Place Flowers](./questions/605.Can_Place_Flowers(Easy).md)|Easy|[Link](https://leetcode.com/problems/can-place-flowers/)|
|[345. Reverse Vowels of a String](./questions/345.Reverse_Vowels_of_a_String(Easy).md)|Easy|[Link](https://leetcode.com/problems/reverse-vowels-of-a-string/)|
|[334. Increasing Triplet Subsequence](./questions/334.Increasing_Triplet_Subsequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/increasing-triplet-subsequence/)|
|[443. String Compression](./questions/443.String_Compression(Medium).md)|Medium|[Link](https://leetcode.com/problems/string-compression/)|
|Miscellaneous||||
|[179. Largest Number](./questions/179.Largest_Number(Medium).md)|Medium|[Link](https://leetcode.com/problems/largest-number/description/)|Python|Google OA|
|[1827. Minimum Operations to Make the Array Increasing](./questions/1827.Minimum_Operations_to_Make_the_Array_Increasing(Easy).md)|Easy|[Link](https://leetcode.com/problems/minimum-operations-to-make-the-array-increasing/description/)|Python|Google OA|


<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Two Pointers

Two pointers can save space complexity, because it only uses constant space complexity $O(1)$. Usually use `l, r` pointers and either increment `l` or decrement `r` depends on the current `sum` compare with `target` value.

|Two Pointers|||||
|---|---|---|---|---|
|[125. Valid Palindrome](./questions/125.Valid_Palindrome_(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-palindrome/)|
|[167. Two Sum II - Input Array Is Sorted](./questions/167.Two_Sum_II_(Medium).md)|Medium|[Link](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)|
|[392. Is Subsequence](./questions/392.Is_Subsequence(Easy).md)|Easy|[Link](https://leetcode.com/problems/is-subsequence/)|
|[11. Container With Most Water](./questions/11.Container_With_Most_Water(Medium).md)|Medium|[Link](https://leetcode.com/problems/container-with-most-water/)|
|[15. 3Sum](./questions/15.3Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/3sum/)|
|[1268. Search Suggestions System](./questions/1268.Search_Suggestions_System(Medium).md)|Medium|[Link](https://leetcode.com/problems/search-suggestions-system/)|
|[5. Longest Palindromic Substring](./questions/5.Longest_Palindromic_Substring(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-palindromic-substring/)|Python|Amazon, Cisco|
|[283. Move Zeroes](./questions/283.Move_Zeroes(Easy).md)|Easy|[Link](https://leetcode.com/problems/move-zeroes/)|
|[1679. Max Number of K-Sum Pairs](./questions/1679.Max_Number_of_K-Sum_Pairs(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-number-of-k-sum-pairs/)|

<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Sliding Window

Sliding Window technique is similar to Two Pointers, usually use a left pointer as a "Pivot" to know where we start recently and then update `left += 1`. Sometimes we may need to use **hashmaps** to find substring.

|Sliding Window||||
|---|---|---|---|
|[3. Longest Substring Without Repeating Characters](./questions/3.Longest_Substring_Without_Repeating_Characters_(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-substring-without-repeating-characters/)|
|[121. Best Time to Buy and Sell Stock](./questions/121.Best_Time_to_Buy_and_Sell_Stock_(Easy).md)|Easy|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)|
|[53. Maximum Subarray](./questions/53.Maximum_Subarray_(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-subarray/)|
|[209. Minimum Size Subarray Sum](./questions/209.Minimum_Size_Subarray_Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-size-subarray-sum/)|
|[424. Longest Repeating Character Replacement](./questions/424.Longest_Repeating_Character_Replacement(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-repeating-character-replacement/)|
|[76. Minimum Window Substring](./questions/76.Minimum_Window_Substring(Hard).md)|Hard|[Link](https://leetcode.com/problems/minimum-window-substring/)|
|[239. Sliding Window Maximum](./questions/239.Sliding_Window_Maximum(Hard).md)|Hard|[Link](https://leetcode.com/problems/sliding-window-maximum/)|
|[567. Permutation in String](./questions/567.Permutation_in_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/permutation-in-string/)|
|LeetCode 75|||
|[643. Maximum Average Subarray I](./questions/643.Maximum_Average_Subarray_I(Easy).md)|Easy|[Link](https://leetcode.com/problems/maximum-average-subarray-i/)|
|[1456. Maximum Number of Vowels in a Substring of Given Length](./questions/1456.Maximum_Number_of_Vowels_in_a_Substring_of_Given_Length(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-number-of-vowels-in-a-substring-of-given-length/)|
|Miscellaneous|||
|[485. Max Consecutive Ones](./questions/485.Max_Consecutives_Ones(Easy).md)|Easy|[Link](https://leetcode.com/problems/max-consecutive-ones/)|
|[487. Max Consecutive Ones II](./questions/487.Max_Consecutive_Ones_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-consecutive-ones-ii/)|Similar to 1493|
|[1493. Longest Subarray of 1's After Deleting One Element](./questions/1493.Longest_Subarray_of_1's_After_Deleting_One_Element(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-subarray-of-1s-after-deleting-one-element/?envType=study-plan-v2&envId=leetcode-75)|Similar to 487|

<!--
|[]()|Medium|[Link]()|
-->
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


<!--
|[]()|Medium|[Link]()|
-->
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
|[108. Convert Sorted Array to Binary Search Tree](./questions/108.Convert_Sorted_Array_to_Binary_Search_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)|
|[235. Lowest Common Ancestor of a Binary Search Tree](./questions/235.Lowest_Common_Ancestor_of_a_Binary_Search_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)|
|[700. Search in a Binary Search Tree](./questions/700.Search_in_a_Binary_Search_Tree(Easy).md)|Easy|[Link](https://leetcode.com/problems/search-in-a-binary-search-tree/)|
|[450. Delete Node in a BST](./questions/450.Delete_Node_in_a_BST(Medium).md)|Medium|[Link](https://leetcode.com/problems/delete-node-in-a-bst/)|

<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Graph General

[286, 130, 417] require reverse-thinking to start running DFS on edges and add grids for some specific requirements. For other types of questions, we can run **DFS** or **BFS** iteratively to solve.

|Graph General||||
|---|---|---|---|
|[200. Number of Islands](./questions/200.Number_of_Islands_(Medium).md)|Medium|[Link](https://leetcode.com/problems/number-of-islands/)|Python, C++|
|[695. Max Area of Island](./questions/695.Max_Area_of_Island(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-area-of-island/)|Python, Java|
|[207. Course Schedule](./questions/207.Course_Schedule_(Medium).md)|Medium|[Link](https://leetcode.com/problems/course-schedule/)|Python|
|[210. Course Schedule II](./questions/210.Course_Schedule_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/course-schedule-ii/)|Python|
|[130. Surrounded Regions](./questions/130.Surrounded_Regions(Medium).md)|Medium|[Link](https://leetcode.com/problems/surrounded-regions/)|Python|
|[286. Walls and Gates](./questions/286.Walls_and_Gates(Medium).md)|Medium|[Link](https://leetcode.com/problems/walls-and-gates/)|Graph BFS|
|[417. Pacific Atlantic Water Flow](./questions/417.Pacific_Atlantic_Water_Flow(Medium).md)|Medium|[Link](https://leetcode.com/problems/pacific-atlantic-water-flow/)|Python|
|[133. Clone Graph](./questions/133.Clone_Graph(Medium).md)|Medium|[Link](https://leetcode.com/problems/clone-graph/)|Python|
|[399. Evaluate Division](./questions/399.Evaluate_Division(Medium).md)|Medium|[Link](https://leetcode.com/problems/evaluate-division/)|Python|
|LeetCode 150||||
|[909. Snakes and Ladders](./questions/909.Snakes_and_Ladders(Medium).md)|Medium|[Link](https://leetcode.com/problems/snakes-and-ladders/)|Graph BFS|
|[127. Word Ladder](./questions/127.Word_Ladder(Hard).md)|Hard|[Link](https://leetcode.com/problems/word-ladder/)|Graph BFS|
|[433. Minimum Genetic Mutation](./questions/433.Minimum_Genetic_Mutation(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-genetic-mutation/)|Graph BFS|
|LeetCode 75|||
|[841. Keys and Rooms](./questions/841.Keys_and_Rooms(Medium).md)|Medium|[Link](https://leetcode.com/problems/keys-and-rooms/)|Graph DFS|
|[547. Number of Provinces](./questions/547.Number_of_Provinces(Medium).md)|Medium|[Link](https://leetcode.com/problems/number-of-provinces/)|Graph DFS|
|[1466. Reorder Routes to Make All Paths Lead to the City Zero](./questions/1466.Reorder_Routes_to_Make_All_Paths_Lead_to_the_City_Zero(Medium).md)|Medium|[Link](https://leetcode.com/problems/reorder-routes-to-make-all-paths-lead-to-the-city-zero/)|Graph DFS|
|[994. Rotting Oranges](./questions/994.Rotting_Oranges(Medium).md)|Medium|[Link](https://leetcode.com/problems/rotting-oranges/)|Graph BFS|
|[1926. Nearest Exit from Entrance in Maze](./questions/1926.Nearest_Exit_from_Entrance_in_Maze(Medium).md)|Medium|[Link](https://leetcode.com/problems/nearest-exit-from-entrance-in-maze/)|Graph BFS|


<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Advanced Graph (Shortest Path)
|Advanced Graph||||
|---|---|---|---|
|[743. Network Delay Time](./questions/743.Network_Delay_Time(Medium).md)|Medium|[Link](https://leetcode.com/problems/network-delay-time/)| Dijkstra's|
|[787. Cheapest Flights Within K Stops](./questions/787.Cheapest_Flights_Within_K_Stops(Medium).md)|Medium|[Link](https://leetcode.com/problems/cheapest-flights-within-k-stops/)|Bellman Ford|
|[269. Alien Dictionary](./questions/269.Alien_Dictionary(Hard).md)|Hard|[Link](https://leetcode.com/problems/alien-dictionary/)|Topological Sort/Post-order DFS|


<!--
|[]()|Medium|[Link]()|
-->
<br>

___

### Trie
|Trie|||
|---|---|---|
|[208. Implement Trie (Prefix Tree)](./questions/208.Implement_Trie_(Medium).md)|Medium|[Link](https://leetcode.com/problems/implement-trie-prefix-tree)|
|[211. Design Add and Search Words Data Structure](./questions/211.Design_Add_and_Search_Words_Data_Structure(Medium).md)|Medium|[Link](https://leetcode.com/problems/design-add-and-search-words-data-structure/)|
|[212. Word Search II](./questions/212.Word_Search_II(Hard).md)|Hard|[Link](https://leetcode.com/problems/word-search-ii/)|
|[1268. Search Suggestions System](./questions/1268.Search_Suggestions_System(Medium).md)|Medium|[Link](https://leetcode.com/problems/search-suggestions-system/)|


<!--
|[]()|Medium|[Link]()|
-->

<br>

---

### Intervals

Usually, we need to sort the array first to better find the overlapping intervals. We compare two intervals with the last element of the interval and the first element of another interval to know whether they are overlapped or not.

|Intervals|||
|---|---|---|
|[56. Merge Intervals](./questions/56.Merge_Intervals(Medium).md)|Medium|[Link](https://leetcode.com/problems/merge-intervals/)|
|[57. Insert Interval](./questions/57.Insert_Interval_(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-interval/)|
|[435. Non-overlapping Intervals](./questions/435.Non-overlapping_Intervals(Medium).md)|Medium|[Link](https://leetcode.com/problems/non-overlapping-intervals/)|
|[228. Summary Ranges](./questions/228.Summary_Ranges(Easy).md)|Easy|[Link](https://leetcode.com/problems/summary-ranges/)|
|[452. Minimum Number of Arrows to Burst Balloons](./questions/452.Minimum_Number_of_Arrows_to_Burst_Balloons(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)|
|[1851. Minimum Interval to Include Each Query](./questions/1851.Minimum_Interval_to_Include_Each_Query(Hard).md)|Hard|[Link](https://leetcode.com/problems/minimum-interval-to-include-each-query/)|


<!--
|[]()|Medium|[Link]()|
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

In most cases, we need to first find the mid point by `len(nums) // 2`, then recursively pass in mid point's left and right.
<br> **Divide & Conquer** means we first divide the problem into several subproblems, we solve them and them merge teh results together.

|Divide & Conquer|||
|---|---|---|
|[108. Convert Sorted Array to Binary Search Tree](./questions/108.Convert_Sorted_Array_to_Binary_Search_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)|
|[148. Sort List](./questions/148.Sort_List_(Medium).md)|Medium|[Link](https://leetcode.com/problems/sort-list/)|
|[427. Construct Quad Tree](./questions/427.Construct_Quad_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/construct-quad-tree/)|


<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Greedy

Greedy problems are hard to identify pattern, but one type of them can be solved by **Kadane's Algorithm**.

|Greedy|||
|---|---|---|
|[53. Maximum Subarray](./questions/53.Maximum_Subarray_(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-subarray/)|
|[55. Jump Game](./questions/55.Jump_Game_(Medium).md)|Medium|[Link](https://leetcode.com/problems/jump-game/)|
|[45. Jump Game II](./questions/45.Jump_Game_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/jump-game-ii/)|
|[134. Gas Station](./questions/134.Gas_Station(Medium).md)|Medium|[Link](https://leetcode.com/problems/gas-station/)|
|[846. Hand of Straights](./questions/846.Hand_of_Straights(Medium).md)|Medium|[Link](https://leetcode.com/problems/hand-of-straights/)|
|[1296. Divide Array in Sets of K Consecutive Numbers](./questions/1296.Divide_Array_in_Sets_of_K_Consecutive_Numbers(Medium).md)|Medium|[Link](https://leetcode.com/problems/divide-array-in-sets-of-k-consecutive-numbers/)|
|[763. Partition Labels](./questions/763.Partition_Labels(Medium).md)|Medium|[Link](https://leetcode.com/problems/partition-labels/)|
|[678. Valid Parenthesis String](./questions/678.Valid_Parenthesis_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/valid-parenthesis-string/)|
|[1899. Merge Triplets to Form Target Triplet](./questions/1899.Merge_Triplets_to_Form_Target_Triplet(Medium).md)|Medium|[Link](https://leetcode.com/problems/merge-triplets-to-form-target-triplet/)|


<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Kadane's Algorithm
Kadane's Algorithm maintains a `curSum` which keep tracks of contiguous summation, it is always `0` if the `curSum + nums[i] < 0`, which means we will not take this element at index `i`. If `curSum > 0` we will keep unpdating `curSum += nums[i]` and update `maxSum = max(maxSum, curSum)`. This is the standard approach of Kadane's algorithm.

|Kadane's Algorithm|||
|---|---|---|
|[53. Maximum Subarray](./questions/53.Maximum_Subarray_(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-subarray/)|
|[134. Gas Station](./questions/134.Gas_Station(Medium).md)|Medium|[Link](https://leetcode.com/problems/gas-station/)|


<br>

___

### 1D DP

1D DP creates dictionary{} or list[] for cache, save time complexity to check repeated cases.

|1D DP|||
|---|---|---|
|[70. Climbing Stairs](./questions/70.Climbing_Stairs_(Easy).md)|Easy|[Link](https://leetcode.com/problems/climbing-stairs/)|
|[746. Min Cost Climbing Stairs](./questions/746.Min_Cost_Climbing_Stairs(Easy).md)|Easy|[Link](https://leetcode.com/problems/min-cost-climbing-stairs/)|
|[1137. N-th Tribonacci Number](./questions/1137.N-th_Tribonacci_Number(Easy).md)|Easy|[Link](https://leetcode.com/problems/n-th-tribonacci-number/)|
|[198. House Robber](./questions/198.House_Robber_(Medium).md)|Medium|[Link](https://leetcode.com/problems/house-robber/)|
|[139. Word Break](./questions/139.Word_Break_(Medium).md)|Medium|[Link](https://leetcode.com/problems/word-break/)|
|[300. Longest Increasing Subsequence](./questions/300.Longest_Increasing_Subsequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-increasing-subsequence/)|
|[322. Coin Change](./questions/322.Coin_Change(Medium).md)|Medium|[Link](https://leetcode.com/problems/coin-change/)|
|[10. Regular Expression Matching](./questions/10.Regular_Expression_Matching_(Hard).md)|Hard|[Link](https://leetcode.com/problems/regular-expression-matching/)|
|[790. Domino and Tromino Tiling](./questions/790.Domino_and_Tromino_Tiling(Medium).md)|Medium|[Link](https://leetcode.com/problems/domino-and-tromino-tiling/)|


<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### 2D DP

In 2D DP, we usually need to create a dP table, then we start filling out the entries by bottom-up method taking sum or choosing the minimum entry from right, below, or diagonal. But before that, we need to find a pattern first, then apply pattern to the dP table. **Usually**, we can reduce from storing the whole 2d table into only storing the previous row/col.

|2D DP|||
|---|---|---|
|[62. Unique Paths](./questions/62.Unique_Paths_(Medium).md)|Medium|[Link](https://leetcode.com/problems/unique-paths/)|
|[72. Edit Distance](./questions/72.Edit_Distance_(Medium).md)|Medium|[Link](https://leetcode.com/problems/edit-distance/)|
|[1143. Longest Common Subsequence](./questions/1143.Longest_Common_Subsequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-common-subsequence/)|
|[518. Coin Change II](./questions/518.Coin_Change_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/coin-change-ii/)|
|[97. Interleaving String](./questions/97.Interleaving_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/interleaving-string/)|
|[309. Best Time to Buy and Sell Stock with Cooldown](./questions/309.Best_Time_to_Buy_and_Sell_Stock_with_Cooldown(Medium).md)|Medium|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/)|
|[714. Best Time to Buy and Sell Stock with Transaction Fee](./questions/714.Best_Time_to_Buy_and_Sell_Stock_with_Transaction_Fee(Medium).md)|Medium|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/)|


<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Heap / Priority Queue

Usually we need to use create a `heap = []`, then use `heapq.heapify` or just `heapq.heappush` to make that heap becomes a `minHeap` by default. If we want a `maxHeap`, we need to store the negative value `heapq.heappush(maxHeap, -i)`, so the top will be the max value, when we pop the element, remember to **negate** it back.

|Heap|||||
|---|---|---|---|---|
|[703. Kth Largest Element in a Stream](./questions/703.Kth_Largest_Element_in_a_Stream_(Easy).md)|Easy|[Link](https://leetcode.com/problems/kth-largest-element-in-a-stream/)|
|[215. Kth Largest Element in an Array](./questions/215.Kth_Largest_Element_in_an_Array_(Medium).md)|Medium|[Link](https://leetcode.com/problems/kth-largest-element-in-an-array/)|
|[1046. Last Stone Weight](./questions/1046.Last_Stone_Weight(Easy).md)|Easy|[Link](https://leetcode.com/problems/last-stone-weight/)|Python, Java, C++|
|[973. K Closest Points to Origin](./questions/973.K_Closest_Points_to_Origin(Medium).md)|Medium|[Link](https://leetcode.com/problems/k-closest-points-to-origin/)|Python|
|[295. Find Median from Data Stream](./questions/295.Find_Median_from_Data_Stream(Hard).md)|Hard|[Link](https://leetcode.com/problems/find-median-from-data-stream/)||Use two heaps|
|[502. IPO](./questions/502.IPO(Hard).md)|Hard|[Link](https://leetcode.com/problems/ipo/)|Python|Use two heaps|
|[621. Task Scheduler](./questions/621.Task_Scheduler(Medium).md)|Medium|[Link](https://leetcode.com/problems/task-scheduler/)|Python|Use heap and deque|
|[355. Design Twitter](./questions/355.Desgin_Twitter(Medium).md)|Medium|[Link](https://leetcode.com/problems/design-twitter/)|


<!--
|[]()|Medium|[Link]()|
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
|[371. Sum of Two Integers](./questions/371.Sum_of_Two_Integers(Medium).md)|Medium|[Link](https://leetcode.com/problems/sum-of-two-integers/)|



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
|[7. Reverse Integer](./questions/7.Reverse_Integer(Medium).md)|Medium|[Link](https://leetcode.com/problems/reverse-integer/)|

<!--
|[]()|Easy|[Link]()|
-->
<br>

---

### Others

|Others|||
|---|---|---|
|[239. Sliding Window Maximum](./questions/239.Sliding_Window_Maximum(Hard).md)|Hard|[Link](https://leetcode.com/problems/sliding-window-maximum/)|
|[287. Find the Duplicate Number](./questions/287.Find_the_Duplicate_Number(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-the-duplicate-number/)|

<!--
|[]()|Easy|[Link]()|
-->

<br> <br>

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt="CC BY-NC-SA" title="CC BY-NC-SA"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt="BY: credit must be given to the creator" title="BY: credit must be given to the creator"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt="NC: Only noncommercial uses of the work are permitted" title="NC: Only noncommercial uses of the work are permitted"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt="SA: Adaptations must be shared under the same terms" title="SA: Adaptations must be shared under the same terms">