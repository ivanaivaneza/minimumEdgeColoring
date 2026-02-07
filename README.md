# minimumEdgeColoring

# Project overview

This project focuses on finding minimum number of edge colors so no two adjacent edges have the same color. This problem applies to simple graphs, but we've also included others: complete, bipartite, regular.

# Problem definition

Color the edges of Graph G(V,E) with minimum number of colors so no two adjacent edges share the same color. This number is also called chromatic index. Vizing proved that chromatic index for simple graph is either Δ or Δ+1, where Δ is maximum degree of graph. So, graph is either class I or class II, respectively. Deciding which of these two values is required is NP-hard problem.

# Optimization techniques

Every technique has multiple number of combinations:

1. VNS - Variable Neighborhood Search `vns.ipynb` `vnsExperimental.ipynb`<br> 
    Local searches <br>
        &emsp;1. First <br>
        &emsp;2. Best <br>
        &emsp;3. Tabu <br>
    Shakings <br>
        &emsp;1. Random <br>
        &emsp;2. Swap <br>
        &emsp;3. Neighbour <br>
        &emsp;4. Conflict <br>
2. GA - Genetic Algorithm `ga.ipynb`<br>  
    Selections <br>
        &emsp;1. Tournament <br>
        &emsp;2. Roulette <br>
        &emsp;3. Rank <br>
    Crossovers <br>
        &emsp;1. Single Point <br>
        &emsp;2. Two Point <br>
        &emsp;3. Uniform <br>

    Mutations <br>
        &emsp;1. Random <br>
        &emsp;2. Smart <br>
        &emsp;3. Conflict <br>

3. GA + LS - Genetic Algorithm + Local Search `gaExperimentalLOCALSEARCH.ipynb`

Exact solver - CPLEX
#

Comparing of optimization techniques and each combination in one technique can be seen in `docs` folder

# Contributors
* Ivana Ivaneža
* Marija Vučetić


