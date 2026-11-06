# 🗺️ Real-Time City Navigation System Using C++

## 📌 Project Overview

The Real-Time City Navigation System is a C++-based application designed to find the shortest and fastest routes between different locations in a city.

The city road network is represented using a graph data structure, where locations are represented as vertices and roads are represented as edges. Each road has a weight based on distance and traffic conditions.

When traffic conditions change, the system dynamically updates road weights and calculates the best possible route.

This project also compares classical and optimized shortest-path algorithms based on execution time and memory usage.
# 🗺️ Real-Time City Navigation System Using C++

## 📌 Project Overview

The Real-Time City Navigation System is a C++-based application designed to find the shortest and fastest routes between different locations in a city.

The city road network is represented using a graph data structure, where locations are represented as vertices and roads are represented as edges. Each road has a weight based on distance and traffic conditions.

When traffic conditions change, the system dynamically updates road weights and calculates the best possible route.

This project also compares classical and optimized shortest-path algorithms based on execution time and memory usage.
# 🗺️ Real-Time City Navigation System Using C++

## 📌 Project Overview

The Real-Time City Navigation System is a C++-based application designed to find the shortest and fastest routes between different locations in a city.

The city road network is represented using a graph data structure, where locations are represented as vertices and roads are represented as edges. Each road has a weight based on distance and traffic conditions.

When traffic conditions change, the system dynamically updates road weights and calculates the best possible route.

This project also compares classical and optimized shortest-path algorithms based on execution time and memory usage.

## 🎯 Objectives

- To represent a city road network using graph data structures.
- To find the shortest path between two locations.
- To update road weights based on changing traffic conditions.
- To identify alternative routes during heavy traffic.
- To implement and compare classical and optimized algorithms.
- To analyze algorithm performance in terms of execution time and memory usage.

## 🛠️ Technologies Used

- **Programming Language:** C++
- **IDE:** Visual Studio Code / Code::Blocks
- **Compiler:** GCC / MinGW
- **Data Structures:** Graphs, Vectors, Priority Queues, Adjacency Lists
- **Algorithms:** Dijkstra's Algorithm, A* Algorithm, Floyd-Warshall Algorithm
- **Libraries:** C++ Standard Template Library (STL)

## ⚙️ Features

1. **Location Management:** Add and manage different city locations.
2. **Road Network Representation:** Connect locations using roads.
3. **Shortest Route Calculation:** Find the shortest route between source and destination.
4. **Dynamic Traffic Updates:** Modify road weights according to traffic conditions.
5. **Alternative Routes:** Find alternative routes when traffic is high.
6. **Algorithm Comparison:** Compare classical and optimized algorithms.
7. **Performance Analysis:** Measure execution time and memory consumption.
8. **Route Information:** Display total distance and estimated travel time.

## 🧩 Project Modules

### 1. Location Management
- Add city locations.
- Assign unique IDs to locations.

### 2. Road Network Management
- Connect different locations.
- Store road distances and travel times.

### 3. Traffic Management
- Update traffic conditions.
- Dynamically modify road weights.

### 4. Shortest Path Calculation
- Implement Dijkstra's algorithm.
- Implement A* algorithm.
- Calculate optimal routes.

### 5. Performance Analysis
- Measure execution time.
- Compare memory consumption.
- Display algorithm performance.

## 🧠 Algorithms Implemented

| Algorithm | Description |
|---|---|
| Dijkstra's Algorithm | Finds the shortest path using non-negative edge weights. |
| Optimized Dijkstra | Uses a priority queue for efficient pathfinding. |
| A* Algorithm | Uses a heuristic to guide the search toward the destination. |
| Floyd-Warshall | Calculates shortest paths between all pairs of locations. |

## 📂 Project Structure

```text
CityNavigationSystem/
│
├── main.cpp
├── graph.h
├── graph.cpp
├── dijkstra.h
├── astar.h
├── traffic.h
├── performance.h
├── locations.txt
├── roads.txt
└── README.md
```

