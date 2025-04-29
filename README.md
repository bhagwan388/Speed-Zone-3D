Speed-Zone-3D: 3D Car Racing Game
=================================

Speed-Zone-3D is an immersive 3D car racing game developed in Unity, showcasing advanced computer graphics, realistic vehicle physics, and AI-driven competition. Race against a challenging computer opponent on a visually rich circuit, experience dynamic environmental effects, and enjoy responsive, physics-based controls—all within a stadium-like atmosphere.

Demo
-------------------

*   **Gameplay Demo Video:** [Watch Here](https://drive.google.com/file/d/16uTexETzOL5jCsDZNIhJQgXWPApcBzF_/view)
    

Features
--------

*   **Physics-Based Racing:** Realistic vehicle dynamics including acceleration, braking, steering, gear shifting, and responsive suspension.
    
*   **Challenging AI Opponent:** Compete against a computer-controlled racer powered by advanced pathfinding and adaptive driving behaviors1.
    
*   **Immersive Environment:** Detailed terrain with mountains, plains, textured surfaces (grass, snow), and decorative elements like trees, rocks, and spectator stands.
    
*   **Dynamic Visual Effects:** Tire marks, exhaust smoke, functional headlights/taillights, and responsive mudguards enhance realism.
    
*   **Multi-Layered Audio:** Engine sounds, gear-shifting effects, and spatial audio provide an engaging soundscape.
    
*   **User Interface:** Minimalist in-game HUD, intuitive menus for car and track selection, and clear lap counters for race progression.
    
*   **Modular Asset Organization:** Structured asset folders, prefab system, and Level of Detail (LOD) for optimized performance.
    
*   **Self-Recovery System:** Cars automatically right themselves if overturned, ensuring smooth gameplay.
    
*   **Shortcuts and Surprises:** Track shortcuts offer alternative routes and strategic depth.
    

Gameplay Overview
-----------------

*   **Game Mode:** Race against one AI opponent over three laps on a circular circuit. First to finish three laps wins.
    
*   **Car Selection:** Choose between two car models (red or blue), each with distinct visual and physical properties.
    
*   **Track Selection:** Select from available circuits (circular or zigzag).
    
*   **Lap System:** Progress is tracked with a lap counter; invisible barriers prevent shortcut exploitation at the finish line.
    
*   **HUD:** Displays current lap out of three, ensuring players can track their progress.
    

Technical Highlights
--------------------

**Unity Engine Utilization**

*   Built with Unity’s physics engine, scriptable render pipeline, terrain system, and particle effects for a cohesive experience.
    
*   C# scripting manages race logic, vehicle controls, AI, and UI.
    

**AI System**

*   AI follows waypoints, adapts speed for corners, and uses randomized patterns for human-like driving.
    
*   Dynamic collision avoidance and multiple braking strategies prevent robotic behavior.
    

**Audio System**

*   Multi-channel engine audio with dynamic crossfading and pitch modulation based on real-time vehicle physics.
    
*   Spatial audio features for immersive sound based on camera position and vehicle speed.
    

Getting Started
---------------

```
git clone viveksapkal2793/Speed-Zone-3D.git
```
    
*  **Open in Unity:** Use Unity 2022.3.58f1 or later for best compatibility.
    
*  **Run the Game:** Open the main scene (Assets/MainMenu.unity) and press Play.
    

Controls
--------

*   **Steering:** Arrow keys or WASD
    
*   **Acceleration/Braking:** Up/Down arrows or W/S
    
*   **Handbrake:** Spacebar
    
*   **Menu Navigation:** Mouse
    

Asset Credits
-------------

*   Unity Technologies (Unity Engine)1
    
*   EasyRoads3D (free version) for circuit design
