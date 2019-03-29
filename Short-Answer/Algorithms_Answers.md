Add your answers to the Algorithms exercises here.

## Exercise I

    A:  Time complexity is O(n). It will take n times to run and finish the
    while loop for any n greater than 0.
    
    B: Time complexity is O(n^3). There are three nested loops being run
    that depend on the value of n. The fourth loop only runs a fixed number
    of times (less than 10) so it has a constant run time. The other three
    loops have a complexity of O(n) each and there are three of them so 
    the time complexity of the entire algo is O(n^3).
    
    C: Time complexity is O(n). bunnyEars will get ran recursively until
    the input reaches 0.
    
## Exercise II

    1. Use divide-and-conquer method to find the f floor. 