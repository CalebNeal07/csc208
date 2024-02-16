# Counting
### Caleb O'Neal - 2024-2-15
---

## Additive and Multiplicative Principles - Pg. 57

> Additive Principle: If A has $m$ states and B has $n$ states and you are selecting $A or B$, e.g. the two states are disjoint, then the number of possible states is $m + n$.

Disjoint means A and B cannot occur simultaneosly.\

> Multiplicitive Principle: If A has $m$ states and each possibile state also allows for $n$ states of B then the event $A and B$ can occur $m*n$ ways.

Both the additive and multiplicitave principles hold for cases with more than two events.\

If we represnet A and B as sets we can define the additive principle as $|A \cup B|=|A|+|B|$.

> Cartesian Product: $ A \times B={(x, y) : x \in A \wedge y \in B}

We can do the same for the multiplicitave principle using the cartesian product. $|A \times B|=|A|*|B|$.

The above reprensetation of the additive principle does not account for the intersection of the two sets and should be revised as $|A \cup B|=|A|+|B|-|A \cap B|$.

This can be expanded to include more than two sets.
$$|A \cup B \cup C|=|A|+|B|+|C|-|A \cap B|-|A \cap C|-|B \cap C| + |A \cap B \cap C|$$

Given
 - $|A|=12$
 - $|B|=5$
 - $|C|=8$
 - $|A \cap B|=2$
 - $|A \cap C|=6$
 - $|B \cap C|=3$
 - $|A \cap B \cap C|=1$
Then
    $$|A \cup B \cup C|=12+5+8-2-6-3+1=15$$


