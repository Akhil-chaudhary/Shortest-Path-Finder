# Shortest-Path-Finder
Express based web app to visualize different algorithms and there working.
The algorithm proceeds as follows:

While QQ is not empty, pop the node vv, that is not already in SS, from QQ with the smallest distdist (vv). In the first run, source node ss will be chosen because distdist(ss) was initialized to 0. In the next run, the next node with the smallest distdist value is chosen.
Add node vv to SS, to indicate that vv has been visited
Update distdist values of adjacent nodes of the current node vv as follows: for each new adjacent node uu,
if distdist (vv) + weight(u,v)weight(u,v) < distdist (uu), there is a new minimal distance found for uu, so update distdist (uu) to the new minimal distance value;
otherwise, no updates are made to distdist (uu).
The algorithm has visited all nodes in the graph and found the smallest distance to each node. distdist now contains the shortest path tree from source ss.
