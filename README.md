# henok2924.github.io

quesion 1 

Algorithm

Iterate through each element in the array using an outer loop.

For each element, iterate through the rest of the array using an inner loop.

Check if the sum of the two selected elements equals the target.

If found, print the indices of the two elements.

Continue searching if required (or return if only one pair is needed).

Complexity Analysis

Time Complexity: O(n²) due to the nested loops iterating through all pairs.




Question 2

Algorithm Explanation

Iterate through the array: Use two nested loops to check all pairs of numbers.

Check if their sum equals the target: If nums[i] + nums[j] == target, print their indices.

Complexity Analysis

Time Complexity: O(n^2) due to the nested loop iterating over all pairs.



Question 3

Algorithm:

Ensure nums1 is the smaller array.

Use binary search on nums1.

Partition both arrays such that all elements on the left are smaller than those on the right.

If partitioning conditions are met:

If total length is odd, return the maximum of the left half.

If total length is even, return the average of max(left half) and min(right half).

Complexity Analysis:

Time Complexity: O(log(min(m, n))) due to binary search.



question 5 

Algorithm:

Use a min-heap to keep track of the smallest elements.

Extract the smallest node and add its next node to the heap.

Repeat until all nodes are merged.

Complexity Analysis:

Time Complexity: O(N log k) where N is the total number of nodes and k is the number of lists.
