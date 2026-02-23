# Sorting_Lab_1
Part 1 of the Sorting Lab in Week 3 CISC 187
## Task 1
The time complexity of an algorithm that takes 4N + 16 steps would be defined as O(N) in Big-O notation. The reason for this being that as N grows the constant values 4 and 16 become negligible, making the linear operation define the growth rate of the algorithm and allowing us to drop our constants.

## Task 2
Much like task 1 we can drop our constant values. In this case an algorithm that takes 2N^2 steps would simplify to O(N^2) in Big-O notation. 

## Task 3
We're presented with code that contains two sequential and not nested loops. Loop 1 acceses each number in the array and doubles it, this operation is simply linear O(N), we access one value at a time and alter one value at a time. Loop 2 sums all numbers, again linear O(N), and simply acceses an element and adds it to a running sum. This process is two linear operations summed, n + n = 2n. Just like in task 1 and 2 we can drop the constants resulting in a Big O notation of O(N).

## Task 4
The code for task 4 is similar to task 3 but in a different summation process. For each element in the array we perform 3 operations, printing uppercase, lowercase, and capitalized. This means we perform 3 operation per an element, or 3n steps. Note another constant could be considered in the processing time, being the average length of a string, but we can again drop it since it is constant and wouldn't change our Big O classification. Again this is a linear process, resulting in a Big O notation of O(N) since we drop constants with time complexity. 

## Task 5
In this code we have two loops. The outer loop iterates through every element in the array to check for even indices. The inner loop is entered about half of the time. Then if the index is even, we add every other value in it, which would be n steps. The inner loop executes about n/2 times, and when it does n operations are performed. This makes the algorithm steps become n/2 * n = n<SUP>2<SUP> / 2, again allowing us to drop the 1/2 constant and extrapolate this operation as an Big O(N^2). Demonstrating that even if we perform an operation half of the time, are scaling is still N^2 based on our algorithm.
