# Network analysis of trophic dynamics
Social network analysis of short-tailed field rats in southern Florida ecosystems

This project consists of demonstrating a trophic dynamics network and aims to investigate interactions between these areas. 
The data were collected from an existing database, available at the following link: https://networkrepository.com/eco-stmarks.php. \
No data preprocessing was necessary, as the number of vertices and nodes was sufficient and there were no irrelevant extra data in the tables. Each vertex symbolizes an ecological area within southern Florida, with edges representing ecological connections to other areas, and the weight indicating the distance between these areas.

## Graph Analysis

The graph is simple, undirected, unweighted, and connected, consisting of 54 vertices and 353 edges. There are 3 loops at vertices 7, 13, and 14, indicating that the food chain in those regions can interact with itself. The diameter of the graph, which is the longest path between the furthest vertices, is 3, demonstrating that all areas are easily accessible to each other. Both node and edge connectivity are 4, meaning that removing 4 vertices or 4 edges would be necessary to disconnect the ecosystems, effectively disrupting all food chain interactions. The graph is connected but cyclic, not characterized as a tree or a forest. The vertex with the highest degree centrality is vertex 54, considered the most important node due to its connections with 48 other nodes/areas. This vertex also has the highest closeness and betweenness centrality, crucial for linking different ecosystem regions. With a global clustering coefficient of approximately 41%, the graph shows that nodes tend not to cluster together, indicating few circular interactions among animals from different regions. The edge-to-node ratio in the graph is only 25%, indicating its density. The graph's coreness is 10, the highest possible coreness for forming a graph, as there are no coreness values greater than 10. Regions of Florida can be removed from the ecosystems up to 10 times without completely affecting the graph. There are 9 vertices with eccentricity equal to the diameter, meaning it is possible to traverse the entire graph from these vertices, connecting all regions and trophic chains analogously.

## Gephi Analysis

- Statistics by Gephi:

  <img src="https://github.com/SynbioLuancesarca/Network-analysis-of-trophic-dynamics/assets/168687335/f1da6291-8e3d-428c-88f6-7855e6e927db" width=400 height=500>

  <img src="https://github.com/SynbioLuancesarca/Network-analysis-of-trophic-dynamics/assets/168687335/725fb875-1731-4e32-9902-da04850448f9" width=500 height=500>
