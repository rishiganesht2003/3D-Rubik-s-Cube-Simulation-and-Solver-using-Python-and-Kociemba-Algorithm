
# 3D Rubik's Cube Simulation and Solver using Python and Kociemba Algorithm

3D Rubik's Cube Simulation and Solver
This project provides a 3D simulation of the Rubik's Cube and includes a solver using the Kociemba algorithm. The simulation allows for interactive manipulation of the cube and provides visualization for solving.

Features
3D Simulation: Visualize and manipulate a 3D Rubik's Cube.
Solver: Solve the Rubik's Cube using the Kociemba algorithm.
Interactive Controls: Use screen buttons for face rotations and future keyboard controls.

## Installation

Clone the Repository

    git clone https://github.com/rishiganesht2003/3D-Rubik-s-Cube-Simulation-and-Solver-using-Python-and-Kociemba-Algorithm.git

    cd 3D-Rubik-s-Cube-Simulation-and-Solver-using-Python-and-Kociemba-Algorithm

### Create a Virtual Environment
    python -m venv venv

### Activate the Virtual Environment
For Windows:

    venv\Scripts\activate
For macOS/Linux:

    source venv/bin/activate
### Install Required Packages
Create a requirements.txt file with the following dependencies:

    vpython numpy random kociemba
**Then install the packages:**

    pip install -r requirements.txt

## Code Overview
The application consists of several key components:

**cube.py**:
Cube Rendering: Handles the 3D rendering and visualization of the Rubik's Cube using vpython.
Face Rotations: Allows users to rotate cube faces through the graphical interface.
User Interface: Manages user interactions for manipulating the cube.

**main.py**:
Application Entry Point: The main script that initializes the simulation and ties all components together.
Event Handling: Manages user input and ensures the correct cube movements are displayed.

**solve_rubiccs_cube.py**
Kociemba Algorithm Integration: Implements the solving algorithm to find the optimal solution for the cube state.

**Solution Visualization:** Animates the solving process so users can see each step.

### Application Structure
**cube.py:** Manages the 3D simulation and user interactions.

**main.py:** The main entry point of the application.

**solve_rubiccs_cube.py:** Contains the logic for solving the Rubik's Cube using the Kociemba algorithm.

## Usage
Run the Application

Start the simulation with:

    python main.py
The simulation will open in a new window displaying the 3D Rubik's Cube.

**Interactive Controls**

Use the screen buttons for face rotations. Keyboard controls will be added in future updates.

License
MIT

MIT License

Copyright (c) 2024 Rishi Ganesh T
