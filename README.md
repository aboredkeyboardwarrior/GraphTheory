# GraphTheory
A summary of all graph theory concepts

# Basics
Node/Vertex = Data point containing name, ID, attributes etc.
Edge/Relationship = Connections between nodes

# Connected Components
Finds all clusters of nodes that are connected together by edges
Assumes not all nodes are connected together

Look into:
nx.connected_components

# Dijkstra's Algorithm
Finds shortest path from node A to node B based on distance (total weight of all connecting edges)
Assumes all nodes are connected

# Minimum Spanning Tree
Finds shortest path connecting all nodes in a single line

# Pagerank

# Centrality
How connected a node is to every other node
Many metrics to use including closeness, betweeness, eigenverctor

# Link Prediction
Algorithms to propose future neighbours
- Jaccard Coefficient
  - considering number of mutual neighbours e.g. Facebook mutual friends

- Preferential Connections
  - those with many connections will match with others with many connections
