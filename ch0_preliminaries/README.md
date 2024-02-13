# Chapter 0 - Preliminaries 

## What is Discrete Mathematics?

Discrete Mathematics is mathematics with discrete number systems.

Fields is Discrete Math indlude:
 - combinatorics
 - sequences
 - symbolic logic
 - graph theory

## Mathematical Statements

Atomic statements are logical statements that can't be reduced.

Molecular statemnts are combinations of atomic statements

Types of logical connectives

|      Name     | Symbol | Purpose |
|---------------|--------|---------|
| conjunction   |$\wedge$| True when both are true |
| disjunction   | $\vee$ | True when either is true |
| implication   |  $\to$ | True when the left is false or the right is true |
| biconditional |$\equiv$| True when two values are |
| negation      | $\neg$ | True when a value is false. |

[Implications](../presentations/0.2-Implications.md)

Take the example $P(n)\to \negP(n+7)$ if P(n) means P is primeo

This is a predicate because it contains a variable.

## Sets

$$A={1, 2, 3}$$

This is a set. It is read as "A is the set containing the elements 1, 2, and 3."

$$A \in {a, b, c}$$

$a$ is a member of the set containg $a$, $b$, and $c$. If there is a line through the $\in$ ($\notin$) then the item is not a member of the set.

Set notation can be used to represent infinite sets:
$$A={x\in \N : \exists n \in \N (x=2n)}$$
is the set of all natural numbers.

Special Sets:
| Symbol |    Name   |
|--------|-----------|
|  $\0$  | Empty Set |
|  $\N$  | Natural Numbers|
|  $\Z$  | Integers  |


![](../resources/set_notation.png)

## Functions

A fucnction assigns every unqiue input to an output.

Functions have both a domain and range the set of values including in their inputs and outputs respectivly.

A function is surjective when every value of its codomain is a member of its range.

A function is injective if it is one to one, where each value of the domain maps to a unique value of the range.

A bijection is a function that is both injective and surjective.

