# Binomial Coefficients

## Subsets

Subsets are one mathematical construct we can count. If we wanted to count how many possible subsets a set has (in set notation this would be expressed as $|\mathbb{P}{(A)}|$.
To build a subset we decide if each element will be a meber of the subset, a yes` or `no` for each member. Thus by the multiplicitve principle we can express this yes/no concept as $2 \cdot 2 \cdot 2 \cdot 2 \cdot 2 = 2^5$

To determine how many of these subsets have a specific size we can count them each individually. When we do this we see that the numbers mirror e.g. there is an equal number of subsets with a cardinality of 1 as there those with a cardinality of 4.

## Bit Strings 

A bit string is a series of 0's and 1's. A bit string's weight is the number of 1's in it.
$B^n$ is the set of all n-bit strings. $B_k^n$ is the set of n-bit strings with a weight of $k$.

To find the number of bit strings with a specific length we can use the multiplicative principle in the same way we did for subsets. 
To find the number of but strings with a specific length we have to include the set of bit strings with a weight of $k-1$ and lengths of $n-1$ and the set of bit strings with weights of $k$ and lengths of $n-1$.

## Lattice Paths

The integer lattice is the set of all points in the Cartesian plane where both x and y ar integers.
A lattice path is the shortest path between two points moving along the integer lattice.
This case like the others can be represented with a yes and no, a 0 or a 1. If the target point is to the right and above the starting point then your options are to move to the right or up to stay on a shortest path.

## Binomial Coefficients

Binomial Coefficients are denoted as n choose k. This costruct is the number of subsets of a set of size n with a cardinality of k.
This is equal to $|B_k^n|$ and is also the lattice path2s of length n containing k steps to the right.
If we arrange binomial coefficients into a triangle we get Pascal's triangle which we can then use to calculate any binomial coefficient.

## Exercises

1. Let $S = {1, 2, 3, 4, 5, 6}$
    (a) How many subsets are there total?
        $$2 \cdot 2 \cdot 2 \cdot 2 \cdot 2 \cdot 2 = 2^6=64$$
    (b) How many subsets have {2, 3, 5} as a subset?
        $$2^3=8$$
    (c) How many subsets contain at least one odd number?
        $$2^6 - 2^3 = 56$$ This is because there are only 3 options that are even so the number of subsets with only even numbers is $2^3$.
    (d) How many subsets contain exactly one even number?
        $$3(2^3)$$

2. Let $S = {1, 2, 3, 4, 5, 6}$
    (a) How many subsets are there of cardinality 4?
        $${6 \choose 4}=15$$
    (b) How many subsets of cardinality 4 have {2, 3, 5} as a subset?
        $${3 \choose 1}$$ There are only 3 chooses left and we only need to pick one
    (c) How many subsets of cardinality 4 contain at least one odd number?
        Same as a, there are only 3 even numbers.
    (d) How many subsets of cardinality 4 contain exactly one even number?
        Same as c

3. Let $A = {1, 2, 3, . . . , 9}$
    (a) How many subsets of A are there? That is, find $|\mathb{P}(A)|$. Explain.
        $$2^9=512$$
    (b) How many subsets of A contain exactly 5 elements? Explain.
        $${9 \choose 5} = 126$$
    (c) How many subsets of A contain only even numbers? Explain.
        $$2^4 - 1=15$$ Four possible even numbers.
    (d) How many subsets of A contain an even number of elements? Explain.
        $$\frac{2^9}{2}=256$$

4. (Presented in class)

5. You break your piggy-bank to discover lots of pennies and nickels. You start arranging these in rows of 6 coins.
    (a) You find yourself making rows containing an equal number of pennies and nickels. For fun, you decide to lay out every possible such row. How many coins will you need?
        $${6 \choose 3} * 6 = 20 * 6=120$$
    (b) How many coins would you need to make all possible rows of 6 coins (not necessarily with equal number of pennies and nickels)?
        $$6(2^6)=6*64=384$$

6. How many 10-bit strings contain 6 or more 1’s?
     $${10 \choose 6} + {10 \choose 7} + {10 \choose 8} + {10 \choose 9} + {10 \choose 10}=210 + 120 + 45 + 10 + 1=386$$

7. (Presented in class)

8. (Presented in class)

9. What is the coefficient of $x^9$ in the expansion of $(x + 1)^14 + x^3(x + 2)^15$?
    Not sure on this one

10. How many lattice paths start at (3,3) and
    (a) end at (10,10)?
        $${14 \choose 7} = 3432$$
    (b) end at (10,10) and pass through (5,7)?
        $${6 \choose 2}{8 \choose 5}=840$$
    (c) end at (10,10) and avoid (5,7)?
        $$3432 - 840 = 2592$$

