# Path_Finding_Visualize

#Tech Stacks and Tools Used:
Programming Languages: C++ (SFML library)
Libraries: SFML (Simple and Fast Multimedia Library)

#Functions and Features

Pathfinding Algorithms: The project implements several pathfinding algorithms:
Breadth-First Search
Greedy Best-First Search
A Algorithm*

Grid Manipulation:
Rendering Grid: Renders a grid-based environment where each cell represents a tile.
Tile Interaction: Allows users to interact with tiles by setting them as solid or empty, similar to a maze or grid-based game environment.

User Interface (UI):
UI Elements: Provides various UI elements for controlling and visualizing the pathfinding process:
Sliders (gridSizeSlider, animationSpeedSlider) for adjusting grid size and animation speed.
Checkboxes (displayFrontierButton, displaySearchedButton) for toggling display of frontier and searched tiles.
Buttons (animationButtons, gridButtons) for controlling animation (start, pause, reset, increment) and grid operations (clear, fill, generate noise).
Other interactive elements like framerateButton, exitButton, and soundSlider.

Markers and Path Visualization:
Start and End Markers: Allows placement and locking of start and end markers on the grid.
Path Rendering: Visualizes the path found by the selected pathfinding algorithm using colored path segments.

Custom Game Engine Components:
Namespace (gs::): Contains utility functions (clamp, approach), rendering functions (renderGrid, renderPath), and UI management functions (updateUI, renderUI).
Structures (gs::Vec2f, gs::Vec2i, gs::Color): Custom data structures for managing grid positions, colors, and vector operations.
Project Purpose
The project's main purpose is to provide a visual representation of various pathfinding algorithms in action. Users can interactively set up obstacles, adjust parameters, and observe how each algorithm navigates the grid environment to find the shortest path from a start to an end point.
