# Python Algorithms & API Architecture 🐍

## 📌 Overview
This repository contains Python scripts focused on REST API development, constraint satisfaction, probabilistic reasoning, and search algorithms. These projects demonstrate my ability to build local servers, process JSON payloads, model risk, and build logical workflows to navigate complex data matrices.

## 🚀 Repository Files & Features

### 1. Flask REST API & JSON Processing (`assignment_4.py`)
* **Concept:** Built a local web server using the Flask framework and exposed endpoints to the public internet using ngrok.
* **Relevance:** Demonstrates proficiency with REST API architecture and JSON data structuring. Includes a `/calculate` endpoint that parses incoming JSON data to compute values, and a `/bfs` endpoint that accepts a JSON-formatted graph to execute a search algorithm.


### 2. Machine Learning Prediction API & Mobile Integration (`Assignment_5.ipynb`)
* **Concept:** Trained a logistic regression model (scikit-learn) to predict whether a student will pass based on study hours and class attendance, then served it through a Flask REST API exposed to the internet with ngrok.
* **Relevance:** Demonstrates end-to-end integration of a machine learning model, REST API, and client application. Includes a `/predict` endpoint that validates incoming JSON, returns a Pass/Fail result with the probability of passing, and is consumed by a mobile app built in MIT App Inventor.
* I will have a screenshot of how things look on the MIT App Inventor side!

### 3. Constraint Solvers & Bayesian Networks (`assignment_3.py`)
* **Concept:** Implemented a Z3 Theorem Prover to solve complex grid-based logic puzzles (Sudoku) and built a Discrete Bayesian Network using `pgmpy` to calculate conditional probabilities.
* **Relevance:** Showcases advanced data validation workflows and risk modeling. The Z3 solver strictly enforces rules to identify valid data states (mirroring enterprise anomaly resolution), while the Bayesian Network infers the probability of outcomes based on conditional evidence.

### 4. A* Search Algorithm (`cs_444_assignment_2p2 (1).py`)
* **Concept:** Developed an A* Search algorithm to navigate a 2D grid, calculating optimal paths while avoiding defined obstacles.
* **Relevance:** Uses a priority queue and a Manhattan distance heuristic to efficiently calculate the cost of data movement through a constrained system.

### 5. Breadth-First Search (BFS) Maze Solver (`cs_444_assignment_2 (1).py`)
* **Concept:** Developed a Breadth-First Search algorithm using a double-ended queue (`deque`) to explore and map open paths in a 2D matrix.
* **Relevance:** Highlights algorithmic problem solving and the ability to track and validate explored data points within a defined matrix boundary.
