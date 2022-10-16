LAB 1
Contributors: Leonardo Rolandi (301216), Flavio Patti (301104), Giuseppe Pellegrino (303999), Davide Aiello (303296) 

We have used a Dijkstra optimized approach.
Every state is a subset of the indeces of the list of lists (problem(N)), to avoid memory overflow.
Every state has a cost, that it is the number of repetitions of the numbers of that subset of lists, divided by the total length of that subset

For N:
- 5 w=5 nodes=3
- 10 w=10 nodes=10
- 20 w=23 nodes=1,350
- 50 w=65 nodes=1,011,738