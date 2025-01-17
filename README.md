# CPhysics

CPhysics is a **2D physics engine** designed for use in games, written in **C++**. This engine simulates real-world physics, allowing objects to move, collide, and interact in a believable manner. It is built using standard C libraries and does not rely on third-party dependencies.

## What is a Physics Engine?

A physics engine is a software component that simulates physical systems, enabling realistic interactions between objects in a virtual environment. It handles essential functions such as:
- **Collision Detection**: Identifying when two objects intersect.
- **Collision Response**: Calculating how objects react after colliding.
- **Movement Simulation**: Simulating motion based on forces like gravity and friction.

## Features Implemented

CPhysics includes several key features that enhance its functionality, particularly focusing on fundamental physics concepts:

### Physics Concepts
- **Newton's Laws of Motion**: The engine applies Newton's laws to simulate how forces affect the motion of objects. This includes:
  - **First Law (Inertia)**: Objects remain at rest or in uniform motion unless acted upon by a force.
  - **Second Law (F=ma)**: The acceleration of an object is directly proportional to the net force acting on it and inversely proportional to its mass.
  - **Third Law (Action-Reaction)**: For every action, there is an equal and opposite reaction.

- **Friction**: The engine simulates frictional forces that affect how objects slide against each other, incorporating both static and kinetic friction.

- **Energy Conservation**: The engine ensures that energy is conserved during interactions, allowing for realistic behavior during collisions and movements.

### Additional Features
- Rigid body dynamics for simulating solid objects.
- Collision detection using methods like Axis-Aligned Bounding Boxes (AABB).
- Basic joint constraints for connecting objects.
- Object stacking and stability simulations.
- Simple particle effects for visualizing explosions.

### Future Features to Implement
The project aims to expand with additional features such as:
- More complex collision shapes and improved detection methods.
- Enhanced joint types (e.g., revolute joints).
- Fluid and soft body simulations.

## Setup Instructions

To run the CPhysics engine, follow these steps:

1. **Clone or Download the Project**: Get the repository from GitHub.
2. **Open Visual Studio**: Launch Visual Studio 2022.
3. **Open the Project Folder**: Click on "Open Local Folder" and navigate to the folder named "Rebuild of cphysics" that you cloned/downloaded.
4. **Open the Solution File**: Double-click on `Rebuild of cphysics.sln`.
5. **Select Build Configuration**: Choose the debug options "Release" and "x86".
6. **Run the Program**: Start the program to see the physics engine in action.

## License

CPhysics is developed by Hayden Marshall and is licensed under the MIT License. See `LICENSE.txt` for more information.

## Credits

Special thanks to Dirk Gregorius and Erin Catto for their invaluable resources on physics engines, which have greatly aided in the development of CPhysics.
