# Shortest Path

# Dijkstra

## One line presentation
From one point, compute the updated distance of all not visited neighbors and restart from one of them until none are available.

## Complexity
O((|V|+|E|).log|V|)

## Limitation
Single source
No negative weigth

## Sources
* https://en.wikipedia.org/wiki/Dijkstra's_algorithm
* https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/

# Bellman-Ford

## One line presentation
Update the distance for all edges, repeat for the number of vectices minus one and finally repeat one last time to check for negative cycles.

## Complexity
O(|V|.|E|)

## Limitation
Single source

## Sources
* https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm
* https://www.programiz.com/dsa/bellman-ford-algorithm

# Floyd-Warshall

## One line presentation
Update the distance between each vectice if it's faster to pass from the current vectice and repeat for each vectice.

## Complexity
O(|V|^3)

## Limitation
No negative cycles

## Sources
* https://en.wikipedia.org/wiki/Floyd%E2%80%93Warshall_algorithm
* https://brilliant.org/wiki/floyd-warshall-algorithm/
* https://www.geeksforgeeks.org/floyd-warshall-algorithm-dp-16/

