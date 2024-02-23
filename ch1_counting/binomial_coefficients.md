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
This is equal to $|B_k^n|$ and is also the lattic paths of length n containing k steps to the right.
If we arrange binomial coefficients into a triangle we get Pascal's triangle which we can then use to calculate any binomial coefficient.
