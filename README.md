# Branch-and-Bound
[Branch and Bound Technique.py]\
(Branch and Bound Technique.py)
# output
5-City TSP - Cost Matrix:
A B C D E
A INF 10 8 9 7
B 10 INF 10 5 6
C 8 10 INF 8 9
D 9 5 8 INF 6
E 7 6 9 6 INF
Optimal Tour: A -> E -> B -> D -> C -> A
Minimum Cost: 34
Path verification:
A -> E: cost = 7
E -> B: cost = 6
B -> D: cost = 5
D -> C: cost = 8
C -> A: cost = 8
