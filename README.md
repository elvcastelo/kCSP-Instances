# About

This repository contains the generated instances generated in [1] for the k-Colour Shortest Path problem. Overall, there are 60 new instances, separated into 3 groups according to their structure.

# How to read

Let $D = (V, A, w, c)$ be a weighted edge-coloured directed graph with set of vertices $V$, set of arcs $A$, cost function $w: A \rightarrow \mathbb{R}_{+}$, and an edge-colouring function $c: A \rightarrow \mathbb{N}$. We also define $c(D) \coloneqq \{c(uv) \mid uv \in A\}$ as the set of all distinct colours in $D$, which includes all colours assigned to the arcs in $A$.

Each file consists of $m + 1$ lines, where $m$ represents the number of arcs in the graph. All the information is separated by spaces. The first line contains the number of vertices $n$, number of arcs $m$, source $s$, destination $t$, natural $k$, and the number of distinct colours $|c(G)|$, respectively. 

The remaining $m$ lines provide information about each arc, including the tail $u$, head $v$, weight $w(uv)$, and colour $c(uv)$, in this order.

## References

[1] de Andrade, R. C., Castelo, E. E. S., & Saraiva, R. D. (2024). Valid inequalities for the k-Color Shortest Path Problem. European Journal of Operational Research, 315(2), 499-510.