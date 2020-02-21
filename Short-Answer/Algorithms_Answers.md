#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
Line 1 is O(1) constant complexity
Line 2 is O(n * n * n) => O(n ^ 3) cubic complexity
Line 3 is O(1) constant complexity

Adding them up: 0(1) + O(n * n * n) + 0(1) = 0(n ^ 3) which is a cubic runtime

## The complexity of an algorithm is said to be cubic when the steps required to execute an algorithm are a cubic function of the number of items in the input. Cubic complexity is denoted as O(n^3). 

b)
Line 1 is O(1) constant complexity
Line 2 is O(n) linear complexity
Line 3 is O(1) constant complexity
Line 4 is O(n * n) quadratic complexity
Line 5 is O(1) constant complexity
Line 6 is O(1) constant complexity

Adding it all up: O(n ^ 2 + n + 4) gives O(n ^ 2) which is a Quadratic Time

## The complexity of an algorithm is said to be quadratic when the steps required to execute an algorithm are a quadratic function of the number of items in the input. Quadratic complexity is denoted as O(n^2). 


c)
Line 2 is O(1) constant complexity
Line 3 is O(1) constant complexity
Line 5 is O(n) linear complexity

Adding it all up: O(n + 2) gives O(n) which is a Linear Time

## The complexity of an algorithm is said to be linear if the steps required to complete the execution of an algorithm increase or decrease linearly with the number of inputs. Linear complexity is denoted by O(n).

## Exercise II
1. Get the numbers of floors in the storey, `n` O(1)
2. Pick a pivot to determine the current floor, f. In this case, the pivot can be the middle floor which is `n//2`.Round up the division into a whole number using int  O(1)
3. Start throwing eggs from this middle floor O(1)
4. If the egg doesn't break, go up the floor and throw egg again. Repeat this process till the egg breaks. Return the floor egg gets broken. O(n)


The total runtime would be linear complexity


## USsing recursion
1. Base case is the floor the egg gets broken
2. Else go up a floor and throw the egg again. Check if broken.
3. If not, repeat process, go up and throw eggs again.
4. Return the floor, f where the egg gets broken