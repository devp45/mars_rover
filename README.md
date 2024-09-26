# Mars Rover Simulation

## Problem Statement
Create a simulation for a Mars Rover that can navigate a grid-based terrain. The Rover should be able to move forward, turn left, and turn right, while avoiding obstacles and staying within the boundaries of the grid. The simulation should utilize pure Object-Oriented Programming (OOP), design patterns, and avoid using if-else conditional constructs.

## Functional Requirements
1. **Initialize the Rover** with a starting position `(x, y)` and direction `(N, S, E, W)`.
2. Implement the following commands:
   - **'M'**: Move one step forward in the direction the Rover is facing.
   - **'L'**: Turn left.
   - **'R'**: Turn right.
3. **Obstacle Detection**: If an obstacle is detected in the path, the Rover should not move.
4. Optional: Add functionality for the Rover to send a **status report** containing its current position and facing direction.

## Key Focus
- **Behavioral Pattern**: Use the **Command Pattern** to encapsulate 'M', 'L', 'R' as objects for flexibility.
- **Structural Pattern**: Use the **Composite Pattern** to represent the grid and obstacles.
- **OOP Principles**: Leverage encapsulation, inheritance, and polymorphism.

## Possible Inputs
- **Grid Size**: (10 x 10)
- **Starting Position**: (0, 0, N)
- **Commands**: ['M', 'M', 'R', 'M', 'L', 'M']
- **Obstacles**: [(2, 2), (3, 5)]

## Possible Outputs
- **Final Position**: (1, 3, E)
- **Status Report**: `"Rover is at (1, 3) facing East. No Obstacles detected."`

## Design Patterns Used
1. **Command Pattern**: Each command (Move, Turn Left, Turn Right) is encapsulated as an object, promoting flexibility in adding or modifying commands.
2. **Composite Pattern**: The grid and obstacles are structured in a composite format, enabling easy representation and management of grid elements.

## Technologies
- **Language**: Java / Python
- **Design Patterns**: Command Pattern, Composite Pattern
- **OOP Concepts**: Inheritance, Polymorphism, Encapsulation

---

## How to Run

1. Clone the repository.
2. Navigate to the project folder.
3. Run the simulation.

```bash
git clone <repository-url>
cd mars-rover-simulation
# Run the simulation