## 💻 How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone <your-repository-link>
```

**Step 2:** Open the project folder.

```bash
cd CityNavigationSystem
```

**Step 3:** Compile the program.

```bash
g++ main.cpp graph.cpp -o navigation
```

**Step 4:** Run the program.

```bash
./navigation
```

For Windows:

```bash
navigation.exe
```

*Note: Include the other `.cpp` files in the compilation command as they are added to the project.*

## 📊 Performance Comparison

The system compares algorithms using the following parameters:

- Execution Time
- Memory Usage
- Route Calculation Efficiency
- Scalability with Increasing Nodes and Edges

## 🔮 Future Enhancements

- Integrate real-time traffic APIs.
- Develop a graphical user interface.
- Display city maps and routes visually.
- Add GPS-based location tracking.
- Provide voice-based navigation.
- Include road closure and accident information.

## 🎓 Applications

- City navigation systems.
- Smart transportation management.
- Traffic monitoring systems.
- Route optimization applications.
- Intelligent transportation networks.

## 👩‍💻 Project Information

**Project Name:** Real-Time City Navigation System Using C++

**Domain:** Data Structures and Algorithms

**Programming Language:** C++
## 📜 Conclusion

The Real-Time City Navigation System demonstrates the practical application of graph data structures and shortest-path algorithms in solving real-world transportation problems. By dynamically updating traffic weights and comparing different algorithms, the system aims to provide efficient route calculations while analyzing their time and memory performance.

## 🎯 Objectives

- To represent a city road network using graph data structures.
- To find the shortest path between two locations.
- To update road weights based on changing traffic conditions.
- To identify alternative routes during heavy traffic.
- To implement and compare classical and optimized algorithms.
- To analyze algorithm performance in terms of execution time and memory usage.

## 🛠️ Technologies Used

- **Programming Language:** C++
- **IDE:** Visual Studio Code / Code::Blocks
- **Compiler:** GCC / MinGW
- **Data Structures:** Graphs, Vectors, Priority Queues, Adjacency Lists
- **Algorithms:** Dijkstra's Algorithm, A* Algorithm, Floyd-Warshall Algorithm
- **Libraries:** C++ Standard Template Library (STL)

## ⚙️ Features

1. **Location Management:** Add and manage different city locations.
2. **Road Network Representation:** Connect locations using roads.
3. **Shortest Route Calculation:** Find the shortest route between source and destination.
4. **Dynamic Traffic Updates:** Modify road weights according to traffic conditions.
5. **Alternative Routes:** Find alternative routes when traffic is high.
6. **Algorithm Comparison:** Compare classical and optimized algorithms.
7. **Performance Analysis:** Measure execution time and memory consumption.
8. **Route Information:** Display total distance and estimated travel time.

## 🧩 Project Modules

### 1. Location Management
- Add city locations.
- Assign unique IDs to locations.

### 2. Road Network Management
- Connect different locations.
- Store road distances and travel times.

### 3. Traffic Management
- Update traffic conditions.
- Dynamically modify road weights.

### 4. Shortest Path Calculation
- Implement Dijkstra's algorithm.
- Implement A* algorithm.
- Calculate optimal routes.

### 5. Performance Analysis
- Measure execution time.
- Compare memory consumption.
- Display algorithm performance.

## 🧠 Algorithms Implemented

| Algorithm | Description |
|---|---|
| Dijkstra's Algorithm | Finds the shortest path using non-negative edge weights. |
| Optimized Dijkstra | Uses a priority queue for efficient pathfinding. |
| A* Algorithm | Uses a heuristic to guide the search toward the destination. |
| Floyd-Warshall | Calculates shortest paths between all pairs of locations. |

## 📂 Project Structure

```text
CityNavigationSystem/
│
├── main.cpp
├── graph.h
├── graph.cpp
├── dijkstra.h
├── astar.h
├── traffic.h
├── performance.h
├── locations.txt
├── roads.txt
└── README.md
```

## 💻 How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone <your-repository-link>
```

**Step 2:** Open the project folder.

```bash
cd CityNavigationSystem
```

**Step 3:** Compile the program.

```bash
g++ main.cpp graph.cpp -o navigation
```

**Step 4:** Run the program.

```bash
./navigation
```

For Windows:

```bash
navigation.exe
```

*Note: Include the other `.cpp` files in the compilation command as they are added to the project.*

## 📊 Performance Comparison

The system compares algorithms using the following parameters:

- Execution Time
- Memory Usage
- Route Calculation Efficiency
- Scalability with Increasing Nodes and Edges

## 🔮 Future Enhancements

- Integrate real-time traffic APIs.
- Develop a graphical user interface.
- Display city maps and routes visually.
- Add GPS-based location tracking.
- Provide voice-based navigation.
- Include road closure and accident information.

## 🎓 Applications

- City navigation systems.
- Smart transportation management.
- Traffic monitoring systems.
- Route optimization applications.
- Intelligent transportation networks.

