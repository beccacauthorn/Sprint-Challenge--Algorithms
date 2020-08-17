#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The runtime is O(n). To get the answer you have to count or estimate how many times the loop is going to be iterated over. It will finish in n steps because the variable increments by n squared and the highest value it can take is n cubed. 


b) The runtime is O(n log n). The reasonging is that the inner loop takes log n and the outer loop takes n. 


c)The runtime is O(n) because the recursive calls increase by one each time. 

## Exercise II
The runtime complexity is O(log n) due to using modified binary search to solve the problem. First, go the floor at the middle and drop an egg. If the eggs breaks, then the first floor where the egg breaks has to be that floor or lower and cannot be higher so you take the lower half of the floors and continue recursively. If the egg does not break then you go higher. 

