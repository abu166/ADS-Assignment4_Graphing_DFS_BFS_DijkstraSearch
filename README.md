# ADS-Assignment4_Graphing_DFS_BFS_DijkstraSearch

Graph Search Algorithms in Java

This project demonstrates the implementation of Breadth-First Search (BFS) and Dijkstra's algorithm on an edge-weighted graph using Java. The focus is on using vertices rather than edges to represent the graph structure.

Project Structure

The project consists of several Java classes, each serving a specific purpose in implementing and demonstrating the graph algorithms:

Vertex Class
Edge Class
WeightedGraph Class
Search Class (Abstract)
DijkstraSearch Class
BreadthFirstSearch Class
Main Class
Vertex Class
The Vertex class represents a vertex in the graph. Each vertex holds data and a map of adjacent vertices with their corresponding edge weights.

Edge Class
The Edge class represents an edge between two vertices and holds the source vertex, destination vertex, and the weight of the edge.

WeightedGraph Class
The WeightedGraph class represents the graph structure. It supports adding vertices and edges, checking for the existence of vertices and edges, and retrieving adjacency lists and edges. This class is designed to handle both directed and undirected graphs.

Search Class (Abstract)
The Search class is an abstract class that serves as a base for specific search algorithm implementations. It maintains a set of marked vertices (those that have been visited) and a map of edge-to relations (to track the path).

DijkstraSearch Class
The DijkstraSearch class extends the Search class and implements Dijkstra's algorithm. It calculates the shortest paths from a source vertex to all other vertices in the graph with non-negative edge weights. The results include the shortest distance to each vertex and the path taken.

BreadthFirstSearch Class
The BreadthFirstSearch class extends the Search class and implements the BFS algorithm. It explores the graph level by level from a source vertex, marking vertices as visited and tracking the path taken.

Main Class
The Main class contains the entry point of the program. It demonstrates the usage of the WeightedGraph, DijkstraSearch, and BreadthFirstSearch classes. It initializes the graph, runs the search algorithms, and outputs the paths and distances found.

Usage

To run the project, compile all the Java files and execute the Main class. The Main class demonstrates both BFS and Dijkstra's algorithm on example graphs with and without weights.
