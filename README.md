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
