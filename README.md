[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


## Proof
To be isomorphic the mapping of one graphs nodes to the others nodes must be one-to-one and unto. So for graph A to be isomorphic to graph B it's mappings must be one-to-one and onto. To be one-to-one, A's nodes map to distinct nodes of B, meaning that no two nodes of A map to the same node in B. And to be onto, every node in B must have a map to it from A. <br/>
If A had one more node than B then either a node in A would not have a map to a node in B or two nodes in A would map to the same node in B, which is not one-to-one. If B had one more node than A, then every node in A could map to a node in B (one-to-one) but there would be a node in B that would not have a mapping to it from A, meaning it is not onto. To be isomorphic the mappings have to both one-to-one and onto, if either node had more or less nodes then the other then they can not be isomorphic.   
