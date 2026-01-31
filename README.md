# Maze Game (code available upon request)

An interactive maze generation and pathfinding visualization tool built in Java, featuring procedural maze creation with Kruskal's algorithm and real-time algorithm visualization.

## Game Overview

This maze game combines algorithmic maze generation with interactive solving mechanics. Players can manually navigate through procedurally generated mazes or watch automated pathfinding algorithms solve them in real-time with visual feedback.

## Features

### Maze Generation
- **Procedural Generation**: Creates unique mazes using Kruskal's minimum spanning tree algorithm
- **Randomized Layouts**: Every maze is different, ensuring endless replayability
- **Configurable Complexity**: Adjustable maze dimensions and difficulty

### Gameplay Modes
- **Manual Mode**: Navigate using arrow keys to find the exit yourself
- **Automated Solving**: Watch BFS or DFS algorithms solve the maze step-by-step
- **Real-Time Visualization**: See algorithms work with color-coded visual feedback

### Visual Feedback System
- 🟦 **Turquoise**: Current player position
- 🔵 **Light Blue**: Previously visited cells
- 🔷 **Dark Blue**: Solution path (when using automated solvers)
- ⬛ **Black**: Walls and boundaries

### Technical Implementation
- **Graph Algorithms**: Kruskal's algorithm for maze generation
- **Pathfinding**: BFS (Breadth-First Search) and DFS (Depth-First Search)
- **Data Structures**: Union-Find (Disjoint Set), Deques, Iterators, Generics
- **Clean Architecture**: Modular, maintainable codebase with separation of concerns

## Controls

### Movement
| Key | Action |
|-----|--------|
| ↑ (UP) | Move player up |
| ↓ (DOWN) | Move player down |
| ← (LEFT) | Move player left |
| → (RIGHT) | Move player right |

### Special Commands
| Key | Action |
|-----|--------|
| **N** | Generate new maze |
| **B** | Solve using BFS (Breadth-First Search) |
| **D** | Solve using DFS (Depth-First Search) |

## Game Rules

- **Objective**: Navigate from the top-left corner to the bottom-right exit
- **Wall Collision**: Players cannot move through walls
- **Post-Solution**: After automated solving, generate a new maze to continue playing
- **No Backtracking Penalty**: Freely explore without consequences

## Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/388275f5-1ccb-4182-bb99-ce728794e4ed" alt="Manual Traversal" width="800"/>
  <br>
  <em>Manual exploration showing visited path in light blue</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/edf3fc56-c620-4fa0-a739-362604457be6" alt="Automated Solving" width="800"/>
  <br>
  <em>BFS/DFS automated solving with highlighted solution path</em>
</p>

## Technologies

- **Language**: Java
- **IDE**: Eclipse
- **Graphics Library**: impworld
- **Algorithms**: 
  - Kruskal's Algorithm (Maze Generation)
  - Breadth-First Search (Shortest Path)
  - Depth-First Search (Alternative Pathfinding)
- **Data Structures**: Union-Find, Deque, Generic Collections, Iterators

## Architecture Highlights

- **Graph-Based Design**: Mazes represented as weighted graphs
- **Union-Find Structure**: Efficient cycle detection for Kruskal's algorithm
- **Iterator Pattern**: Clean traversal of maze structures
- **Generic Programming**: Type-safe, reusable components
- **Event-Driven Input**: Responsive keyboard controls

## Algorithm Comparison

### BFS (Breadth-First Search)
- ✅ Guarantees shortest path
- ✅ Explores level-by-level
- ⚠️ Higher memory usage

### DFS (Depth-First Search)
- ✅ Memory efficient
- ✅ Faster for deep mazes
- ⚠️ May not find shortest path


## Development

Co-developed project emphasizing:
- Advanced algorithmic problem-solving
- Data structure implementation and optimization
- Visual algorithm demonstration
- Clean code architecture and design patterns

## Learning Outcomes

This project demonstrates proficiency in:
- Graph algorithms and maze generation
- Pathfinding algorithm implementation
- Real-time visualization techniques
- Object-oriented design principles
- Data structure selection and optimization
