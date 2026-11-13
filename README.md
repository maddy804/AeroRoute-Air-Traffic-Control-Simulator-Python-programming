
# ✈️ AeroRoute – Air Traffic Control Simulator

### An Air Traffic Control Simulator Using Graph Algorithms

AeroRoute is a Python-based Air Traffic Control Simulator that models a network of Indian airports using graph algorithms. It demonstrates how algorithms can help solve routing, scheduling, connectivity, and optimization problems in air traffic management.

## 🚀 Project Overview

The project represents airports as vertices and flight corridors as weighted edges in a graph.

It uses multiple Design and Analysis of Algorithms (DAA) techniques to simulate important air traffic control operations.

## 🛠️ Technologies Used

- Python 3.14
- Tkinter
- NumPy
- Pandas
- Matplotlib

## ✨ Key Features

- Airport network visualization
- Shortest flight route calculation
- Alternative route calculation
- Minimum spanning tree generation
- Airport connectivity analysis
- Flight scheduling simulation
- Emergency flight queue demonstration
- Cargo optimization
- Travelling Salesman Problem implementation
- Graph colouring and subset sum demonstrations

## 🧠 Algorithms Implemented

### 1. Graph Algorithms
- Dijkstra's Algorithm
- Bellman-Ford Algorithm
- Floyd-Warshall Algorithm
- Prim's Algorithm
- Kruskal's Algorithm
- Warshall's Transitive Closure

### 2. Optimization Algorithms
- 0/1 Knapsack
- Branch and Bound
- Job Sequencing
- Travelling Salesman Problem
- Held-Karp Dynamic Programming

### 3. Other Algorithms
- Binary Heap
- Topological Sorting
- Backtracking
- Graph Colouring
- Subset Sum
- KMP String Matching
- Rabin-Karp String Matching
- Huffman Coding

## 📊 Project Dataset

The simulator uses a synthetic airport network containing:

- 22 Indian airports
- 83 flight corridors
- Weighted graph representation

The airport and corridor data are synthetic and are used for academic simulation.

## 📈 Sample Results

| Feature | Result |
|---|---|
| Distance-based route | 2,511 km |
| Time-based route | 214 minutes |
| Minimum spanning tree | 21 edges |
| Airport connectivity | 16 unreachable pairs in a closure scenario |
| Automated tests | 41 |
| Mutation testing | 19/20 injected faults detected |

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/AeroRoute-Air-Traffic-Control-Simulator.git
```

Move into the project directory:

```bash
cd AeroRoute-Air-Traffic-Control-Simulator
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

Run the main Python file:

```bash
python src/main.py
```

Use the actual entry-point filename and path from your source code.

## 🧪 Testing

Run the automated tests:

```bash
python -m unittest discover -s tests
```

## 🎯 Project Objectives

- Apply DAA concepts to a practical simulation.
- Understand graph-based airport networks.
- Compare different shortest-path algorithms.
- Demonstrate optimization and scheduling techniques.
- Analyze algorithm performance.

## ⚠️ Limitations

- Uses synthetic airport and flight corridor data.
- Does not connect to live air traffic systems.
- Large computations may affect GUI responsiveness.
- It is an academic simulator, not a real-world air traffic control system.

## 🔮 Future Scope

- Integration of real-time flight data.
- A* search algorithm.
- Improved route optimization.
- Better GUI responsiveness.
- Advanced traffic prediction.

## 👨‍💻 Author

**Madhvendra Singh**

UID: 26MCI10041

MCA – Artificial Intelligence and Machine Learning

Chandigarh University

## 📚 Academic Information

Subject: Python programming

Subject Code: 26CAH-606

Project Guide: Prof. Deepali Saini

---

⭐ If you find this project interesting, consider giving the repository a star!

