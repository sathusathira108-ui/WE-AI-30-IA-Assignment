# Pac-Man Search Algorithms

## Project Overview
This group assignment explores artificial intelligence search algorithms using the Pac-Man environment. We implement DFS, BFS, UCS and A* search, along with heuristics for visiting all four corners and collecting all food.

## Team Responsibilities
- Member 1: Q1 DFS and Q2 BFS
- Member 2: Q3 UCS and Q4 A*
- Member 3: Q5 CornersProblem and Q6 Corners Heuristic
- Member 4: Q7 Food Heuristic and final integration

## How to Run
Open a terminal in the folder containing pacman.py.

Run DFS:
python pacman.py -l mediumMaze -p SearchAgent -a fn=dfs

Run BFS:
python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs

## Testing
Run the relevant autograder tests:
python autograder.py -q q1
python autograder.py -q q2
python autograder.py -q q3
python autograder.py -q q4
python autograder.py -q q5
python autograder.py -q q6
python autograder.py -q q7

## Collaboration
Each member works on an individual Git branch and submits their changes through a Pull Request. All implementations are reviewed and tested before integration into main.

## AI Usage
Any AI assistance used during development is documented in the group report, including the tools and exact prompts used.
