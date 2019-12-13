#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n) because how many times the while loop runs depends directly on the value of n


b)O(n^2) because of the nested loop.  Both loop sizes are dependent on the value of n, causing the time complexity to be n raised to the 2nd degree.


c)O(n) also because you are calling a recursive function until it hits 0 and the code is dependent on the value of bunnies

## Exercise II

This is just like how to find someone in a big phone book.  

You would want to go to the middle floor and check if it breaks.  If it doesn't break, then you go up half the remaining floors and check again.

Do that until it breaks and then you can come down each floor until you find the last one it breaks and then the next one that it doesn't.

this would be O(log n) because of constantly cutting the floors in smaller and smaller groups.
