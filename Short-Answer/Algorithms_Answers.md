#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) because the wile loop is based on the input size. As n is increased in the problem, so will the amount
    of iterations throughout the loop.


b) O(n^2) This is quadratic time because the program is running 2 separate loops based the input size of n. As the
    size of n increase, so will the size of BOTH loops, which raises the factor of n by 2. (n * n)


c) O(1) This is a constant run time since the problem is a basic arithmetic operation with no loops. 

## Exercise II

I would solve this problem by doing a recursive function for the n-story building and divide the floors until I reached
a floor level where once I dropped the egg, it doesn't break.

I would first initiate a test floor variable.

Take 0 and n-story of the building and divide it by 2 to get the middle floor of the building.

On that floor, drop the egg

If the egg breaks, I will recurse the function, using that current floor as the highest floor possible.

Take 0 and the new highest floor of the building and divide it by 2 again to get the new test floor.

If it breaks again, repeat. If the egg survives, set the current test floor as the lowest floor possible instead and repeat.

Once the lowest and highest floor possible meets, that should give us the value of f.

    
