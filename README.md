# Shortest-Path-Graph-Dijkstra-Algorithm
C++ code for using dijkstra algorithm to find the shortest path between any two given graph nodes.

ALGORITHM:

1.Set all vertices distances to infinity except for the source vertex and set the source distance to 0.

2.Push the source vertex in a minimum priority queue in the form (distance , vertex).

3.Pop the vertex with the minimum distance from the priority queue.

4.Update the distances of the connected vertices to the popped vertex in case of "current vertex distance + edge weight" being less than the next vertex distance.

5.Push the vertex with the new distance to the priority queue.

6.If the popped vertex has been visited before skip it.

7.Loop algorithm again until the priority queue is empty.

8.End
