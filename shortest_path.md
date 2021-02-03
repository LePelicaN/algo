# Shortest Path

# Dijkstra

## One line presentation
From one point, compute the updated distance of all not visited neighbors and restart from one of them until none are available.

## Complexity
O((|V|+|E|).log|V|)

## Limitation
Non negative weigth

## Sources
* https://en.wikipedia.org/wiki/Dijkstra's_algorithm
* https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/

# Bellman-Ford

## One line presentation
Update the distance for all edges, repeat for the number of vectices minus one and finally repeat one last time to check for negative cycle.

## Complexity
O(|V|.|E|)

## Limitation


## Sources
* https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm
* https://www.programiz.com/dsa/bellman-ford-algorithm

