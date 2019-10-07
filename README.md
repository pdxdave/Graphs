# Graphs
Graphs Notes

### What is a graph?
A graph is a collection of data represented by nodes and connections between nodes. 
* Trees can be considered a type of graph

#### Components required to make up a graph
* Nodes or vertices - represent objects in a data set (e.g., animals, cities, webpages, etc)
* Edges - they are connections between vertices, and they can be bidirectional.  An edge might be somethng like an animal group then all the subgroups below it. Not all edges are created equal so there might be a cost to traverse them.
* Weight - the cost to travel across an edge

#### What are graphs useful for?
* A city transit map.  For instance, a subway might use nodes to represent the stops.  The different trains we can think of as the edges. The weight might be how long it takes to get from one stop to another.
* Github could uses graphs to represent the push/pull history of a repo.

#### Specific kinds of graphs
* Directed graph - can only move along edges in one direction
* Undirected graph - allows movement in both directions along edges.
* Cyclic graph - edges allow you to visit at least one verticle. 
* Acyclic graphy - vertices can only be visited once

### Breadth first search
* It's a way to search the graph.    
* Explors all possible paths to find one with the smallest possible weight
* Traversing across before traversing down
* Never revisits nodes
* Useful for route or path finding

#### Breadth first algorithm
* A starting vertex.  In a tree it would be the root node.  In an undirected graph we'd have a labled vertex to start at.
* Uses a que: first in, first out.  
