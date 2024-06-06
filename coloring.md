# Coloring 

**Coloring is the process of assigning a label, refered to as a color, to elements of a graph.**

### Definitions:
1. **Vertex Coloring**: Assigning a color to each vertex in a graph
2. **Proper**: A vertex is proper if every adjacent vertex are colored differently than the center vertex
3. **CHromatic Number**: The smallest number of unqiue colors that makes every vertex in a graph proper

> [!Note]
> The chromatic number of a graph $G$ is written as $\chi (G)$

## The Four Color Theorem
**The Four Color Thereom states that the chromatic number of a planar graph is always less than or equal to 4.**

### Proof of the Four Color Theorem

The book doesn't go deep into the proof due to its complexity. I was planning on demonstrating the proof (which can be found [here](https://github.com/coq-community/fourcolor)) using some proof assitance software, but it proved to be too unwieldy to actually present. The book says that the proof relies on reducing the possible configurations of graphs to a set of 633, and although this is true the computer actually has to check over a billion situations to properly verify the proof not just the 633.

#### Example
![image](https://github.com/CalebNeal07/csc208/assets/105329924/9ba909e1-bc37-45d9-a320-1cef36a745fb)


[Next](https://github.com/bananajoeo7/csc208/blob/main/presentations/Chapter_4/Chapter_4.4_Presentation.md)
## Sources
 - https://en.wikipedia.org/wiki/Graph_coloring
 - https://github.com/coq-community/fourcolor
 - https://inria.hal.science/hal-04034866/document
