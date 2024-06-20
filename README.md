Concept- Adjacency List - Array of ArrayLists. 
Why Adjacency list- Less time to access neighbours due to its storing nature 
ArrayList has the information of Edges. What does an edge mean here? Source to destination
So we shall first create an Edge Class and use it whenever we need to create a New Edge
Before storage any edge we first have to create an empty ArrayList
How do we Store an edge in this? we first access the array index, then create a new edge. If we have multple edges for Vertex, we continue to create edges, obviously. 
How do we access Neighbours for a Vertex? We create an edge type variable and store the edges, and then we access destination from this variable continously(for loop).
Concepts learned- Class-Object creation, User defined data types, SOLID principles. 
Each edge can also have a distance, in that case we create an edge with details, source, destination and weight. 
