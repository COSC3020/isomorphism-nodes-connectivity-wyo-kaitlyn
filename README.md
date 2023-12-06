[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12528044&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Using the bijective mapping part of the definition, two graphs are isomorphic if each
element in graph $A$ can be mapped to exactly one element in graph $B$ using a function,
and vice versa.  

For each node in graph A, there exists an edge connecting it to each
other node in $A$, as that is required for a graph to be completely connected.  Therefore, 
graph $B$ would have the same number of edges as $A$, as it is also completely connected, 
and has the same number of nodes.  This means any node in graph $A$ can be mapped to a node 
in map $B$, since the edges will be the same. 
 
Every node in $A$ can be mapped to a unique node in $B$, as they have the same number of nodes
and edges.  Any permation of graph $A$ nodes can be bijectively mapped to graph $B$ nodes, as each 
element in $A$ can be mapped to exactly one in $B$.  

This fulfills the definition of isomorphic, as $A$ can be bijectively mapped to $B$.
