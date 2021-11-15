# topo-aspl
This repo creates a graph with (possible) smallest average shortest path length (ASPL).

## Prerequisite
* networkx

## Run
```shell
$ python3 topo-aspl.py <nnodes> <degree> [-i <iteration>] #default iteration is 1,000
```

## Source Files
### [topo-aspl.py](topo-aspl.py)
* This is the main program.

## Output
The generated topology (edge file) and output information are stored in the *output/* folder. 
