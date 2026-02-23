# Sorting_Lab_1
Part 1 of the Sorting Lab in Week 3 CISC 187
## Task 1
The time complexity of an algorithm that takes 4N + 16 steps would be defined as O(N) in Big-O notation. The reason for this being that as N grows the constant values 4 and 16 become negligible, making the time complexity essentially n steps and allowing us to drop our constants.

## Task 2
Much like task 1 we can drop our constant values. In this case an algorithm that takes 2N^2 steps would simplify to O(N^2) in Big-O notation. 

## Task 3
We're presented with code that contains two loops. Loop 1 acceses each number in the array and doubles it, this operation is simply linear O(N), we access one value at a time and alter one value at a time. Loop 2 sums all numbers, again linear O(N), and simply accesses an element and adds it to a running sum. This process is two linear operations summed, n + n, or 2n. Just like in task 1 and 2 we can drop the constants resulting in a Big O notation of O(N).

## Task 4
The code for task 4 is similar to task 3 but in a different summation process. For each element in the array we perform 3 operations, printing uppercase, lowercase, and captitalized. This means we perform 3 operation per an element, or 3n steps. Again this is a linear process, resulting in a Big O notation of O(N) since we drop constants with time complexity.

## Task 5
Braindump: First instinct based on code alone is O(N^2). Two loops, check n, if n is even, for each even n, add every other number. so n(n-1) the -1 being itself...