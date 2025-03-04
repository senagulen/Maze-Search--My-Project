### **Author**
Developed by **senagulen** 
# Maze Search Project

## Overview
This project is a **maze navigation system** that uses **stack-based depth-first search (DFS)** to explore rooms and identify escape routes. It consists of two primary components:  
1. **Maze Runner (`maze_runner.py`)** - Creates test mazes with interconnected rooms and runs the search algorithm.  
2. **Maze Search (`maze_search.py`)** - Implements a **Stack** data structure and a search algorithm to traverse the maze and find escape rooms.

## Features
- Implements a **Stack** data structure to facilitate depth-first search.
- Defines a **Room** class to represent rooms in a maze, supporting up to four linked rooms.
- Allows users to create **simple or complex mazes** for testing.
- Identifies rooms that contain **an escape route**.

## How It Works
1. **Maze Creation**  
   - `maze_runner.py` defines a **complex** and a **simple** test maze.
   - Each room is connected to other rooms, forming a navigable structure.

2. **Maze Traversal & Escape Search**  
   - `find_escapes(start_room)` in `maze_search.py` uses a **stack** to explore all rooms.
   - It marks visited rooms and collects escape rooms (`is_escape=True`).
   - The traversal order and escape rooms are displayed in the output.

## How to Run
1. Clone the repository:
   ```bash
   git clone git@github.com:senagulen/Maze-Search--My-Project.git
