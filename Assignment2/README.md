Qyestion 1

Algorithm Explanation
To solve this problem efficiently in linear time O(n) and constant space O(1), we use the Boyer-Moore Voting Algorithm.

Complexity Analysis

Time Complexity:

O(n): The algorithm iterates through the array only once, making it very efficient.

Space Complexity:

O(1): No additional data structures are used, making the solution space-efficient.


Question 2 
Algorithm Explanation

The partition function selects the last element as the pivot, reorders elements, and returns the pivot index. The kthLargest function applies Quickselect:

Converts k to an index (len(nums) - k).

Recursively partitions until the target index is found.

Complexity Analysis

Best/Average Case: O(n) (balanced partitioning).

Worst Case: O(n²) (unbalanced partitioning).

Space Complexity: O(1) (in-place) or O(log n) (recursion depth).

Efficiency Considerations

More efficient than sorting (O(n log n)).

Using Median of Medians can improve worst-case performance.

Question 3

Quickselect Algorithm (k-th Largest Element)

Uses partitioning (similar to QuickSort) to find the k-th largest element in O(n) average time.

Converts k to an index (len(nums) - k) and recursively partitions until the target index is found.

Time Complexity: O(n) average, O(n²) worst case.

Space Complexity: O(1) in-place, O(log n) recursion depth.

Maximum Gap Algorithm (Bucket Sort)

Finds the max difference between consecutive elements in sorted order in O(n) time.

Uses bucket sorting:

Determines min/max values.

Divides numbers into buckets.

Finds max gap between non-empty buckets.

Time Complexity: O(n), Space Complexity: O(n).

Question 4
Quickselect (k-th Largest Element)

Finds the k-th largest element using partitioning.

Time: O(n) avg, O(n²) worst; Space: O(1).

Maximum Gap (Bucket Sort)

Finds the max difference between consecutive elements in O(n).

Time: O(n); Space: O(n).

Remove Duplicates (Lexicographically Smallest String)

Uses a stack to maintain order and remove duplicates.

Time: O(n); Space: O(n).