## 👩‍💻 Project Information

**Project Name:** Real-Time City Navigation System Using C++

**Domain:** Data Structures and Algorithms

**Programming Language:** C++
## 📜 Conclusion

The Real-Time City Navigation System demonstrates the practical application of graph data structures and shortest-path algorithms in solving real-world transportation problems. By dynamically updating traffic weights and comparing different algorithms, the system aims to provide efficient route calculations while analyzing their time and memory performance.

## 🎯 Objectives

- To represent a city road network using graph data structures.
- To find the shortest path between two locations.
- To update road weights based on changing traffic conditions.
- To identify alternative routes during heavy traffic.
- To implement and compare classical and optimized algorithms.
- To analyze algorithm performance in terms of execution time and memory usage.

## 🛠️ Technologies Used

- **Programming Language:** C++
- **IDE:** Visual Studio Code / Code::Blocks
- **Compiler:** GCC / MinGW
- **Data Structures:** Graphs, Vectors, Priority Queues, Adjacency Lists
- **Algorithms:** Dijkstra's Algorithm, A* Algorithm, Floyd-Warshall Algorithm
- **Libraries:** C++ Standard Template Library (STL)

## ⚙️ Features

1. **Location Management:** Add and manage different city locations.
2. **Road Network Representation:** Connect locations using roads.
3. **Shortest Route Calculation:** Find the shortest route between source and destination.
4. **Dynamic Traffic Updates:** Modify road weights according to traffic conditions.
5. **Alternative Routes:** Find alternative routes when traffic is high.
6. **Algorithm Comparison:** Compare classical and optimized algorithms.
7. **Performance Analysis:** Measure execution time and memory consumption.
8. **Route Information:** Display total distance and estimated travel time.

## 🧩 Project Modules

### 1. Location Management
- Add city locations.
- Assign unique IDs to locations.

### 2. Road Network Management
- Connect different locations.
- Store road distances and travel times.

### 3. Traffic Management
- Update traffic conditions.
- Dynamically modify road weights.

### 4. Shortest Path Calculation
- Implement Dijkstra's algorithm.
- Implement A* algorithm.
- Calculate optimal routes.

### 5. Performance Analysis
- Measure execution time.
- Compare memory consumption.
- Display algorithm performance.

## 🧠 Algorithms Implemented

| Algorithm | Description |
|---|---|
| Dijkstra's Algorithm | Finds the shortest path using non-negative edge weights. |
| Optimized Dijkstra | Uses a priority queue for efficient pathfinding. |
| A* Algorithm | Uses a heuristic to guide the search toward the destination. |
| Floyd-Warshall | Calculates shortest paths between all pairs of locations. |

## 📂 Project Structure

```text
CityNavigationSystem/
│
├── main.cpp
├── graph.h
├── graph.cpp
├── dijkstra.h
├── astar.h
├── traffic.h
├── performance.h
├── locations.txt
├── roads.txt
└── README.md
```

## 💻 How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone <your-repository-link>
```

**Step 2:** Open the project folder.

```bash
cd CityNavigationSystem
```

**Step 3:** Compile the program.

```bash
g++ main.cpp graph.cpp -o navigation
```

**Step 4:** Run the program.

```bash
./navigation
```

For Windows:

```bash
navigation.exe
```

*Note: Include the other `.cpp` files in the compilation command as they are added to the project.*

## 📊 Performance Comparison

The system compares algorithms using the following parameters:

- Execution Time
- Memory Usage
- Route Calculation Efficiency
- Scalability with Increasing Nodes and Edges

## 🔮 Future Enhancements

- Integrate real-time traffic APIs.
- Develop a graphical user interface.
- Display city maps and routes visually.
- Add GPS-based location tracking.
- Provide voice-based navigation.
- Include road closure and accident information.

## 🎓 Applications

- City navigation systems.
- Smart transportation management.
- Traffic monitoring systems.
- Route optimization applications.
- Intelligent transportation networks.

## 👩‍💻 Project Information

**Project Name:** Real-Time City Navigation System Using C++

**Domain:** Data Structures and Algorithms

**Programming Language:** C++
## 📜 Conclusion

The Real-Time City Navigation System demonstrates the practical application of graph data structures and shortest-path algorithms in solving real-world transportation problems. By dynamically updating traffic weights and comparing different algorithms, the system aims to provide efficient route calculations while analyzing their time and memory performance.
