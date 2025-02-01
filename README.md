<!--
Template
|Topic||||
|---|---|---|---|
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
- [Monotonic Stack](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#monotonic-stack)
- [Linked List](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#linked-list)
- [Binary Tree General](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#binary-tree-general)
- [Binary Tree BFS](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#binary-tree-bfs)
- [Binary Tree DFS](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#binary-tree-dfs)
- [Binary Search Tree](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#binary-search-tree)
- [Graph General](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#graph-general)
- [Advanced Graph (Shortest Path)](https://github.com/JC01111/Leetcode?tab=readme-ov-file#advanced-graph-shortest-path)
- [Union Find (Disjoint Set)](https://github.com/JC01111/Leetcode?tab=readme-ov-file#union-find-disjoint-set)
- [Trie](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#trie)
- [Intervals](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#intervals)
- [Hashmap](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#hashmap)
- [Queue](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#queue)
- [Divide & Conquer](https://github.com/JC01111/Leetcode_I_Solved/tree/main?tab=readme-ov-file#divide--conquer)
- [Greedy](https://github.com/JC01111/Leetcode_I_Solved#greedy)
- [Kadane's Algorithm](https://github.com/JC01111/Leetcode_I_Solved/tree/main?tab=readme-ov-file#kadanes-algorithm)
- [1D DP](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#1d-dp)
- [2D DP](https://github.com/JC01111/Leetcode_I_Solved#2d-dp)
- [Heap](https://github.com/JC01111/Leetcode?tab=readme-ov-file#heap)
- [Prefix Sum](https://github.com/JC01111/Leetcode?tab=readme-ov-file#prefix-sum)
- [Bit Manupulation](https://github.com/JC01111/Leetcode_I_Solved/tree/main?tab=readme-ov-file#bit-manipulation)
- [Math](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#math)

### Tag Questions
- [Meta](https://github.com/JC01111/Leetcode_I_Solved?tab=readme-ov-file#meta-tag)

<br>

___

### Array / String

General cases we want to replace element with non-repeating element in `nums`, so we set an index to keep track of repeating position.

|Array / String|||||
|---|---|---|---|---|
|LeetCode 150|||
|[88. Merge Sorted Array](./questions/88.Merge_Sorted_Array_(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-sorted-array/)|Meta Tag|Compare nums1, nums2 backward and add the larger value into the end of nums1, use three pointers to keep track|
|[27. Remove Element](./questions/27.Remove_Element_(Easy).md)|Easy|[Link](https://leetcode.com/problems/remove-element/)||Use pointer to keep track of non-val element and replace the index when i != val to remove the val in nums|
|[26. Remove Duplicates from Sorted Array](./questions/26.Remove_Duplicates_from_Sorted_Array_(Easy).md)|Easy|[Link](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)||Similar to 27, keep track of prev elem, if current n != prev, replace nums[k] = n, update prev = n|
|[80. Remove Duplicates from Sorted Array II](./questions/80.Remove_Duplicates_from_Sorted_Array_II_(Medium).md)|Medium|[Link](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/)|
|[169. Majority Element](./questions/169.Majority_Element_(Easy).md)|Easy|[Link](https://leetcode.com/problems/majority-element/)||Use two variables to keep track of curMax element and its count, decrement count if current elem != val, when count == 0, update curMax = i. Otherwise, increment count|
|[189. Rotate Array](./questions/189.Rotate_Array_(Medium).md)|Mediun|[Link](https://leetcode.com/problems/rotate-array/)||Reverse nums and reverse nums[:k], same as rotate the array to the right by k steps|
|[121. Best Time to Buy and Sell Stock](./questions/121.Best_Time_to_Buy_and_Sell_Stock_(Easy).md)|Easy|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)|
|[122. Best Time to Buy and Sell Stock II](./questions/122.Best_Time_to_Buy_and_Sell_Stock_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/)|
|[45. Jump Game II](./questions/45.Jump_Game_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/jump-game-ii/)||Use l, r ptrs to find a reachable range, update farthest variable within the range, update l = r + 1, r = farthest, update jumps by 1|
|[14. Longest Common Prefix](./questions/14.Longest_Common_Prefix(Easy).md)|Easy|[Link](https://leetcode.com/problems/longest-common-prefix/)|
|[58. Length of Last Word](./questions/58.Length_of_Last_Word(Easy).md)|Easy|[Link](https://leetcode.com/problems/length-of-last-word/)|
|[151. Reverse Words in a String](./questions/151.Reverse_Words_in_a_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/reverse-words-in-a-string/)|
|[42. Trapping Rain Water](./questions/42.Trapping_Rain_Water(Hard).md)|Hard|[Link](https://leetcode.com/problems/trapping-rain-water/)||Use l, r pointers to update maxLeft, maxRight, update res += maxLeft - height[l] or by maxRight, then we update maxLeft, maxRight to a greater value from height[l], height[r]|
|[6. Zigzag Conversion](./questions/6.Zigzag_Conversion(Medium).md)|Medium|[Link](https://leetcode.com/problems/zigzag-conversion/)||Find the distance to get another char on the same row. Use the normal interval - (current row * 2) to get the extra char on each interval|
|[68. Text Justification](./questions/68.Text_Justification(Hard).md)|Hard|[Link](https://leetcode.com/problems/text-justification/)||For each row with maxWidth, repeatly add words until a new word cannot be added. Then we compute how many spaces we need to assign after each word|
|[1380. Lucky Numbers in a Matrix](./questions/1380.Lucky_Numbers_in_a_Matrix(Easy).md)|Easy|[Link](https://leetcode.com/problems/lucky-numbers-in-a-matrix/)|Cisco|
|[274. H-Index](./questions/274.H-Index(Medium).md)|Medium|[Link](https://leetcode.com/problems/h-index/)||Sort citations in descending order, find when index >= citation, or return len(citations) in the end|
|[13. Roman to Integer](./questions/13.Roman_to_Integer(Easy).md)|Easy|[Link](https://leetcode.com/problems/roman-to-integer/)|
|[12. Integer to Roman](./questions/12.Integer_to_Roman(Medium).md)|Medium|[Link](https://leetcode.com/problems/integer-to-roman/)|
|[28. Find the Index of the First Occurrence in a String](./questions/28.Find_the_Index_of_the_First_Occurrence_in_a_String(Easy).md)|Easy|[Link](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/)||Brute Force to try each haystack[i:i + len(needle)] == needle|
|[380. Insert Delete GetRandom O(1)](./questions/380.Insert_Delete_GetRandom_O(1)(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-delete-getrandom-o1/)|
|[135. Candy](./questions/135.Candy(Hard).md)|Hard|[Link](https://leetcode.com/problems/candy/)||Similar to 238, initialize an array and traverse from left to right and right to left to compare their neighbor, and update res[i] accordingly|
|Blind 75|||
|[217. Contains Duplicate](./questions/217.Contains_Duplicate_(Easy).md)|Easy|[Link](https://leetcode.com/problems/contains-duplicate/)|
|[1. Two Sum](./questions/1.Two_Sum_(Easy).md)|Easy|[Link](https://leetcode.com/problems/two-sum/)|Amazon, Meta|Save the remainder (target - nums[i]) into hashmap, when a remainder exists in hashmap, return [i, hashmap[nums[i]]]|
|[347. Top K Frequent Elements](./questions/347.Top_K_Frequent_Elements(Medium).md)|Medium|[Link](https://leetcode.com/problems/top-k-frequent-elements/)|Amazon, Meta Tag|Count num with their counts, use minHeap to sort the counts then append num k times from minHeap to res[]|
|[692. Top K Frequent Words](./questions/692.Top_K_Frequent_Words(Medium).md)|Medium|[Link](https://leetcode.com/problems/top-k-frequent-words/)|Amazon|
|[271. Encode and Decode Strings](./questions/271.Encode_and_Decode_Strings(Medium).md)|Medium|[Link](https://leetcode.com/problems/encode-and-decode-strings/)|
|[238. Product of Array Except Self](./questions/238.Product_of_Array_Except_Self(Medium).md)|Medium|[Link](https://leetcode.com/problems/product-of-array-except-self/)||Maintain a list of left product, then traverse from right to left update with product, and update product * nums[i]|
|[128. Longest Consecutive Sequence](./questions/128.Longest_Consecutive_Sequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-consecutive-sequence/)||Convert `nums` to set() to avoid duplicate elements, then for each base element (check if n-1 in set), we increment by 1 each time when the total is in the set()|
|LeetCode 75|||||
|[1768. Merge Strings Alternately](./questions/1768.Merge_Strings_Alternately(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-strings-alternately/)|Meta|Use two ptrs to add chars from two strings alternatively, then check to add the remaining from `word1` or `word2`|
|[1071. Greatest Common Divisor of Strings](./questions/1071.Greatest_Common_Divisor_of_Strings(Easy).md)|Easy|[Link](https://leetcode.com/problems/greatest-common-divisor-of-strings/)|
|[1431. Kids With the Greatest Number of Candies](./questions/1431.Kids_With_the_Greatest_Number_of_Candies(Easy).md)|Easy|[Link](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/)||Easy Not worthy to redo|
|[605. Can Place Flowers](./questions/605.Can_Place_Flowers(Easy).md)|Easy|[Link](https://leetcode.com/problems/can-place-flowers/)|Meta|Append `0` to two ends of `flowerbed`, check `flowerbed[i]` and its neighbors are all `0` or not, if so, replace `0` to `1` and decrement `n`. Return `n <= 0`|
|[345. Reverse Vowels of a String](./questions/345.Reverse_Vowels_of_a_String(Easy).md)|Easy|[Link](https://leetcode.com/problems/reverse-vowels-of-a-string/)|
|[334. Increasing Triplet Subsequence](./questions/334.Increasing_Triplet_Subsequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/increasing-triplet-subsequence/)|
|[443. String Compression](./questions/443.String_Compression(Medium).md)|Medium|[Link](https://leetcode.com/problems/string-compression/)|
|Miscellaneous||||
|[179. Largest Number](./questions/179.Largest_Number(Medium).md)|Medium|[Link](https://leetcode.com/problems/largest-number/description/)|Google OA|
|[1827. Minimum Operations to Make the Array Increasing](./questions/1827.Minimum_Operations_to_Make_the_Array_Increasing(Easy).md)|Easy|[Link](https://leetcode.com/problems/minimum-operations-to-make-the-array-increasing/description/)|Google OA|
|[1526. Minimum Number of Increments on Subarrays to Form a Target Array](./questions/1526.Minimum_Number_of_Increments_on_Subarrays_to_Form_a_Target_Array(Hard).md)|Hard|[Link](https://leetcode.com/problems/minimum-number-of-increments-on-subarrays-to-form-a-target-array/)|Google OA|
|[3024. Type of Triangle](./questions/3024.Type_of_Triangle(Easy).md)|Easy|[Link](https://leetcode.com/problems/type-of-triangle/)|Google Tag|
|[2663. Lexicographically Smallest Beautiful String](./questions/2663.Lexicographically_Smallest_Beautiful_String(Hard).md)|Hard|[Link](https://leetcode.com/problems/lexicographically-smallest-beautiful-string/)|Google Tag|Increment the last element and check if current element within range of k letters, iterate to the left and make changes if needed|
|[1652. Defuse the Bomb](./questions/1652.Defuse_the_Bomb(Easy).md)|Easy|[Link](https://leetcode.com/problems/defuse-the-bomb/)||Use curr % len(code) to get the next k numbers, increment curr k times. Use len(code) + curr % len(code) to get previous k numbers, decrement curr k times|
|[408. Valid Word Abbreviation](./questions/408.Vaild_Word_Abbreviation(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-word-abbreviation?envType=company&envId=facebook&favoriteSlug=facebook-thirty-days)|Meta Tag|Use  pointer for each string to compare, if abbr[j].isdigit(), we extract the number and increment i += int(number)|
|[1570. Dot Product of Two Sparse Vectors](./questions/1570.Dot_Product_of_Two_Sparse_Vectors(Medium).md)|Medium|[Link](https://leetcode.com/problems/dot-product-of-two-sparse-vectors)|Meta Tag|Use hashmap to save nonzero element with its index as key to hashmap{}. Update res with an index exists in both hashmaps|
|[791. Custom Sort String](./questions/791.Custom_Sort_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/custom-sort-string)|Meta|Use hashmap to save each char in `s` with counts, traverse `order` and add char in hashmap with repeated times to `res`, traverse hashmap to add missing chars to res|
|[1762. Buildings With an Ocean View](./questions/1762.Buildings_With_an_Ocean_View(Medium).md)|Medium|[Link](https://leetcode.com/problems/buildings-with-an-ocean-view)|Meta|Traverse heights from right to left, save the last height as curMax, if heights[i] > curMax, update curMax and save its index into res[], finally, return the reversed res[]|
|[921. Minimum Add to Make Parentheses Valid](./questions/921.Minimum_Add_to_Make_Parentheses_Valid(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid)|Meta|Count "(" and ")", when encounter ")", check if we have "(" to remove or decrement, otherwise, increment the count of ")".|
|[65. Valid Number](./questions/65.Valid_Number(Hard).md)|Hard|[Link](https://leetcode.com/problems/valid-number)|Meta|Keep track of `seenDigit`, `seenExponent`, `seenDot`, then we check if the current char is valid base on some rules|
|[415. Add Strings](./questions/415.Add_Strings(Easy).md)|Easy|[Link](https://leetcode.com/problems/add-strings)|Meta|Use two ptrs to access two chars backward + carry to perform addition, and append the result to `[]`|
|[287. Find the Duplicate Number](./questions/287.Find_the_Duplicate_Number(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-the-duplicate-number/)||Fast and Slow method|
|[31. Next Permutation](./questions/31.Next_Permutation(Medium).md)|Medium|[Link](https://leetcode.com/problems/next-permutation)|Meta|Find index such that `nums[i] < nums[i+1]`, then find another element `nums[j] > nums[i]` from backward, swap them, and reverse `nums[i+1:]`|
|[3043. Find the Length of the Longest Common Prefix](./questions/3043.Find_the_Length_of_the_Longest_Common_Prefix(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-the-length-of-the-longest-common-prefix)|Uber OA|Use hashset to save all the prefixes of `x` from `arr1`, and compare each prefixes of `y` from `arr2`|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Two Pointers

Two pointers can save space complexity, because it only uses constant space complexity $O(1)$. Usually use `l, r` pointers and either increment `l` or decrement `r` depends on the current `sum` compare with `target` value.

|Two Pointers|||||
|---|---|---|---|---|
|LeetCode 150||||
|[125. Valid Palindrome](./questions/125.Valid_Palindrome_(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-palindrome/)|Meta Tag|Use l, r ptrs to compare if two elem are the same, increment or decrement ptr if non-alphanumeric elem exists|
|[167. Two Sum II - Input Array Is Sorted](./questions/167.Two_Sum_II_(Medium).md)|Medium|[Link](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)|
|[42. Trapping Rain Water](./questions/42.Trapping_Rain_Water(Hard).md)|Hard|[Link](https://leetcode.com/problems/trapping-rain-water/)|
|[15. 3Sum](./questions/15.3Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/3sum/)|
|LeetCode 75||||
|[283. Move Zeroes](./questions/283.Move_Zeroes(Easy).md)|Easy|[Link](https://leetcode.com/problems/move-zeroes/)|
|[392. Is Subsequence](./questions/392.Is_Subsequence(Easy).md)|Easy|[Link](https://leetcode.com/problems/is-subsequence/)|
|[11. Container With Most Water](./questions/11.Container_With_Most_Water(Medium).md)|Medium|[Link](https://leetcode.com/problems/container-with-most-water/)|
|[1679. Max Number of K-Sum Pairs](./questions/1679.Max_Number_of_K-Sum_Pairs(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-number-of-k-sum-pairs/)|
|Miscellaneous||||
|[5. Longest Palindromic Substring](./questions/5.Longest_Palindromic_Substring(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-palindromic-substring/)|Amazon, Cisco|Use l, r ptrs to compare if s[l] == s[r] to confirm palindrome, update res with longer substring|
|[1268. Search Suggestions System](./questions/1268.Search_Suggestions_System(Medium).md)|Medium|[Link](https://leetcode.com/problems/search-suggestions-system/)|
|[680. Valid Palindrome II](./questions/680.Valid_Palindrome_II(Easy).md)|Medium|[Link](https://leetcode.com/problems/valid-palindrome-ii)|Meta Tag|Use two ptrs to find where two chars are different, then check if `s[l+1, r]` or `s[l, r-1]` is a valid palindrome|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Sliding Window

Sliding Window technique is similar to Two Pointers, usually use a left pointer as a "Pivot" to know where we start recently and then update `left += 1`. Sometimes we may need to use **hashmaps** to find substring.

|Sliding Window|||||
|---|---|---|---|---|
|LeetCode 150|||||
|[209. Minimum Size Subarray Sum](./questions/209.Minimum_Size_Subarray_Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-size-subarray-sum/)||Maintain a sliding window with curSum, while curSum >= target, we update res = min(res, r - l + 1) and shrink the sliding window to find the minimal length subarray|
|[3. Longest Substring Without Repeating Characters](./questions/3.Longest_Substring_Without_Repeating_Characters_(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-substring-without-repeating-characters/)||Maintain a sliding window, repeatedly update the length when there is no repeated character. When a repeated char exists, shrink the sliding window from the left-most element|
|[30. Substring with Concatenation of All Words](./questions/30.Substring_with_Concatenation_of_All_Words(Hard).md)|Medium|[Link](https://leetcode.com/problems/substring-with-concatenation-of-all-words/)|
|[76. Minimum Window Substring](./questions/76.Minimum_Window_Substring(Hard).md)|Hard|[Link](https://leetcode.com/problems/minimum-window-substring/)|Meta|Use two hashmaps and 2 counts to keep track of every chars, update res when sCount == tCount, and we start shrinking the sliding window|
|LeetCode 75|||
|[643. Maximum Average Subarray I](./questions/643.Maximum_Average_Subarray_I(Easy).md)|Easy|[Link](https://leetcode.com/problems/maximum-average-subarray-i/)||First calculate the sum(nums[:k]) as sliding window result, then update the curSum by removing the left most element and adding the new element|
|[1456. Maximum Number of Vowels in a Substring of Given Length](./questions/1456.Maximum_Number_of_Vowels_in_a_Substring_of_Given_Length(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-number-of-vowels-in-a-substring-of-given-length/)|
|[1493. Longest Subarray of 1's After Deleting One Element](./questions/1493.Longest_Subarray_of_1's_After_Deleting_One_Element(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-subarray-of-1s-after-deleting-one-element/?envType=study-plan-v2&envId=leetcode-75)||Similar to 487|
|[1004. Max Consecutive Ones III](./questions/1004.Max_Consecutive_Ones_III(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-consecutive-ones-iii/)|Meta|Maintain sliding window with at most k 0, each time if `nums[r]` is `0`, we decrement k, when k is negative, we update `l += 1`, same as moving the current max sliding window to the right each time|
|NeetCode 150|||||
|[121. Best Time to Buy and Sell Stock](./questions/121.Best_Time_to_Buy_and_Sell_Stock_(Easy).md)|Easy|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)|
|[424. Longest Repeating Character Replacement](./questions/424.Longest_Repeating_Character_Replacement(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-repeating-character-replacement/)|
|[567. Permutation in String](./questions/567.Permutation_in_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/permutation-in-string/)|
|[239. Sliding Window Maximum](./questions/239.Sliding_Window_Maximum(Hard).md)|Hard|[Link](https://leetcode.com/problems/sliding-window-maximum/)|
|Miscellaneous|||
|[53. Maximum Subarray](./questions/53.Maximum_Subarray_(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-subarray/)|
|[485. Max Consecutive Ones](./questions/485.Max_Consecutives_Ones(Easy).md)|Easy|[Link](https://leetcode.com/problems/max-consecutive-ones/)|
|[487. Max Consecutive Ones II](./questions/487.Max_Consecutive_Ones_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-consecutive-ones-ii/)|Similar to 1493|
|[3318. Find X-Sum of All K-Long Subarrays I](./questions/3318.Find_X-Sum_of_All_K-Long_Subarrays_I(Easy).md)|Easy|[Link](https://leetcode.com/problems/find-x-sum-of-all-k-long-subarrays-i/)|Google Tag|Sliding Window, maxHeap, hashmap|
|[2461. Maximum Sum of Distinct Subarrays With Length K](./questions/2461.Maximum_Sum_of_Distinct_Subarrays_With_Length_K(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-sum-of-distinct-subarrays-with-length-k/)||Sliding window to find max sum of subarray, use hashmap to detect duplicate elements|

<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Matrix

The trick is to use pointers to keep in track of the boundaries. Then we shrink the boundaries after we finish a traverse or something.

|Matrix|||||
|---|---|---|---|---|
|[36. Valid Sudoku](./questions/36.Valid_Sudoku_(Medium).md)|Medium|[Link](https://leetcode.com/problems/valid-sudoku/)|Meta|Use three dicts to check repetition|
|[54. Spiral Matrix](./questions/54.Spiral_Matrix(Medium).md)|Medium|[Link](https://leetcode.com/problems/spiral-matrix/)|
|[48. Rotate Image](./questions/48.Rotate_Image(Medium).md)|Medium|[Link](https://leetcode.com/problems/rotate-image/)|
|[73. Set Matrix Zeroes](./questions/73.Set_Matrix_Zeroes(Medium).md)|Medium|[Link](https://leetcode.com/problems/set-matrix-zeroes/)|
|[289. Game of Life](./questions/289.Game_of_Life(Medium).md)|Medium|[Link](https://leetcode.com/problems/game-of-life/)||Traverse the grid to find which entries need to be changed later, and we mark it as other number. Later, we change the marked number back to either live or dead|
|Miscellaneous|||||
|[1861. Rotating the Box](./questions/1861.Rotating_the_Box(Medium).md)|Medium|[Link](https://leetcode.com/problems/rotating-the-box)||First move all the stones to the valid spaces, then convert each column into each row of the new matrix|
|[498. Diagonal Traverse](./questions/498.Diagonal_Traverse(Medium).md)|Medium|[Link](https://leetcode.com/problems/diagonal-traverse)|Meta|Save the diagonal index by (r+c) with values `{diagonal_idx: [val]}`, then check `idx % 2` to decide whether reverse the saved values' list or not|
|[766. Toeplitz Matrix](./questions/766.Toeplitz_Matrix(Easy).md)|Easy|[Link](https://leetcode.com/problems/toeplitz-matrix)|Meta|Compare each entry with their bottom-right neighbor (if exists)|
|[37. Sudoku Solver](./questions/37.Sudoku_Solver(Hard).md)|Medium|[Link](https://leetcode.com/problems/sudoku-solver)|Meta|Use 3 sets to save existed vals, backtrack number `i` from `[1, 9]` for `'.'`|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Binary Search
Use this method when we see sorted in **non-decreasing** order or when we need to write an algorithm in $O(log\ n)$ runtime. Use left & right pointer, then we iteratively find the mid point by `(left + right) // 2`, and compare the mid point with `target`, if `target < m`, we update the `right` by `m - 1`, if `target > m`, we update `left` by `m + 1`. 

|Binary Search|||||
|---|---|---|---|---|
|LeetCode 150||||
|[704. Binary Search](./questions/704.Binary_Search_(Easy).md)|Easy|[Link](https://leetcode.com/problems/binary-search/)|
|[35. Search Insert Position](./questions/35.Search_Insert_Position_(Easy).md)|Easy|[Link](https://leetcode.com/problems/search-insert-position/)|
|[74. Search a 2D Matrix](./questions/74.Search_a_2D_Matrix_(Medium).md)|Medium|[Link](https://leetcode.com/problems/search-a-2d-matrix/)|
|[153. Find Minimum in Rotated Sorted Array](./questions/153.Find_Minimum_in_Rotated_Sorted_Array(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)|
|[33. Search in Rotated Sorted Array](./questions/33.Search_in_Rotated_Sorted_Array(Medium).md)|Medium|[Link](https://leetcode.com/problems/search-in-rotated-sorted-array/)|
|[162. Find Peak Element](./questions/162.Find_Peak_Element(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-peak-element/)|Meta Tag|Run Binary Search to check if a peak element exists, if not, update l or r pointer to the greater value neighbor|
|[34. Find First and Last Position of Element in Sorted Array](./questions/34.Find_First_and_Last_Position_of_Element_in_Sorted_Array(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)|Meta|Find the left end and right end of `nums` by running Binary Search twice, update different ptr each time|
|[4. Median of Two Sorted Arrays](./questions/4.Median_of_Two_Sorted_Arrays(Hard).md)|Hard|[Link](https://leetcode.com/problems/median-of-two-sorted-arrays/)|
|LeetCode 75|||||
|[374. Guess Number Higher or Lower](./questions/374.Guess_Number_Higher_or_Lower(Easy).md)|Easy|[Link](https://leetcode.com/problems/guess-number-higher-or-lower/)|
|[2300. Successful Pairs of Spells and Potions](./questions/2300.Successful_Pairs_of_Spells_and_Potions(Medium).md)|Medium|[Link](https://leetcode.com/problems/successful-pairs-of-spells-and-potions/)||Sort potions first and then run Binary Search on potions to find the smallest left pointer for each spell|
|[875. Koko Eating Bananas](./questions/875.Koko_Eating_Bananas(Medium).md)|Medium|[Link](https://leetcode.com/problems/koko-eating-bananas/)||Run Binary Search on range of speed k, update r = k - 1 when hours <= h, update l = k + 1 when hours > h|
|Miscellaneous|||||
|[528. Random Pick with Weight](./questions/528.Random_Pick_with_Weight(Medium).md)|Medium|[Link](https://leetcode.com/problems/random-pick-with-weight)|Meta Tag|First initialize each index from [0, len(w)-1] a probability by w[i] / sum(w), then we calculate the prefixSum of each index. Next, randomly generate a prob within [0, 1], then we use Binary Search to find the index with the closest probability|
|[1539. Kth Missing Positive Number](./questions/1539.Kth_Missing_Positive_Number(Easy).md)|Easy|[Link](https://leetcode.com/problems/kth-missing-positive-number)|Meta|Run Binary Search with k on the difference between the original `arr` and current `arr`|


<!--
|[]()|Easy|[Link]()|||
-->
<br>

---

### Backtracking

Backtracing is recursion with base case(s), we have to first find the base case(s), if the case satisfies the base case condition that we can `append` the desired answer then return, and continue the recursion by `i+1`.

|Backtracking|||||
|---|---|---|---|---|
|[78. Subsets](./questions/78.Subsets_(Medium).md)|Medium|[Link](https://leetcode.com/problems/subsets)|Meta|Use backtrack with index `i` to keep track of current `curSum[]`, when `i==len(nums)`, we append `curSum` into `res[]` and return, we pop the last element and add new element into `curSum` with `i += 1`|
|[90. Subsets II](./questions/90.Subsets_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/subsets-ii/)|
|[39. Combination Sum](./questions/39.Combination_Sum_(Medium).md)|Medium|[Link](https://leetcode.com/problems/combination-sum/)|
|[40. Combination Sum II](./questions/40.Combination_Sum_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/combination-sum-ii/)|
|[216. Combination Sum III](./questions/216.Combination_Sum_III(Medium).md)|Medium|[Link](https://leetcode.com/problems/combination-sum-iii/)|
|[17. Letter Combinations of a Phone Number](./questions/17.Letter_Combinations_of_a_Phone_Number_(Medium).md)|Medium|[Link](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)||Use index i to traverse each digit in the digitsMap, when len(string) == len(digits), add this to res[], increment index i|
|[77. Combinations](./questions/77.Combinations_(Medium).md)|Medium|[Link](https://leetcode.com/problems/combinations/)|
|[22. Generate Parentheses](./questions/22.Generate_Parentheses(Medium).md)|Medium|[Link](https://leetcode.com/problems/generate-parentheses/)|
|[46. Permutations](./questions/46.Permutations(Medium).md)|Medium|[Link](https://leetcode.com/problems/permutations/)|
|[79. Word Search](./questions/79.Word_Search(Medium).md)|Medium|[Link](https://leetcode.com/problems/word-search/)|
|[131. Palindrome Partitioning](./questions/131.Palindrome_Partitioning(Medium).md)|Medium|[Link](https://leetcode.com/problems/palindrome-partitioning/)|
|[51. N-Queens](./questions/51.N-Queens(Hard).md)|Hard|[Link](https://leetcode.com/problems/n-queens/)|
|[52. N-Queens II](./questions/52.N-Queens_II(Hard).md)|Hard|[Link](https://leetcode.com/problems/n-queens-ii/)|
|[386. Lexicographical Numbers](./questions/386.Lexicographical_Numbers(Medium).md)|Medium|[Link](https://leetcode.com/problems/lexicographical-numbers/description/)|Google Tag| Similar to combination|
|Miscellaneous|||||
|[698. Partition to K Equal Sum Subsets](./questions/698.Partition_to_K_Equal_Sum_Subsets(Medium).md)|Medium|[Link](https://leetcode.com/problems/partition-to-k-equal-sum-subsets)|Meta|Use Backtrack to try each element with other elements subarray, if the subarray equals to k, we mark all elements to be visited, run backtrack from the beginning again. For every subarray, we decrement k -= 1, return True when k == 0|


<!--
|[]()|Medium|[Link]()|||
-->

<br>

---

### Stack

|Stack|||||
|---|---|---|---|---|
|LeetCode 150|||||
|[20. Valid Parentheses](./questions/20.Valid_Parentheses_(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-parentheses/)|
|[71. Simplify Path](./questions/71.Simplify_Path(Medium).md)|Medium|[Link](https://leetcode.com/problems/simplify-path/)|Meta Tag|Detect each char to know if it equals to '/' or not, and use stack to add new file name or pop previous file name|
|[155. Min Stack](./questions/155.Min_Stack_(Medium).md)|Medium|[Link](https://leetcode.com/problems/min-stack/)|
|[150. Evaluate Reverse Polish Notation](./questions/150.Evaluate_Reverse_Polish_Notation(Medium).md)|Medium|[Link](https://leetcode.com/problems/evaluate-reverse-polish-notation/)|
|[224. Basic Calculator](./questions/224.Basic_Calculator(Hard).md)|Hard|[Link](https://leetcode.com/problems/basic-calculator/)|Google Tag, Meta Tag|Use `res, sign ,curr` to keep track of previous operation result, update `res` when we have new sign, append `res, sign` into stack[] when we have "(". Calculate result within `()`, and pop everything back from stack[], reset variables|
|LeetCode 75|||||
|[2390. Removing Stars From a String](./questions/2390.Removing_Stars_From_a_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/removing-stars-from-a-string/)||Use stack to store each element until a "\*", we then pop the top of stack to remove "\*"s left non-star character|
|[735. Asteroid Collision](./questions/735.Asteroid_Collision(Medium).md)|Medium|[Link](https://leetcode.com/problems/asteroid-collision/)|
|[394. Decode String](./questions/394.Decode_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/decode-string/)|Google Tag|
|NeetCode 150|||||
|[22. Generate Parentheses](./questions/22.Generate_Parentheses(Medium).md)|Medium|[Link](https://leetcode.com/problems/generate-parentheses/)|
|[84. Largest Rectangle in Histogram](./questions/84.Largest_Rectangle_in_Histogram(Hard).md)|Hard|[Link](https://leetcode.com/problems/largest-rectangle-in-histogram/)|Google Tag|
|Miscellaneous|||||
|[1249. Minimum Remove to Make Valid Parentheses](./questions/1249.Minimum_Remove_to_Make_Valid_Parentheses(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses)|Meta Tag|Use stack to save "(" index, when we encounter ")", we pop the last index from stack to close a parenthese. If we encounter ")" with no "(", change it to ""|
|[227. Basic Calculator II](./questions/227.Basic_Calculator_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/basic-calculator-ii)|Meta Tag|Use stack to save previous result, we only append new element with sign into stack when we encounter a new sign|
|[921. Minimum Add to Make Parentheses Valid](./questions/921.Minimum_Add_to_Make_Parentheses_Valid(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid)|Meta|Count "(" and ")", when encounter ")", check if we have "(" to remove or decrement, otherwise, increment the count of ")".|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Monotonic Stack
|Monotonic Stack|||||
|---|---|---|---|---|
|LeetCode 75|||||
|[739. Daily Temperatures](./questions/739.Daily_Temperatures(Medium).md)|Medium|[Link](https://leetcode.com/problems/daily-temperatures/)||Maintain a decreasing monotonic stack and update prev less temperature's index with day difference|
|[901. Online Stock Span](./questions/901.Online_Stock_Span(Medium).md)|Medium|[Link](https://leetcode.com/problems/online-stock-span/)||Maintain an decreasing monotonic stack, when current price >= last elem in stack, add its span with current span, eventually append [price, span] into stack|

<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Linked List

Usually needs to check `if not node`: `return None`

|Linked List|||||
|---|---|---|---|---|
|[141. Linked List Cycle](./questions/141.Linked_List_Cycle_(Easy).md)|Easy|[Link](https://leetcode.com/problems/linked-list-cycle/)|
|[21. Merge Two Sorted Lists](./questions/21.Merge_Two_Sorted_Lists_(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-two-sorted-lists/)|
|[2. Add Two Numbers](./questions/2.Add_Two_Numbers_(Medium).md)|Medium|[Link](https://leetcode.com/problems/add-two-numbers/)|Meta|Create dummy node with `carry` to save the sum|
|[92. Reverse Linked List II](./questions/92.Reverse_Linked_List_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/reverse-linked-list-ii/)|
|[138. Copy List with Random Pointer](./questions/138.Copy_List_With_Random_Pointer(Medium).md)|Medium|[Link](https://leetcode.com/problems/copy-list-with-random-pointer/)|Meta|Use hashmap to save each node with new node, traverse `head` to assign .next, .random to be the new node in hashmap|
|[143. Reorder List](./questions/143.Reorder_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/reorder-list/)|
|[19. Remove Nth Node From End of List](./questions/19.Remove_Nth_Node_From_End_of_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)|
|[146. LRU Cache](./questions/146.LRU_Cache(Medium).md)|Medium|[Link](https://leetcode.com/problems/lru-cache/)|Meta|Use two dummy nodes to keep track of the LRU and MRU, if we need to remove the LRU, remove `right.prev`. Insert to `left.next` to add new node. Access value by `hashmap[key].val`|
|[25. Reverse Nodes in k-Group](./questions/25.Reverse_Nodes_in_k-Group(Hard).md)|Hard|[Link](https://leetcode.com/problems/reverse-nodes-in-k-group/)|||
|[61. Rotate List](./questions/61.Rotate_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/rotate-list/)|Python, C++|
|[23. Merge k Sorted Lists](./questions/23.Merge_k_Sorted_Lists(Hard).md)|Hard|[Link](https://leetcode.com/problems/merge-k-sorted-lists/)|Meta|Merge 2 lists each time and replace `lists` with the merged sorted lists|
|LeetCode 75||||
|[2095. Delete the Middle Node of a Linked List](./questions/2095.Delete_the_Middle_Node_of_a_Linked_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/delete-the-middle-node-of-a-linked-list/)||Fast, Slow method to remove the middle node|
|[328. Odd Even Linked List](./questions/328.Odd_Even_Linked_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/odd-even-linked-list/)||Create odd and even linkedlist, add even linked list to the end of odd linkedlist|
|[206. Reverse Linked List](./questions/206.Reverse_Linked_List(Easy).md)|Easy|[Link](https://leetcode.com/problems/reverse-linked-list/)||Flip every node to connect its previous node, and reset prev, head every time|
|[2130. Maximum Twin Sum of a Linked List](./questions/2130.Maximum_Twin_Sum_of_a_Linked_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-twin-sum-of-a-linked-list/)||Reverse the first half linked-list, update res with the first half.val + second half.val|
|LeetCode 150||||
|[86. Partition List](./questions/86.Partition_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/partition-list)||Use two nodes to save lists of nodes less than `x` and nodes greater or equal to `x`|
|Miscellaneous|||||
|[83. Remove Duplicates from Sorted List](./questions/83.Remove_Duplicates_from_Sorted_List(Easy).md)|Easy|[Link](https://leetcode.com/problems/remove-duplicates-from-sorted-list/)||Repeatly set curr.next = curr.next.next to remove duplicate, update curr only a non-duplicated element is found|
|[82. Remove Duplicates from Sorted List II](./questions/82.Remove_Duplicates_from_Sorted_List_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/)||Use while loop to skip duplicate (while head and head.next and head.val == head.next.val), use prev node to save the non-duplicate element|
|[708. Insert into a Sorted Circular Linked List](./questions/708.Insert_into_a_Sorted_Circular_Linked_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list)|Meta|Use `prev`, `curr` to keep track of two nodes and compare their values with `insertVal` and add new Node between `prev` and `curr`|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Binary Tree General

Binary Tree Problems usually can use Recursion to solve, start from the root, then recurse on its left subtree and right subtree to check three conditons: 1. if `not left and not right` (when both are None). 2. if `not left or not right` (when one of the node is None, not match). 3. if `left.val != right.val` (values are not the same, not match).

It is also convention to use **BFS** (queue), **DFS** (stack) to check each node with the above three conditions.

|Binary Tree General|||||
|---|---|---|---|---|
|LeetCode 150|||
|[104. Maximum Depth of Binary Tree](./questions/104.Maximum_Depth_of_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/maximum-depth-of-binary-tree/)|DFS|
|[100. Same Tree](./questions/100.Same_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/same-tree/)|
|[226. Invert Binary Tree](./questions/226.Invert_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/invert-binary-tree/)|
|[101. Symmetric Tree](./questions/101.Symmetric_Tree(Easy).md)|Easy|[Link](https://leetcode.com/problems/symmetric-tree/)|
|[105. Construct Binary Tree from Preorder and Inorder Traversal](./questions/105.Construct_Binary_Tree_from_Preorder_and_Inorder_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)|
|[106. Construct Binary Tree from Inorder and Postorder Traversal](./questions/106.Construct_Binary_Tree_from_Inorder_and_Postorder_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/)|
|[117. Populating Next Right Pointers in Each Node II](./questions/117.Populating_Next_Right_Pointers_in_Each_Node_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/)||Run BFS on each level and set each node's next to the next node, except the last one|
|[114. Flatten Binary Tree to Linked List](./questions/114.Flatten_Binary_Tree_to_Linked_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)||Find curr's left subtree's rightmost node and set its node.right to curr's right-subtree. Then set curr.right = curr.left, update curr.left = None and curr = curr.right|
|[173. Binary Search Tree Iterator](./questions/173.Binary_Search_Tree_Iterator(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-search-tree-iterator)||Use `stack[]` to save nodes in descending order, so we can always find the next smallest value by popping|
|[222. Count Complete Tree Nodes](./questions/222.Count_Complete_Tree_Nodes(Easy).md)|Easy|[Link](https://leetcode.com/problems/count-complete-tree-nodes/)|
|[112. Path Sum](./questions/112.Path_Sum(Easy).md)|Easy|[Link](https://leetcode.com/problems/path-sum/)||Run DFS from root to leaf, check if curSum == targetSum|
|[124. Binary Tree Maximum Path Sum](./questions/124.Binary_Tree_Maximum_Path_Sum(Hard).md)|Hard|[Link](https://leetcode.com/problems/binary-tree-maximum-path-sum/)|
|[987. Vertical Order Traversal of a Binary Tree](./questions/987.Vertical_Order_Traversal_of_a_Binary_Tree(Hard).md)|Hard|[Link](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree)|Meta|Save `(node, row, col)` into `deque[]`, and run BFS to append `node.left` with `(row+1, col-1)` and `node.right` with `(row+1, col+1)`. Add all nodes with the same col into `hashmap{col: [node.val]}`. Sort `col` and `row` in the end|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Binary Tree BFS

BFS uses `collections.queue()` and follows **FIFO**, DFS uses `stack()` and follows **LIFO**, both BFS and DFS can be implemented by `list()`.

|Binary Tree BFS|||||
|---|---|---|---|---|
|[199. Binary Tree Right Side View](./questions/199.Binary_Tree_Right_Side_View_(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-right-side-view/)|Meta Tag|Run BFS on each level and only append the last node of each level to res[]|
|[637. Average of Levels in Binary Tree](./questions/637.Average_of_Levels_in_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/average-of-levels-in-binary-tree/)|
|[102. Binary Tree Level Order Traversal](./questions/102.Binary_Tree_Level_Order_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-level-order-traversal/)|
|[103. Binary Tree Zigzag Level Order Traversal](./questions/103.Binary_Tree_Zigzag_Level_Order_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)|
|LeetCode 75|||
|[1161. Maximum Level Sum of a Binary Tree](./questions/1161.Maximum_Level_Sum_of_a_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-level-sum-of-a-binary-tree/)||Similar to 199, standard BFS with slightly modification|
|Miscellaneous|||||
|[314. Binary Tree Vertical Order Traversal](./questions/314.Binary_Tree_Vertical_Order_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-vertical-order-traversal/)|Meta|Run BFS to save all the nodes with their column index [node, col] into deque and save them into hashmap {index: [node]}|
|Miscellaneous|||||
|[863. All Nodes Distance K in Binary Tree](./questions/863.All_Nodes_Distance_K_in_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree)|Meta|Build an undirected graph to connect two connected nodes together, then run BFS from `target` to add all its neighbor nodes into deque, when distance == k, we append the node.val into res[]|
|[958. Check Completeness of a Binary Tree](./questions/958.Check_Completeness_of_a_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/check-completeness-of-a-binary-tree)|Meta|Run BFS with `seenNull` to check if a null node exists, if it exists and we have other non-null nodes, return False|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Binary Tree DFS
|Binary Tree DFS|||||
|---|---|---|---|---|
|LeetCode 75||||
|[104. Maximum Depth of Binary Tree](./questions/104.Maximum_Depth_of_Binary_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/maximum-depth-of-binary-tree/)|
|[872. Leaf-Similar Trees](./questions/872.Leaf_Similar_Trees(Easy).md)|Easy|[Link](https://leetcode.com/problems/leaf-similar-trees/)|
|[1448. Count Good Nodes in Binary Tree](./questions/1448.Count_Food_Nodes_in_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/count-good-nodes-in-binary-tree/)||Standard DFS with slightly modification|
|[437. Path Sum III](./questions/437.Path_Sum_III(Medium).md)|Medium|[Link](https://leetcode.com/problems/path-sum-iii/)||Use hashmap to keep track of current subtree's prefixSum, and update res with counts of diff = curSum - targetSum in current subtree's hashmap|
|[1372. Longest ZigZag Path in a Binary Tree](./questions/1372.Longest_ZigZag_Path_in_a_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-zigzag-path-in-a-binary-tree)||Run DFS on each node, use `goLeft` to know if we should continue the path to `node.left`, we also run DFS on the opposite direction for each node with depth 1|
|[236. Lowest Common Ancestor of a Binary Tree](./questions/236.Lowest_Common_Ancestor_of_a_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)|Meta Tag|Recursively go to root's left and right subtree to find if a node == p or node == q, if both node can be found, means the common ancestor is the root. Otherwise, either l or r is the ancestor|
|Miscellaneous||||
|[113. Path Sum II](./questions/113.Path_Sum_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/path-sum-ii/)||Run DFS to reach the leaf and compare if curSum == targetSum, if so, copy the current path into res[], and pop, remove (backtrack) the current node.val to explore other paths|
|[1650. Lowest Common Ancestor of a Binary Tree III](./questions/1650.Lowest_Common_Ancestor_of_a_Binary_Tree_III(Medium).md)|Medium|[Link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-iii/)|Meta Tag|First save the path from `p` to `root`, traverse from `q` to `root`, the first common node is the LCA|
|[543. Diameter of Binary Tree](./questions/543.Diameter_of_Binary_Tree(Easy).md)|Easy|[Link](https://leetcode.com/problems/diameter-of-binary-tree)|Meta Tag|Run DFS on each node to get its left, right subtree height and update res with left + right, for each node, return max(left, right) + 1|
|[129. Sum Root to Leaf Numbers](./questions/129.Sum_Root_to_Leaf_Numbers(Medium).md)|Medium|[Link](https://leetcode.com/problems/sum-root-to-leaf-numbers)|Meta|Run DFS to add every number in the path, when reaches the leaf node, return `curSum`, return `node.left` + `node.right`|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Binary Search Tree

Binary Search Tree (BST) has property that the nodes on the left of the root are smaller than the root, the nodes on the right of the root are greater than the root. So, in many cases we can implement the **DFS** to perform **In-order traversal**: left -> root -> right.

|Binary Search Tree|||||
|---|---|---|---|---|
|LeetCode 150|||||
|[530. Minimum Absolute Difference in BST](./questions/530.Minimum_Absolute_Difference_in_BST_(Easy).md)|Easy|[Link](https://leetcode.com/problems/minimum-absolute-difference-in-bst/)||Run DFS and set the left node as prev, then update res min(res, abs(prev.val-node.val)), change prev = node, go to its right|
|[230. Kth Smallest Element in a BST](./questions/230.Kth_Smallest_Element_in_a_BST_(Medium).md)|Medium|[Link](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)|
|[98. Validate Binary Search Tree](./questions/98.Validate_Binary_Search_Tree_(Medium).md)|Medium|[Link](https://leetcode.com/problems/validate-binary-search-tree/)|
|LeetCode 75|||
|[700. Search in a Binary Search Tree](./questions/700.Search_in_a_Binary_Search_Tree(Easy).md)|Easy|[Link](https://leetcode.com/problems/search-in-a-binary-search-tree/)|
|[450. Delete Node in a BST](./questions/450.Delete_Node_in_a_BST(Medium).md)|Medium|[Link](https://leetcode.com/problems/delete-node-in-a-bst/)||Run Binary Search to find the key, then replace the key with the second smallest element from its right branch deep left node to maintain the BST property|
|Miscellaneous|||
|[108. Convert Sorted Array to Binary Search Tree](./questions/108.Convert_Sorted_Array_to_Binary_Search_Tree_(Easy).md)|Easy|[Link](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)|
|[235. Lowest Common Ancestor of a Binary Search Tree](./questions/235.Lowest_Common_Ancestor_of_a_Binary_Search_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)|
|[938. Range Sum of BST](./questions/938.Range_Sum_of_BST(Easy).md)|Medium|[Link](https://leetcode.com/problems/range-sum-of-bst)|Meta Tag|Based on the property of BST, we check if current node < low, we recursively call on its right subtree, if current node > high, we recursively call on its left subtree|
|[426. Convert Binary Search Tree to Sorted Doubly Linked List](./questions/426.Convert_Binary_Search_Tree_to_Sorted_Doubly_Linked_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list)|Meta|Run DFS in-order traversal: left->root->right and update `head.right = node` and `node.left = head`, then update `head = node`. Finally, connect head and dummy together to be circular|
|[270. Closest Binary Search Tree Value](./questions/270.Closest_Binary_Search_Tree_Value(Easy).md)|Easy|[Link](https://leetcode.com/problems/closest-binary-search-tree-value)|Meta|Compare the `abs(node.val-target)` with `abs(res-target)`, if they equal, update res to be the smaller val, otherwise, update res to the one will smaller difference. Run DFS with Binary Search to find the closer one|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Graph General

[286, 130, 417] require reverse-thinking to start running DFS on edges and add grids for some specific requirements. For other types of questions, we can run **DFS** or **BFS** iteratively to solve.

|Graph General|||||
|---|---|---|---|---|
|[200. Number of Islands](./questions/200.Number_of_Islands_(Medium).md)|Medium|[Link](https://leetcode.com/problems/number-of-islands/)|Graph BFS|Run BFS on each entry to find island that has not been visited|
|[695. Max Area of Island](./questions/695.Max_Area_of_Island(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-area-of-island/)|Python, Java|
|[207. Course Schedule](./questions/207.Course_Schedule_(Medium).md)|Medium|[Link](https://leetcode.com/problems/course-schedule/)|DFS|Run DFS to check all the prerequisites of a course, if can be completed, remove it and set preMap[crs] = []|
|[210. Course Schedule II](./questions/210.Course_Schedule_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/course-schedule-ii/)||
|[130. Surrounded Regions](./questions/130.Surrounded_Regions(Medium).md)|Medium|[Link](https://leetcode.com/problems/surrounded-regions/)||
|[286. Walls and Gates](./questions/286.Walls_and_Gates(Medium).md)|Medium|[Link](https://leetcode.com/problems/walls-and-gates/)|Graph BFS|
|[417. Pacific Atlantic Water Flow](./questions/417.Pacific_Atlantic_Water_Flow(Medium).md)|Medium|[Link](https://leetcode.com/problems/pacific-atlantic-water-flow/)||
|[133. Clone Graph](./questions/133.Clone_Graph(Medium).md)|Medium|[Link](https://leetcode.com/problems/clone-graph/)|Meta|Create each node's copy into `hashmap{node: new_node}`, run DFS to append each node's neighbors|
|[399. Evaluate Division](./questions/399.Evaluate_Division(Medium).md)|Medium|[Link](https://leetcode.com/problems/evaluate-division/)||
|LeetCode 150||||
|[909. Snakes and Ladders](./questions/909.Snakes_and_Ladders(Medium).md)|Medium|[Link](https://leetcode.com/problems/snakes-and-ladders/)|Graph BFS|
|[127. Word Ladder](./questions/127.Word_Ladder(Hard).md)|Hard|[Link](https://leetcode.com/problems/word-ladder/)|Graph BFS|
|[433. Minimum Genetic Mutation](./questions/433.Minimum_Genetic_Mutation(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-genetic-mutation/)|Graph BFS|
|LeetCode 75|||
|[841. Keys and Rooms](./questions/841.Keys_and_Rooms(Medium).md)|Medium|[Link](https://leetcode.com/problems/keys-and-rooms/)|Graph DFS|
|[547. Number of Provinces](./questions/547.Number_of_Provinces(Medium).md)|Medium|[Link](https://leetcode.com/problems/number-of-provinces/)|Graph DFS|For each unvisited city, run DFS to add all connected cities into visited(), increment res|
|[1466. Reorder Routes to Make All Paths Lead to the City Zero](./questions/1466.Reorder_Routes_to_Make_All_Paths_Lead_to_the_City_Zero(Medium).md)|Medium|[Link](https://leetcode.com/problems/reorder-routes-to-make-all-paths-lead-to-the-city-zero/)|Graph DFS|
|[994. Rotting Oranges](./questions/994.Rotting_Oranges(Medium).md)|Medium|[Link](https://leetcode.com/problems/rotting-oranges/)|Graph BFS|
|[1926. Nearest Exit from Entrance in Maze](./questions/1926.Nearest_Exit_from_Entrance_in_Maze(Medium).md)|Medium|[Link](https://leetcode.com/problems/nearest-exit-from-entrance-in-maze/)|Graph BFS|
|Miscellaneous|||||
|[339. Nested List Weight Sum](./questions/339.Nested_List_Weight_Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/nested-list-weight-sum)|Meta Tag|Run DFS/BFS on each element in list, if this is element, update total with current depth and element's val. Otherwise, dfs on the list to update total with each element in that list with depth+1|
|[1091. Shortest Path in Binary Matrix](./questions/1091.Shortest_Path_in_Binary_Matrix(Medium).md)|Medium|[Link](https://leetcode.com/problems/shortest-path-in-binary-matrix)|Meta|Run BFS to find the shortest path, add all the same level neighbors into visited and deque, update res += 1|
|[827. Making A Large Island](./questions/827.Making_A_Large_Island(Hard).md)|Medium|[Link](https://leetcode.com/problems/making-a-large-island)|Meta|Run DFS/BFS start from an entry with 1 to change this island's every entry to be `index`. Traverse `grid` again to run BFS on `0` to calculate the area of its neighbors + 1|
|[721. Accounts Merge](./questions/721.Accounts_Merge(Medium).md)|Medium|[Link](https://leetcode.com/problems/accounts-merge)|Meta|Use hashmap to map `{email: id}` use `uf.union()` for existed email's id, then use `uf.find()` to find root_id and group `{id: [email]}`, lastly, follow the format to return|
|[329. Longest Increasing Path in a Matrix](./questions/329.Longest_Increasing_Path_in_a_Matrix(Hard).md)|Hard|[Link](https://leetcode.com/problems/longest-increasing-path-in-a-matrix)|Meta|2D DP + DFS on entry's neighbors|
|[1443. Minimum Time to Collect All Apples in a Tree](./questions/1443.Minimum_Time_to_Collect_All_Apples_in_a_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-time-to-collect-all-apples-in-a-tree)|Meta|Build adjacent graph and run DFS to search if node's children has apple, if so return `secs + 2`, otherwise, return 2 if `node` is apple, `0` else|
|[489. Robot Room Cleaner](./questions/489.Robot_Room_Cleaner(Hard).md)|Hard|[Link](https://leetcode.com/problems/robot-room-cleaner)||Run DFS and backtrack|


<!--
|[]()|Medium|[Link]()|||
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

---

### Union Find (Disjoint Set)

More to pratice: <br>
547. Number of Provinces <br>
952. Largest Component Size by Common Factor <br>
947. Most Stones Removed with Same Row or Column <br>
1319. Number of Operations to Make Network Connected <br>
684. Redundant Connection <br>
990. Satisfiability of Equality Equations <br>
1202. Smallest String With Swaps <br>
2421. Number of Good Paths

|Union Find|||||
|---|---|---|---|---|
|[721. Accounts Merge](./questions/721.Accounts_Merge(Medium).md)|Medium|[Link](https://leetcode.com/problems/accounts-merge)|Meta|Use hashmap to map `{email: id}` use `uf.union()` for existed email's id, then use `uf.find()` to find root_id and group `{id: [email]}`, lastly, follow the format to return|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

___

### Trie
Use {} to save this current node's next characters, "*" to indicate the end of a word.

|Trie|||||
|---|---|---|---|---|
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

Usually, we need to **sort** the array first to better find the overlapping intervals. We compare two intervals with the last element of previous interval and the first element of new interval to know detect overlap.

|Intervals|||||
|---|---|---|---|---|
|[56. Merge Intervals](./questions/56.Merge_Intervals(Medium).md)|Medium|[Link](https://leetcode.com/problems/merge-intervals/)|Meta|Compare new interval with previous interval, if there is overlap, we update the previous interval with [min(x1, x2), max(y1, y2)]. Otherwise, append the new interval to `res[]`|
|[57. Insert Interval](./questions/57.Insert_Interval_(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-interval/)|
|LeetCode 75|||||
|[435. Non-overlapping Intervals](./questions/435.Non-overlapping_Intervals(Medium).md)|Medium|[Link](https://leetcode.com/problems/non-overlapping-intervals/)|
|[452. Minimum Number of Arrows to Burst Balloons](./questions/452.Minimum_Number_of_Arrows_to_Burst_Balloons(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)||Use `prev` to compare with current interval, if `start <= prev[1]`, there is overlap and update `prev`|
|[228. Summary Ranges](./questions/228.Summary_Ranges(Easy).md)|Easy|[Link](https://leetcode.com/problems/summary-ranges/)|
|[1851. Minimum Interval to Include Each Query](./questions/1851.Minimum_Interval_to_Include_Each_Query(Hard).md)|Hard|[Link](https://leetcode.com/problems/minimum-interval-to-include-each-query/)|
|Miscellaneous|||||
|[252. Meeting Rooms](./questions/252.Meeting_Rooms(Easy).md)|Easy|[Link](https://leetcode.com/problems/meeting-rooms)||First sort intervals, then use `prev` to save the previous interval's end time, then compare with new interval's start time, if `prev > start`, return False|
|[253. Meeting Rooms II](./questions/253.Meeting_Rooms_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/meeting-rooms-ii)||Use minHeap to save all the current meeting with their end time. For each new interval, we compare their start_i with minHeap[0], if the start_i > minHeap[0], we replace the the room, otherwise, we append new end_i time into minHeap|
|[986. Interval List Intersections](./questions/986.Interval_List_Intersections(Medium).md)|Medium|[Link](https://leetcode.com/problems/interval-list-intersections)|Meta|Use two ptrs to find the intersection, keep the interval with greater end|
|[636. Exclusive Time of Functions](./questions/636.Exclusive_Time_of_Functions(Medium).md)|Medium|[Link](https://leetcode.com/problems/exclusive-time-of-functions)|Meta|Use stack to store ids, identify `start` or `end`, and add the difference to `res[i]`|


<!--
|[]()|Medium|[Link]()|||
-->

<br>

---
  
### Hashmap

In general, create a hashmap {} and store elements and their indices into the hashmap as the for-loop goes, then in the for loop we check if an element has already in the hashmap or not, or in the case we want to decrement the number of times we have seen an element in the hashmap.

|Hashmap|||||
|---|---|---|---|---|
|[1. Two Sum](./questions/1.Two_Sum_(Easy).md)|Easy|[Link](https://leetcode.com/problems/two-sum/)|
|[219. Contains Duplicate II](./questions/219.Contains_Duplicate_II_(Easy).md)|Easy|[Link](https://leetcode.com/problems/contains-duplicate-ii/)|
|[242. Valid Anagram](./questions/242.Valid_Anagram(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-anagram/)|
|LeetCode 75 Hashmap/Set|||
|[1207. Unique Number of Occurrences](./questions/1207.Unique_Number_of_Occurrences(Easy).md)|Easy|[Link](https://leetcode.com/problems/unique-number-of-occurrences/)||Convert arr into hashmap, and add all occurences into set(), if an occurence already exisited in set(), return False. Otherwise, return True in the end|
|[2215. Find the Difference of Two Arrays](./questions/2215.Find_the_Difference_of_Two_Arrays(Easy).md)|Easy|[Link](https://leetcode.com/problems/find-the-difference-of-two-arrays/)||Build two hashmaps and loop over to add non-repeatitive keys into set(), and convert to list and append to res|
|[1657. Determine if Two Strings Are Close](./questions/1657.Determine_if_Two_Strings_Are_Close(Medium).md)|Medium|[Link](https://leetcode.com/problems/determine-if-two-strings-are-close/)||Use two hashmaps and two sets() to compare if the strings' keys and values_counts are the same|
|[2352. Equal Row and Column Pairs](./questions/2352.Equal_Row_and_Column_Pairs(Medium).md)|Medium|[Link](https://leetcode.com/problems/equal-row-and-column-pairs/)||Convert each row into str(row) and save into rows{}, then form str(col) and update res = rows[str(col)]|
|LeetCode 150|||||
|[383. Ransom Note](./questions/383.Ransom_Note_(Easy).md)|Easy|[Link](https://leetcode.com/problems/ransom-note/)|
|[205. Isomorphic Strings](./questions/205.Isomorphic_Strings(Easy).md)|Easy|[Link](https://leetcode.com/problems/isomorphic-strings/)||Build two hashmaps to compare the mapping of each two chars, if they don't match, return False|
|[290. Word Pattern](./questions/290.Word_Pattern(Easy).md)|Easy|[Link](https://leetcode.com/problems/word-pattern/)||Build a hashmap to check the previous mapping, but we also need to check if the mapping is unique, no duplicate words are used, we can use set() to compare|
|[49. Group Anagrams](./questions/49.Group_Anagrams(Medium).md)|Medium|[Link](https://leetcode.com/problems/group-anagrams/)||Sort word to be the key in hashmap, then append this word to the correpsonding list by the sorted(word) as key|
|[202. Happy Number](./questions/202.Happy_Number(Easy).md)|Easy|[Link](https://leetcode.com/problems/happy-number)||Use `set()` to detect when there is repeated number, so we can stop|
|Miscellaneous|||
|[359. Logger Rate Limiter](./questions/359.Logger_Rate_Limiter(Easy).md)|Easy|[Link](https://leetcode.com/problems/logger-rate-limiter/)|Google VO|


<!--
|[]()|Easy|[Link]()|||
-->
<br>

___

### Queue

|Queue|||||
|---|---|---|---|---|
|[933. Number of Recent Calls](./questions/933.Number_of_Recent_Calls(Easy).md)|Easy|[Link](https://leetcode.com/problems/number-of-recent-calls/)||Maintain a deque and pop the top when time expires|
|[649. Dota2 Senate](./questions/649.Dota2_Senate(Medium).md)|Medium|[Link](https://leetcode.com/problems/dota2-senate/)||Maintain 2 deques to fight with each party, the lower index party will win and requeue, the loser will not be added back. When one deque is empty, another party will announce victory|
|Miscellaneous|||||
|[346. Moving Average from Data Stream](./questions/346.Moving_Average_from_Data_Stream(Medium).md)|Easy|[Link](https://leetcode.com/problems/moving-average-from-data-stream)|Meta|Use deque[] to save `k` elements with `curSum`, when `len(deque) == size`, we remove the left-most element then add the right-most element into `deque[]`|
|[239. Sliding Window Maximum](./questions/239.Sliding_Window_Maximum(Hard).md)|Hard|[Link](https://leetcode.com/problems/sliding-window-maximum/)|


<!--
|[]()|Easy|[Link]()|||
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

|Greedy|||||
|---|---|---|---|---|
|[53. Maximum Subarray](./questions/53.Maximum_Subarray_(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-subarray/)|
|[55. Jump Game](./questions/55.Jump_Game_(Medium).md)|Medium|[Link](https://leetcode.com/problems/jump-game/)|
|[45. Jump Game II](./questions/45.Jump_Game_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/jump-game-ii/)|
|[134. Gas Station](./questions/134.Gas_Station(Medium).md)|Medium|[Link](https://leetcode.com/problems/gas-station/)|
|[846. Hand of Straights](./questions/846.Hand_of_Straights(Medium).md)|Medium|[Link](https://leetcode.com/problems/hand-of-straights/)|
|[1296. Divide Array in Sets of K Consecutive Numbers](./questions/1296.Divide_Array_in_Sets_of_K_Consecutive_Numbers(Medium).md)|Medium|[Link](https://leetcode.com/problems/divide-array-in-sets-of-k-consecutive-numbers/)|
|[763. Partition Labels](./questions/763.Partition_Labels(Medium).md)|Medium|[Link](https://leetcode.com/problems/partition-labels/)|
|[678. Valid Parenthesis String](./questions/678.Valid_Parenthesis_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/valid-parenthesis-string/)|
|[1899. Merge Triplets to Form Target Triplet](./questions/1899.Merge_Triplets_to_Form_Target_Triplet(Medium).md)|Medium|[Link](https://leetcode.com/problems/merge-triplets-to-form-target-triplet/)|
|Miscellaneous|||||
|[670. Maximum Swap](./questions/670.Maximum_Swap(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-swap)|Meta|Use variables to keep track of the current maximum index and swap indices, update them based on `num[i]`, finally check if both swap_ids are valid and swap, then return|


<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Kadane's Algorithm
Kadane's Algorithm maintains a `curSum` which keep tracks of contiguous summation, it is always `0` if the `curSum + nums[i] < 0`, which means we will not take this element at index `i`. If `curSum > 0` we will keep unpdating `curSum += nums[i]` and update `maxSum = max(maxSum, curSum)`. This is the standard approach of Kadane's algorithm.

|Kadane's Algorithm|||||
|---|---|---|---|---|
|LeetCode 150|||||
|[53. Maximum Subarray](./questions/53.Maximum_Subarray_(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-subarray/)|
|[918. Maximum Sum Circular Subarray](./questions/918.Maximum_Sum_Circular_Subarray(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-sum-circular-subarray)||Use Kadane's alg to find globalMin and globalMax, return max(globalMax, sum(nums)-globalMin)|
|[134. Gas Station](./questions/134.Gas_Station(Medium).md)|Medium|[Link](https://leetcode.com/problems/gas-station/)|

<!--
|[]()|Medium|[Link]()|||
-->
<br>

___

### 1D DP

1D DP creates dictionary{} or list[] for cache, save time complexity to check repeated cases.

|1D DP|||||
|---|---|---|---|---|
|LeetCode 75|||||
|[1137. N-th Tribonacci Number](./questions/1137.N-th_Tribonacci_Number(Easy).md)|Easy|[Link](https://leetcode.com/problems/n-th-tribonacci-number/)|
|[746. Min Cost Climbing Stairs](./questions/746.Min_Cost_Climbing_Stairs(Easy).md)|Easy|[Link](https://leetcode.com/problems/min-cost-climbing-stairs/)|
|[198. House Robber](./questions/198.House_Robber_(Medium).md)|Medium|[Link](https://leetcode.com/problems/house-robber/)|
|[790. Domino and Tromino Tiling](./questions/790.Domino_and_Tromino_Tiling(Medium).md)|Medium|[Link](https://leetcode.com/problems/domino-and-tromino-tiling/)|
|LeetCode 150|||||
|[70. Climbing Stairs](./questions/70.Climbing_Stairs_(Easy).md)|Easy|[Link](https://leetcode.com/problems/climbing-stairs/)|
|[139. Word Break](./questions/139.Word_Break_(Medium).md)|Medium|[Link](https://leetcode.com/problems/word-break/)|Meta|Build 1d DP to check if an index `s[i:i+len(word)] == word`, then we set `dp[i] = dp[i+len(word)]`|
|[322. Coin Change](./questions/322.Coin_Change(Medium).md)|Medium|[Link](https://leetcode.com/problems/coin-change/)||Build a dp table from range(0, amount+1), calculate how many coins need for each amount, take the current coin + dp(a-c)|
|[300. Longest Increasing Subsequence](./questions/300.Longest_Increasing_Subsequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-increasing-subsequence/)|
|Miscellaneous|||||
|[10. Regular Expression Matching](./questions/10.Regular_Expression_Matching_(Hard).md)|Hard|[Link](https://leetcode.com/problems/regular-expression-matching/)|Amazon OA||


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### 2D DP
Find pattern, base cases, then apply the recurrence relation to fill out the dp table. Sometimes, we can optimize 2D table to 1D array with a dp[] (row).

|2D DP|||||
|---|---|---|---|---|
|[62. Unique Paths](./questions/62.Unique_Paths_(Medium).md)|Medium|[Link](https://leetcode.com/problems/unique-paths/)|
|[72. Edit Distance](./questions/72.Edit_Distance_(Medium).md)|Medium|[Link](https://leetcode.com/problems/edit-distance/)|
|[1143. Longest Common Subsequence](./questions/1143.Longest_Common_Subsequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-common-subsequence/)|
|[518. Coin Change II](./questions/518.Coin_Change_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/coin-change-ii/)|
|[97. Interleaving String](./questions/97.Interleaving_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/interleaving-string/)|
|[309. Best Time to Buy and Sell Stock with Cooldown](./questions/309.Best_Time_to_Buy_and_Sell_Stock_with_Cooldown(Medium).md)|Medium|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/)|
|[714. Best Time to Buy and Sell Stock with Transaction Fee](./questions/714.Best_Time_to_Buy_and_Sell_Stock_with_Transaction_Fee(Medium).md)|Medium|[Link](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/)|
|LeetCode 150||||
|[120. Triangle](./questions/120.Triangle(Medium).md)|Medium|[Link](https://leetcode.com/problems/triangle/description/?envType=study-plan-v2&envId=top-interview-150)|
|[64. Minimum Path Sum](./questions/64.Minimum_Path_Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-path-sum/)||Build a dp table top-bottom, each entry takes its `grid_val + min(dp_left, dp_up)`|
|[63. Unique Paths II](./questions/63.Unique_Paths_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/unique-paths-ii)||Modify the original grid as DP, each grid represents how many ways to go|
|LeetCode 75||||
|Miscellaneous||||
|[312. Burst Balloons](./questions/312.Burst_Balloons(Hard).md)|Hard|[Link](https://leetcode.com/problems/burst-balloons/)||Backtrack + 2D DP|
|[516. Longest Palindromic Subsequence](./questions/516.Longest_Palindromic_Subsequence(Medium).md)|Medium|[Link](https://leetcode.com/problems/longest-palindromic-subsequence)||Build 2d DP with string `s` and its reverse, we compare if two chars are the same, if yes, we upate `dp[r][c] = dp[r-1][c-1]+ 1`, otherwise, we update `dp[r][c] = max(dp[r-1][c], dp[r][c-1]`|
|[1216. Valid Palindrome III](./questions/1216.Valid_Palindrome_III(Hard).md)|Hard|[Link](https://leetcode.com/problems/valid-palindrome-iii)|Meta|Build a dp table of `s` and `s_reversed`, check `len(s) - dp[-1][-1] <= k` so we know we can have k-palindrome|
|[329. Longest Increasing Path in a Matrix](./questions/329.Longest_Increasing_Path_in_a_Matrix(Hard).md)|Hard|[Link](https://leetcode.com/problems/longest-increasing-path-in-a-matrix)|Meta|2D DP + DFS on entry's neighbors|


<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Heap
Create a `heap = []`, then use `heapq.heapify(nums)` or just `heapq.heappush(minHeap, i)` to make a `minHeap` by default. If we want a `maxHeap`, we need to store the negative value `heapq.heappush(maxHeap, -i)`, so the top will be the max value, when we pop the element, remember to **negate** it back.

$O(nlogn)$ for heapify(), $O(logn)$ for heappush() and heappop().

|Heap|||||
|---|---|---|---|---|
|LeetCode 150|||||
|[215. Kth Largest Element in an Array](./questions/215.Kth_Largest_Element_in_an_Array_(Medium).md)|Medium|[Link](https://leetcode.com/problems/kth-largest-element-in-an-array/)|Meta Tag|Maintain a minHeap with k elements, the top of the minHeap is the kth largest element|
|[502. IPO](./questions/502.IPO(Hard).md)|Hard|[Link](https://leetcode.com/problems/ipo/)||Use two heaps|
|[295. Find Median from Data Stream](./questions/295.Find_Median_from_Data_Stream(Hard).md)|Hard|[Link](https://leetcode.com/problems/find-median-from-data-stream/)||Use two heaps|
|NeetCode 150|||||
|[703. Kth Largest Element in a Stream](./questions/703.Kth_Largest_Element_in_a_Stream_(Easy).md)|Easy|[Link](https://leetcode.com/problems/kth-largest-element-in-a-stream/)|
|[1046. Last Stone Weight](./questions/1046.Last_Stone_Weight(Easy).md)|Easy|[Link](https://leetcode.com/problems/last-stone-weight/)|||
|[973. K Closest Points to Origin](./questions/973.K_Closest_Points_to_Origin(Medium).md)|Medium|[Link](https://leetcode.com/problems/k-closest-points-to-origin/)|Meta Tag|Use minHeap to maintain k closest points|
|[621. Task Scheduler](./questions/621.Task_Scheduler(Medium).md)|Medium|[Link](https://leetcode.com/problems/task-scheduler/)||Use heap and deque|
|[355. Design Twitter](./questions/355.Desgin_Twitter(Medium).md)|Medium|[Link](https://leetcode.com/problems/design-twitter/)|
|LeetCode 75|||||
|[2336. Smallest Number in Infinite Set](./questions/2336.Smallest_Number_in_Infinite_Set(Medium).md)|Medium|[Link](https://leetcode.com/problems/smallest-number-in-infinite-set/)||Use a variable to keep track of the smallest when heap is empty|
|[2542. Maximum Subsequence Score](./questions/2542.Maximum_Subsequence_Score(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-subsequence-score/)||Merged two nums together and sort them in descending order, maintain a heap with k elements for v1, update res by max(res, curSum * v2)|
|[2462. Total Cost to Hire K Workers](./questions/2462.Total_Cost_to_Hire_K_Workers(Medium).md)|Medium|[Link](https://leetcode.com/problems/total-cost-to-hire-k-workers/)||Maintain 2 minHeaps for left and right, each of the minHeap has length `candidates`. Choose the lowest from these two minHeap, add new element to the minHeap|

<!--
|[]()|Medium|[Link]()|||
-->
<br>

___

### Prefix Sum

Given an array arr[] of size N, find the prefix sum of the array. A prefix sum array is another array prefixSum[] of the same size, such that the value of prefixSum[i] is arr[0] + arr[1] + arr[2] . . . arr[i].

|Prefix Sum|||||
|---|---|---|---|---|
|LeetCode 75|||
|[1732. Find the Highest Altitude](./questions/1732.Find_the_Highest_Altitude(Easy).md)|Easy|[Link](https://leetcode.com/problems/find-the-highest-altitude/)|
|[724. Find Pivot Index](./questions/724.Find_Pivot_Index(Easy).md)|Easy|[Link](https://leetcode.com/problems/find-pivot-index/)||Maintain prefixSum and suffixSum, return i when they are equal|
|[3028. Ant on the Boundary](./questions/3028.Ant_on_the_Boundary(Easy).md)|Easy|[Link](https://leetcode.com/problems/ant-on-the-boundary/)|Google Tag|
|[560. Subarray Sum Equals K](./questions/560.Subarray_Sum_Equals_K(Medium).md)|Medium|[Link](https://leetcode.com/problems/subarray-sum-equals-k/)|Meta|Use hashmap to save diff = curSum - k with its counts, if a diff = curSum - k in hashmap, we update res with diff's counts|
|Miscellaneous|||||
|[437. Path Sum III](./questions/437.Path_Sum_III(Medium).md)|Medium|[Link](https://leetcode.com/problems/path-sum-iii/)||Use hashmap to keep track of current subtree's prefixSum, and update res with counts of diff = curSum - targetSum in current subtree's hashmap|
|Miscellaneous|||||
|[528. Random Pick with Weight](./questions/528.Random_Pick_with_Weight(Medium).md)|Medium|[Link](https://leetcode.com/problems/random-pick-with-weight)|Meta Tag|First initialize each index from [0, len(w)-1] a probability by w[i] / sum(w), then we calculate the prefixSum of each index. Next, randomly generate a prob within [0, 1], then we use Binary Search to find the index with the closest probability|

<!--
|[]()|Medium|[Link]()|||
-->
<br>

---

### Bit Manipulation
For this type of question, we usually need to perform `&, |` (and, or) operation elementwise, and maybe need to shift bit by `n >> 1` or `n << 1` to move bits. Sometimes, we may need to start comparing two binary string **backward**, then return the reversed `[::-1]` version.

|Bit Manipulation|||||
|---|---|---|---|---|
|[136. Single Number](./questions/136.Single_Number_(Easy).md)|Easy|[Link](https://leetcode.com/problems/single-number/)||XOR will eliminate the same element|
|[191. Number of 1 Bits](./questions/191.Number_of_1_bits_(Easy).md)|Easy|[Link](https://leetcode.com/problems/number-of-1-bits/)|
|[190. Reverse Bits](./questions/190.Reverse_Bits_(Easy).md)|Easy|[Link](https://leetcode.com/problems/reverse-bits/)|
|[67. Add Binary](./questions/67.Add_Binary_(Easy).md)|Easy|[Link](https://leetcode.com/problems/add-binary/)|
|[371. Sum of Two Integers](./questions/371.Sum_of_Two_Integers(Medium).md)|Medium|[Link](https://leetcode.com/problems/sum-of-two-integers/)|
|LeetCode 75||||
|[338. Counting Bits](./questions/338.Counting_Bits(Easy).md)|Easy|[Link](https://leetcode.com/problems/counting-bits/)||Use dp to know how many 1s in the previous bits, and use i & 1 to know if the last bit is 1 or not|
|[1318. Minimum Flips to Make a OR b Equal to c](./questions/1318.Minimum_Flips_to_Make_a_OR_b_Equal_to_c(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-flips-to-make-a-or-b-equal-to-c/)||Compare the last bits of a, b, c, and count how many flips we need|


<!--
|[]()|Medium|[Link]()|
-->
<br>

---

### Math

|Math|||||
|---|---|---|---|---|
|LeetCode 150|||||
|[9. Palindrome Number](./questions/9.Palindrome_Number_(Easy).md)|Easy|[Link](https://leetcode.com/problems/palindrome-number/)|
|[66. Plus One](./questions/66.Plus_One_(Easy).md)|Easy|[Link](https://leetcode.com/problems/plus-one/)|
|[69. Sqrt(x)](./questions/69.Sqrt(x)(Easy).md)|Easy|[Link](https://leetcode.com/problems/sqrtx/)||Run Binary Search in `[0, x]` to find the maximum `m` such that `m^2 <= x`|
|[50. Pow(x, n)](./questions/50.Pow(x,%20n)(Medium).md)|Medium|[Link](https://leetcode.com/problems/powx-n)|Meta Tag|Use a pattern to divide the exponent into half based on even or odd each time, so we can save the time complexity to be $O(log\ n)$|
|Miscellaneous|||||
|[7. Reverse Integer](./questions/7.Reverse_Integer(Medium).md)|Medium|[Link](https://leetcode.com/problems/reverse-integer/)|


<!--
|[]()|Easy|[Link]()|||
-->
<br>

---

### Meta Tag

|Meta Tag|||||
|---|---|---|---|---|
|[1249. Minimum Remove to Make Valid Parentheses](./questions/1249.Minimum_Remove_to_Make_Valid_Parentheses(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses)|Stack|Use stack to save "(" index, when we encounter ")", we pop the last index from stack to close a parenthese. If we encounter ")" with no "(", change it to ""|
|[227. Basic Calculator II](./questions/227.Basic_Calculator_II(Medium).md)|Medium|[Link](https://leetcode.com/problems/basic-calculator-ii)|Stack|Use stack to save previous result, we only append new element with sign into stack when we encounter a new sign|
|[408. Valid Word Abbreviation](./questions/408.Vaild_Word_Abbreviation(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-word-abbreviation?envType=company&envId=facebook&favoriteSlug=facebook-thirty-days)|Array/String|Use pointer for each string to compare, if abbr[j].isdigit(), we extract the number and increment i += int(number)|
|[680. Valid Palindrome II](./questions/680.Valid_Palindrome_II(Easy).md)|Medium|[Link](https://leetcode.com/problems/valid-palindrome-ii)|Two Pointers|Use two ptrs to find where two chars are different, then check if `s[l+1, r]` or `s[l, r-1]` is a valid palindrome|
|[314. Binary Tree Vertical Order Traversal](./questions/314.Binary_Tree_Vertical_Order_Traversal(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-vertical-order-traversal/)|Binary Tree BFS|Run BFS to save all the nodes with their column index [node, col] into deque and save them into hashmap {index: [node]}|
|[215. Kth Largest Element in an Array](./questions/215.Kth_Largest_Element_in_an_Array_(Medium).md)|Medium|[Link](https://leetcode.com/problems/kth-largest-element-in-an-array/)|minHeap|Maintain a minHeap with k elements, the top of the minHeap is the kth largest element|
|[236. Lowest Common Ancestor of a Binary Tree](./questions/236.Lowest_Common_Ancestor_of_a_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)|Binary Tree DFS|Recursively go to root's left and right subtree to find if a node == p or node == q, if both node can be found, means the common ancestor is the root. Otherwise, either l or r is the ancestor|
|[1650. Lowest Common Ancestor of a Binary Tree III](./questions/1650.Lowest_Common_Ancestor_of_a_Binary_Tree_III(Medium).md)|Medium|[Link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree-iii/)|Binary Tree DFS|First save the path from `p` to `root`, traverse from `q` to `root`, the first common node is the LCA|
|[50. Pow(x, n)](./questions/50.Pow(x,%20n)(Medium).md)|Medium|[Link](https://leetcode.com/problems/powx-n)|Math|Use a pattern to divide the exponent into half based on even or odd each time, so we can save the time complexity to be $O(log\ n)$|
|[938. Range Sum of BST](./questions/938.Range_Sum_of_BST(Easy).md)|Medium|[Link](https://leetcode.com/problems/range-sum-of-bst)|Binary Search Tree|Based on the property of BST, we check if current node < low, we recursively call on its right subtree, if current node > high, we recursively call on its left subtree|
|[88. Merge Sorted Array](./questions/88.Merge_Sorted_Array_(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-sorted-array/)|Array/String|Compare nums1, nums2 backward and add the larger value into the end of nums1, use three pointers to keep track|
|[339. Nested List Weight Sum](./questions/339.Nested_List_Weight_Sum(Medium).md)|Medium|[Link](https://leetcode.com/problems/nested-list-weight-sum)|Graph General|Run DFS/BFS on each element in list, if this is element, update total with current depth and element's val. Otherwise, dfs on the list to update total with each element in that list with depth+1|
|[528. Random Pick with Weight](./questions/528.Random_Pick_with_Weight(Medium).md)|Medium|[Link](https://leetcode.com/problems/random-pick-with-weight)|PrefixSum, Binary Search|First initialize each index from [0, len(w)-1] a probability by w[i] / sum(w), then we calculate the prefixSum of each index. Next, randomly generate a prob within [0, 1], then we use Binary Search to find the index with the closest probability|
|[162. Find Peak Element](./questions/162.Find_Peak_Element(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-peak-element/)|Binary Search|Run Binary Search to check if a peak element exists, if not, update l or r pointer to the greater value neighbor|
|[199. Binary Tree Right Side View](./questions/199.Binary_Tree_Right_Side_View_(Medium).md)|Medium|[Link](https://leetcode.com/problems/binary-tree-right-side-view/)|Binary Tree BFS|Run BFS on each level and only append the last node of each level to res[]|
|[71. Simplify Path](./questions/71.Simplify_Path(Medium).md)|Medium|[Link](https://leetcode.com/problems/simplify-path/)|Stack|Detect each char to know if it equals to '/' or not, and use stack to add new file name or pop previous file name|
|[125. Valid Palindrome](./questions/125.Valid_Palindrome_(Easy).md)|Easy|[Link](https://leetcode.com/problems/valid-palindrome/)|Two Pointers|Use l, r ptrs to compare if two elem are the same, increment or decrement ptr if non-alphanumeric elem exists|
|[543. Diameter of Binary Tree](./questions/543.Diameter_of_Binary_Tree(Easy).md)|Easy|[Link](https://leetcode.com/problems/diameter-of-binary-tree)|Binary Tree DFS|Run DFS on each node to get its left, right subtree height and update res with left + right, for each node, return max(left, right) + 1|
|[560. Subarray Sum Equals K](./questions/560.Subarray_Sum_Equals_K(Medium).md)|Medium|[Link](https://leetcode.com/problems/subarray-sum-equals-k/)|prefixSum, hashmap|Use hashmap to save diff = curSum - k with its counts, if a diff = curSum - k in hashmap, we update res with diff's counts|
|[1. Two Sum](./questions/1.Two_Sum_(Easy).md)|Easy|[Link](https://leetcode.com/problems/two-sum/)|Hashmap/Array|Save the remainder (target - nums[i]) into hashmap, when a remainder exists in hashmap, return [i, hashmap[nums[i]]]|
|[973. K Closest Points to Origin](./questions/973.K_Closest_Points_to_Origin(Medium).md)|Medium|[Link](https://leetcode.com/problems/k-closest-points-to-origin/)|Heap|Use minHeap to maintain k closest points|
|[1570. Dot Product of Two Sparse Vectors](./questions/1570.Dot_Product_of_Two_Sparse_Vectors(Medium).md)|Medium|[Link](https://leetcode.com/problems/dot-product-of-two-sparse-vectors)|Array, Hashmap|Use hashmap to save nonzero element with its index as key to hashmap{}. Update res with an index exists in both hashmaps|
|[146. LRU Cache](./questions/146.LRU_Cache(Medium).md)|Medium|[Link](https://leetcode.com/problems/lru-cache/)|Linked List, Hashmap, Deque|Use two dummy nodes to keep track of the LRU and MRU, if we need to remove the LRU, remove `right.prev`. Insert to `left.next` to add new node. Access value by `hashmap[key].val`|
|[791. Custom Sort String](./questions/791.Custom_Sort_String(Medium).md)|Medium|[Link](https://leetcode.com/problems/custom-sort-string)|Array, Hashmap|Use hashmap to save each char in `s` with counts, traverse `order` and add char in hashmap with repeated times to `res`, traverse hashmap to add missing chars to res|
|[1091. Shortest Path in Binary Matrix](./questions/1091.Shortest_Path_in_Binary_Matrix(Medium).md)|Medium|[Link](https://leetcode.com/problems/shortest-path-in-binary-matrix)|Graph BFS|Run BFS to find the shortest path, add all the same level neighbors into visited and deque, update res += 1|
|[56. Merge Intervals](./questions/56.Merge_Intervals(Medium).md)|Medium|[Link](https://leetcode.com/problems/merge-intervals/)|Intervals|Compare new interval with previous interval, if there is overlap, we update the previous interval with [min(x1, x2), max(y1, y2)]. Otherwise, append the new interval to `res[]`|
|[426. Convert Binary Search Tree to Sorted Doubly Linked List](./questions/426.Convert_Binary_Search_Tree_to_Sorted_Doubly_Linked_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list)|Binary Search Tree, Linked List|Run DFS in-order traversal: left->root->right and update `head.right = node` and `node.left = head`, then update `head = node`. Finally, connect head and dummy together to be circular|
|[1762. Buildings With an Ocean View](./questions/1762.Buildings_With_an_Ocean_View(Medium).md)|Medium|[Link](https://leetcode.com/problems/buildings-with-an-ocean-view)|Array|Traverse heights from right to left, save the last height as curMax, if heights[i] > curMax, update curMax and save its index into res[], finally, return the reversed res[]|
|[23. Merge k Sorted Lists](./questions/23.Merge_k_Sorted_Lists(Hard).md)|Hard|[Link](https://leetcode.com/problems/merge-k-sorted-lists/)|Linked List|Merge 2 lists each time and replace `lists` with the merged sorted lists|
|[863. All Nodes Distance K in Binary Tree](./questions/863.All_Nodes_Distance_K_in_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree)|Binary Tree BFS|Build an undirected graph to connect two connected nodes together, then run BFS from `target` to add all its neighbor nodes into deque, when distance == k, we append the node.val into res[]|
|[921. Minimum Add to Make Parentheses Valid](./questions/921.Minimum_Add_to_Make_Parentheses_Valid(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid)|String, Stack|Count "(" and ")", when encounter ")", check if we have "(" to remove or decrement, otherwise, increment the count of ")"|
|[346. Moving Average from Data Stream](./questions/346.Moving_Average_from_Data_Stream(Medium).md)|Easy|[Link](https://leetcode.com/problems/moving-average-from-data-stream)|Deque|Use deque[] to save `k` elements with `curSum`, when `len(deque) == size`, we remove the left-most element then add the right-most element into `deque[]`|
|[986. Interval List Intersections](./questions/986.Interval_List_Intersections(Medium).md)|Medium|[Link](https://leetcode.com/problems/interval-list-intersections)|Intervals|Use two ptrs to find the intersection, keep the interval with greater end|
|[138. Copy List with Random Pointer](./questions/138.Copy_List_With_Random_Pointer(Medium).md)|Medium|[Link](https://leetcode.com/problems/copy-list-with-random-pointer/)|Linked List|Use hashmap to save each node with new node, traverse `head` to assign .next, .random to be the new node in hashmap|
|[65. Valid Number](./questions/65.Valid_Number(Hard).md)|Hard|[Link](https://leetcode.com/problems/valid-number)|Array/String|Keep track of `seenDigit`, `seenExponent`, `seenDot`, then we check if the current char is valid base on some rules|
|[129. Sum Root to Leaf Numbers](./questions/129.Sum_Root_to_Leaf_Numbers(Medium).md)|Medium|[Link](https://leetcode.com/problems/sum-root-to-leaf-numbers)|Binary Tree DFS|Run DFS to add every number in the path, when reaches the leaf node, return `curSum`, return `node.left` + `node.right`|
|[1004. Max Consecutive Ones III](./questions/1004.Max_Consecutive_Ones_III(Medium).md)|Medium|[Link](https://leetcode.com/problems/max-consecutive-ones-iii/)|Sliding window|Maintain sliding window with at most k `0`, each time if `nums[r]` is `0`, we decrement k, when k is negative, we update `l += 1`, same as moving the current max sliding window to the right|
|[827. Making A Large Island](./questions/827.Making_A_Large_Island(Hard).md)|Medium|[Link](https://leetcode.com/problems/making-a-large-island)|Graph General|Run DFS/BFS start from an entry with 1 to change this island's every entry to be `index`. Traverse `grid` again to run BFS on `0` to calculate the area of its neighbors + 1|
|[270. Closest Binary Search Tree Value](./questions/270.Closest_Binary_Search_Tree_Value(Easy).md)|Easy|[Link](https://leetcode.com/problems/closest-binary-search-tree-value)|Binary Search Tree|Compare the `abs(node.val-target)` with `abs(res-target)`, if they equal, update res to be the smaller val, otherwise, update res to the one will smaller difference. Run DFS with Binary Search to find the closer one|
|[76. Minimum Window Substring](./questions/76.Minimum_Window_Substring(Hard).md)|Hard|[Link](https://leetcode.com/problems/minimum-window-substring/)|Sliding Window|Use two hashmaps and 2 counts to keep track of every chars, update res when sCount == tCount, and we start shrinking the sliding window|
|[958. Check Completeness of a Binary Tree](./questions/958.Check_Completeness_of_a_Binary_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/check-completeness-of-a-binary-tree)|Binary Tree BFS|Run BFS with `seenNull` to check if a null node exists, if it exists and we have other non-null nodes, return False|
|[415. Add Strings](./questions/415.Add_Strings(Easy).md)|Easy|[Link](https://leetcode.com/problems/add-strings)|Array/String|Use two ptrs to access two chars backward + carry to perform addition, and append the result to `[]`|
|[2. Add Two Numbers](./questions/2.Add_Two_Numbers_(Medium).md)|Medium|[Link](https://leetcode.com/problems/add-two-numbers/)|Linked List|Create dummy node with `carry` to save the sum|
|[1216. Valid Palindrome III](./questions/1216.Valid_Palindrome_III(Hard).md)|Hard|[Link](https://leetcode.com/problems/valid-palindrome-iii)|2D DP|Build a dp table of `s` and `s_reversed`, check `len(s) - dp[-1][-1] <= k` so we know we can have k-palindrome|
|[31. Next Permutation](./questions/31.Next_Permutation(Medium).md)|Medium|[Link](https://leetcode.com/problems/next-permutation)|Array|Find index such that `nums[i] < nums[i+1]`, then find another element `nums[j] > nums[i]` from backward, swap them, and reverse `nums[i+1:]`|
|[78. Subsets](./questions/78.Subsets_(Medium).md)|Medium|[Link](https://leetcode.com/problems/subsets)|Backtrack|Use backtrack with index `i` to keep track of current `curSum[]`, when `i==len(nums)`, we append `curSum` into `res[]` and return, we pop the last element and add new element into `curSum` with `i += 1`|
|[133. Clone Graph](./questions/133.Clone_Graph(Medium).md)|Medium|[Link](https://leetcode.com/problems/clone-graph/)|Graph General|Create each node's copy into `hashmap{node: new_node}`, run DFS to append each node's neighbors|
|[987. Vertical Order Traversal of a Binary Tree](./questions/987.Vertical_Order_Traversal_of_a_Binary_Tree(Hard).md)|Hard|[Link](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree)|Binary Tree General|Save `(node, row, col)` into `deque[]`, and run BFS to append `node.left` with `(row+1, col-1)` and `node.right` with `(row+1, col+1)`. Add all nodes with the same col into `hashmap{col: [node.val]}`. Sort `col` and `row` in the end|
|[670. Maximum Swap](./questions/670.Maximum_Swap(Medium).md)|Medium|[Link](https://leetcode.com/problems/maximum-swap)|Greedy|Use variables to keep track of the current maximum index and swap indices, update them based on `num[i]`, finally check if both swap_ids are valid and swap, then return|
|[721. Accounts Merge](./questions/721.Accounts_Merge(Medium).md)|Medium|[Link](https://leetcode.com/problems/accounts-merge)|Union Find, DFS|Use hashmap to map `{email: id}` use `uf.union()` for existed email's id, then use `uf.find()` to find root_id and group `{id: [email]}`, lastly, follow the format to return|
|[1539. Kth Missing Positive Number](./questions/1539.Kth_Missing_Positive_Number(Easy).md)|Easy|[Link](https://leetcode.com/problems/kth-missing-positive-number)|Binary Search|Run Binary Search with k on the difference between the original `arr` and current `arr`|
|[139. Word Break](./questions/139.Word_Break_(Medium).md)|Medium|[Link](https://leetcode.com/problems/word-break/)|1D DP|Build 1d DP to check if an index `s[i:i+len(word)] == word`, then we set `dp[i] = dp[i+len(word)]`|
|[708. Insert into a Sorted Circular Linked List](./questions/708.Insert_into_a_Sorted_Circular_Linked_List(Medium).md)|Medium|[Link](https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list)|Linked List|Use `prev`, `curr` to keep track of two nodes and compare their values with `insertVal` and add new Node between `prev` and `curr`|
|[34. Find First and Last Position of Element in Sorted Array](./questions/34.Find_First_and_Last_Position_of_Element_in_Sorted_Array(Medium).md)|Medium|[Link](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)|Binary Search|Find the left end and right end of `nums` by running Binary Search twice, update different ptr each time|
|[1768. Merge Strings Alternately](./questions/1768.Merge_Strings_Alternately(Easy).md)|Easy|[Link](https://leetcode.com/problems/merge-strings-alternately/)|Two Pointers|Use two ptrs to add chars from two strings alternatively, then check to add the remaining from `word1` or `word2`|
|[498. Diagonal Traverse](./questions/498.Diagonal_Traverse(Medium).md)|Medium|[Link](https://leetcode.com/problems/diagonal-traverse)|Matrix|Save the diagonal index by (r+c) with values `{diagonal_idx: [val]}`, then check `idx % 2` to decide whether reverse the saved values' list or not|
|[605. Can Place Flowers](./questions/605.Can_Place_Flowers(Easy).md)|Easy|[Link](https://leetcode.com/problems/can-place-flowers/)|Array|Append `0` to two ends of `flowerbed`, check `flowerbed[i]` and its neighbors are all `0` or not, if so, replace `0` to `1` and decrement `n`. Return `n <= 0`|
|[329. Longest Increasing Path in a Matrix](./questions/329.Longest_Increasing_Path_in_a_Matrix(Hard).md)|Hard|[Link](https://leetcode.com/problems/longest-increasing-path-in-a-matrix)|2D DP, Graph General|2D DP + DFS on entry's neighbors|
|[766. Toeplitz Matrix](./questions/766.Toeplitz_Matrix(Easy).md)|Easy|[Link](https://leetcode.com/problems/toeplitz-matrix)|Matrix|Compare each entry with their bottom-right neighbor (if exists)|
|[1443. Minimum Time to Collect All Apples in a Tree](./questions/1443.Minimum_Time_to_Collect_All_Apples_in_a_Tree(Medium).md)|Medium|[Link](https://leetcode.com/problems/minimum-time-to-collect-all-apples-in-a-tree)|Graph General, DFS|Build adjacent graph and run DFS to search if node's children has apple, if so return `secs + 2`, otherwise, return 2 if `node` is apple, `0` else|
|[224. Basic Calculator](./questions/224.Basic_Calculator(Hard).md)|Hard|[Link](https://leetcode.com/problems/basic-calculator/)|Stack|Use `res, sign ,curr` to keep track of previous operation result, update `res` when we have new sign, append `res, sign` into stack[] when we have "(". Calculate result within `()`, and pop everything back from stack[], reset variables|
|一亩三分地|||||
|[347. Top K Frequent Elements](./questions/347.Top_K_Frequent_Elements(Medium).md)|Medium|[Link](https://leetcode.com/problems/top-k-frequent-elements/)|minHeap|Count num with their counts, use minHeap to sort the counts then append num k times from minHeap to res[]|
|[71. Simplify Path](./questions/71.Simplify_Path(Medium).md)|Medium|[Link](https://leetcode.com/problems/simplify-path/)|Stack|Detect each char to know if it equals to '/' or not, and use stack to add new file name or pop previous file name|
|[698. Partition to K Equal Sum Subsets](./questions/698.Partition_to_K_Equal_Sum_Subsets(Medium).md)|Medium|[Link](https://leetcode.com/problems/partition-to-k-equal-sum-subsets)|Array, Backtrack|Use Backtrack to try each element with other elements subarray, if the subarray equals to k, we mark all elements to be visited, run backtrack from the beginning again. For every subarray, we decrement k -= 1, return True when k == 0|
|[36. Valid Sudoku](./questions/36.Valid_Sudoku_(Medium).md)|Medium|[Link](https://leetcode.com/problems/valid-sudoku/)|Matrix|Use three dicts to check repetition|
|[37. Sudoku Solver](./questions/37.Sudoku_Solver(Hard).md)|Medium|[Link](https://leetcode.com/problems/sudoku-solver)|Matrix, Backtrack|Use 3 sets to save existed vals, backtrack number `i` from `[1, 9]` for `'.'`|
|[636. Exclusive Time of Functions](./questions/636.Exclusive_Time_of_Functions(Medium).md)|Medium|[Link](https://leetcode.com/problems/exclusive-time-of-functions)|Meta|Use stack to store ids, identify `start` or `end`, and add the difference to `res[i]`|


<!--
|[]()|Easy|[Link]()|||
-->

<br> <br>

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt="CC BY-NC-SA" title="CC BY-NC-SA"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt="BY: credit must be given to the creator" title="BY: credit must be given to the creator"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt="NC: Only noncommercial uses of the work are permitted" title="NC: Only noncommercial uses of the work are permitted"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt="SA: Adaptations must be shared under the same terms" title="SA: Adaptations must be shared under the same terms">