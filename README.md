# Flytbase-UAV-Strategic-Deconfiction-in-Shared-Airspace
**Table of Contents**
    About The Project
    Built With
    Getting Started
        Prerequisites
        Installation
    Usage
    Conflict Types & Resolution
    Roadmap
    Contributing
    License
    Contact

**About The Project :**
UAV Strategic Deconfliction in Shared Airspace simulates a multi-drone airspace environment, identifies flight conflicts (spatial, temporal, NFZ, infrastructure), and applies smart AI-based conflict resolution strategies.

**Why This Project? :**
Enables safer and more efficient drone operations in congested airspace, Modular design for plug-and-play testing of multiple resolution algorithms, Offers detailed visualizations and logs for flight review and debugging

**Core Features :** 3D/2D plotting and animation, Modular input/output segments, Conflict explanation and resolution tagging, Includes A*, RRT, heuristics, and temporal/z-axis offset methods

**Built With :**  Python 3.10+, matplotlib (2D/3D visualization), numpy (geometry & interpolation), heapq, networkx (A* path planning), Google Colab / Jupyter

**Prerequisites :**  pip install matplotlib numpy networkx

**Code Structure :** 

Step 1 → Run Segment 1 (Core Components)

Step 2 → Choose and run Segment 2A (Path With Conflicts) OR 2B (Conflict-Free Path)

Step 3 → Choose a Resolution Strategy from:
- Segment 3A: Temporal & Z-axis Shift
- Segment 3B: Heuristic Path Bypass
- Segment 3C: RRT-based Replanning
- Segment 3D: A* Spatio-Temporal Path Planning
- Segment 3E: Priority-Based Reordering

Step 4 → Run Segment 4 for Animation & Conflict Visualization

**Conflict Types & Resolution :** 

Conflict Types : Spatial / Temporal / Spatio-Temporal Conflicts, Path Interference, Takeoff/Landing Conflicts, NFZ Violation, Infrastructure & Obstacle Collision

Resolution Methods : Temporal Shifting (Delay/Advance), Altitude Diversion (Z-Axis Offset), Path Offset (XY Plane), A* Path Replanning, RRT Random Sampling, Maxima/Minima Heuristic Detouring, Priority-Based Sorting, Predefined Safe Corridors

**Contact** : 

jangidrahul@gmail.com
    
https://www.linkedin.com/in/rahul-jangid-909872126/
    
https://colab.research.google.com/drive/1NMvANJG_oigWAcmvUQp8gQU62_WsxRiF?usp=sharing
    
