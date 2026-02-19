# Sorting_Lab_1
Part 1 of the Sorting Lab in Week 3 CISC 187
## Task 1
The time complexity of an algorithm that takes 4N + 16 steps would be defined as O(N) in Big-O notation. The reason for this being that as N grows the constant values 4 and 16 become negligible, making the time complexity essentially N.

## Task 2
Much like task 1 we can drop our constant values. In this case an algorithm that takes 2N^2 steps would simplify to O(N^2) in Big-O notation. 

## Task 3
Braindump: doubling of each number is n steps, summing all numbers is n steps. 2n = O(N) ? No nested loops, usually indicative of n^2, so assuming it's linear.
## Task 4
Braindump: Also O(N)? each n has 3 steps, so that simply 3*n, drop the constant and we have a linear time complexity... hints: also only one loop
## Task 5
Braindump: First instinct based on code alone is O(N^2). Two loops, check n, if n is even, for each even n, add every other number. so n(n-1) the -1 being itself...