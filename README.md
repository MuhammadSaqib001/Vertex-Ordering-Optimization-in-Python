# Vertex-Ordering-Optimization-in-Python
Simplified form of Bayes Net Learning , given a set of vertices the goal is to  determine a vertex ordering with the minimum cost . Finding optimal graph structures is an important optimization problem that has applications in several areas including machine learning itself, such as Bayesian Network Learning. The problem of Bayes-Net Learning can be simplified as the vertex ordering problem. Given a set of vertices the goal is to


## Objective :-
Determine a vertex ordering with the minimum cost. Consider the network below, which can be
represented by the ordering (B, C, A):

Consider the following optimization problem. We are given vertices V1, · · · , Vn and possible parent
sets for each vertex. Each parent set has an associated cost. Let O be an ordering (a permutation) of the
vertices. We say that a parent set of a vertex Vi is consistent with an ordering O if all of the parents
come before the vertex in the ordering. Thus, (C, B, A) would be an inconsistent ordering for the above
network. Let mcc(Vi,O) be the minimum cost of the parent sets of vertex Vi that are consistent with
ordering O. The task is to find an ordering of vertices O that minimizes the total cost of the network:
mcc(V1, O) + · · · + mcc(Vn, O):

As an example, consider that you are not given the network above. Instead you are given the vertices
A,B, and C and their possible parent sets along with their cost as follows and given the task of finding
the minimium cost network.

## Sample Output
