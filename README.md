# Dhaval Panchal

Final-year IT Engineering student (Mumbai University, '26), based in Mumbai.  
Focused on C++ systems programming and engine architecture.  
Computer graphics and game systems are where I want to build my career -
so that's where I spend my time outside of class.

---

## What I'm Building

**Stardust** - Real-time 3D N-Body Physics Engine

Built a real-time gravitational simulation in C++ using Raylib 5.5, where multiple
bodies exert mutual gravitational pull, collide, and explode.  
Core systems: Euler integration, delta-time scaling, Tombstone Explosion Pool
(object pooling), sphere-sphere collision detection, and additive-blend
wireframe explosion rendering.

**Problems I solved:**

**1. Real planetary distances break the simulation visually.**  
In reality, the planets in our solar system are too far apart to fit on any screen
meaningfully. The fix was a deliberate design decision: compress orbital distances
to keep all bodies visible simultaneously while preserving relative scale and
gravitational behaviour. The goal was educational and game-like - plausible, not
physically exact.

**2. Planet textures rendered completely black.**  
Root cause: no lighting shader was loaded and no light source existed in the scene.
Raylib's 3D renderer makes zero assumptions about lighting - without explicitly
loading a GLSL shader pair and calling CreateLight(), objects render with zero
light contribution regardless of texture. Fixed by implementing a full
Phong lighting pipeline (lighting.vs / lighting.fs) and placing a point
light at the Sun's position.

-> [Repository link](https://github.com/dhavalp16/Stardust.git)

---

## Active Learning

**Low-Level C++ - The Cherno Series**  
Working through memory architecture, pointers, stack vs heap allocation.  
Building comprehension from first principles.

**Coursera: C++ Programming for Unreal Game Development**  
Specialization in progress. Targeting engine-level work in UE5.

---

## Tech Stack

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Raylib](https://img.shields.io/badge/Raylib-000000?style=flat&logo=raylib&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-0E1128?style=flat&logo=unrealengine&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=flat&logo=blender&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat&logo=visualstudio&logoColor=white)
![Antigravity](https://img.shields.io/badge/Antigravity-FF6B35?style=flat&logoColor=white)

---

## Experience

**Data Curation Intern - Greenox** (6 months)  
ML pipeline support and spatial dataset curation.

**Incoming Analyst - Capgemini**

---

## Contact

[LinkedIn](https://www.linkedin.com/in/dhavalp16) · dhavaljpanchal1602@gmail.com · Mumbai, India
