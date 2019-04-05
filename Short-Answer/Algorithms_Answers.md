Add your answers to the Algorithms exercises here.
Exercise I
a. Runtime is constant Time 0(n) because in the case of n=0, the number of operations would change

b. O(n^4) because there are 4 nested loops 

c. 0(c) because regardless of the number of bunnies, the number of operations will remain the same, even in the case of 0

Exercise II
Questions: 
1. Does this question include real-world physics logic?

Since, it is reasonable to assume an egg will be broken quite easily, it would be most effective to start from floor 1.

def egg_break_threshhold(f):
    #for every floor of f drop an egg
    #check to see if egg is broken
    #if it is not broken increase count of f by 1 
    # if broken higher than 1st floor return "These eggs are strong"
    # If broken on 1st floor return "Did this really need to be tested?"

    0(n) - Linear time because depending on the outcome of egg broken on the first floor, extra operations would have to be used.
