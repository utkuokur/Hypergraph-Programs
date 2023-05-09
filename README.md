This package contains Sagemath code to calculate:

1- the list of Veblen hypergraphs on d edges and less than or equal to n vertices, of rank k.

2- the associated coefficient of a Veblen hypergraph

3- the characteristic polynomial of a simple hypergraph

The main file contains the three functions just mentioned. In addition, there are three example files, to demonstrate the usage of the functions in the main file. 

These and related concepts are described in the paper:

Joshua Cooper and Gregory Clark:
Journal of Combinatorial Theory, Series B,
Volume 149,
2021,
Pages 1-15,
ISSN 0095-8956,
https://doi.org/10.1016/j.jctb.2021.01.002.
(https://www.sciencedirect.com/science/article/pii/S0095895621000022)

Abstract: We generalize the Harary-Sachs theorem to k-uniform hypergraphs: the codegree-d coefficient of the characteristic polynomial of a uniform hypergraph H can be expressed as a weighted sum of subgraph counts over certain multi-hypergraphs with d edges. We include a detailed description of the aforementioned multi-hypergraphs and a formula for their corresponding weights.
Keywords: Characteristic polynomial; Hypergraph; Subgraph statistics; Coefficient

Definitions: 

A Veblen hypergraph of rank k is a hypergraph of rank k such that the degree of each vertex is divisible by k. Given k, n and d, we can calculate the list of all possibly disconnected Veblen hypergraphs on d edges and less than or equal to n vertices, of rank k, using the first program.

The associated coefficient of a Veblen hypergraph H is the rational number obtained by summing, over all rootings R of H, the ratio of the number of Eulerian circuits of D_R, the digraph obtained from R, over the product of the in-degrees of the vertices of D_R. 

The characteristic polynomial of a simple hypergraph H is polynomial in the variable x obtained by taking the resultant of I-xA, where A is the adjacency hypermatrix of H.

Examples:

1- In Example 1, we calculate the list of all Veblen hypergraphs on 6 edges and less than or equal to 5 vertices, of rank 3. 

2- In Example 2, we calculate the associated coefficient of the Veblen hypergraph with edge set { [0,1,2], [0,1,2], [0,1,2], [1,2,3], [1,2,3], [1,2,3] }. 

3- In Example 3, we calculate the characteristic polynomial of the hypergraph with edge set { [0,1,2], [0,1,3], [0,2,3], [1,2,3] } (the complete hypergraph of rank 3 on 4 vertices). There is an option to estimate the remaining time. 

The code is written in Sagemath 9.7, which is available in WSL2 (Windows Subsystem for Linux) in Windows 11. The third program requires Macaulay 2, a software system for algebraic geometry.

Download Sagemath: https://www.sagemath.org/

Download WSL2: https://learn.microsoft.com/en-us/windows/wsl/install

Download Macaulay 2: http://www2.macaulay2.com/Macaulay2/Downloads/

