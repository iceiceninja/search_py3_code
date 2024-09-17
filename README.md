# Example commands  
## For autograder
```
python autograder.py
python autograder.py -q q2 
```
## For Simulation
### DFS
```
python pacman.py -l tinyMaze -p SearchAgent
python pacman.py -l mediumMaze -p SearchAgent
python pacman.py -l bigMaze -z .5 -p SearchAgent
```
### BFS
```
python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
python eightpuzzle . py
```
### UCS
```
python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
python pacman.py -l mediumDottedMaze -p StayEastSearchAgent
python pacman.py -l mediumScaryMaze -p StayWestSearchAgent
```
### A*
```
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar , heuristic = manhattanHeuristic
```
### Find all corners
```
python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs ,prob=CornersProblem
python pacman.py -l mediumCorners -p SearchAgent -a fn=bfs ,prob = CornersProblem
```
### Find all corners: Heuristic
```
python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5
```
