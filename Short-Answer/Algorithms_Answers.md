#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n) - the number of times the loop runs is linear to the input n. An increase in n signifies a corresponding increase in the number of times the loop will run


b)O(log n) - the number of times the loop runs is increasing slower than the size of the input is increasing


c)O(n) - the function is being called recursively n times before reaching base case so it is linear

## Exercise II

Divide the number of floors, n into 3
Go the last floor of the first_fraction and drop an egg
If the egg breaks, the number of floors to check now is that first_fraction
Repeat the cycle
If the egg doesn't break, divide n-first_fraction into 3 and repeat until you find the floor at which it starts to break

Time complexity is O(log n)