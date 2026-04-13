Linear search:

Linear search has a time complexity that depends on the number of elements in the array. In the best case, when the target
value is found at the first position, the time complexity is O(1). If the target is found at the second position, it takes 
2 steps, and so on. In the worst case, when the target value is not present or is at the last position, the algorithm takes 
n steps, giving a time complexity of O(n).


Binary search :

Binary search works differently because it repeatedly divides the search space in half (and it only works on a sorted array).
Here’s a clear explanation:
Binary search has a time complexity based on how many times the array can be divided.
In the best case, the target element is found at the middle of the array on the first check, so the time complexity is O(1).
In the worst case, the algorithm keeps dividing the array into halves until only one element remains. This takes about log₂(n)
steps, so the time complexity is O(log n).
So overall, the time complexity of binary search is O(log n) in the worst and average cases, and O(1) in the best case.


Bubble sort:

Bubble sort works by repeatedly comparing adjacent elements in an array and swapping them if they are in the wrong order. After each pass, the largest element moves to the end of the array.

In the best case, when the array is already sorted, the time complexity is O(n) (with optimization). In the average and worst cases, it takes multiple passes through the array, resulting in a time complexity of O(n²).

for every iteration of the outer loop, there is no need to go till the end of the array in the inner loop. This is because after each pass, the largest element is already placed at the end, so the sorted elements do not need to be compared again.


Selection Sort

Selection sort works by repeatedly finding the smallest element from the unsorted part of the array and placing it at the correct position. In each pass, it selects the minimum element and swaps it with the first unsorted element.

In the best, average, and worst cases, the time complexity is O(n²) because it always checks all remaining elements, even if the array is already sorted.
