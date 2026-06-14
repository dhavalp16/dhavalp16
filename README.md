# Dhaval Panchal

IT Engineering Graduate (Mumbai University, '26), based in Mumbai.  
Focused on C++ systems programming and engine architecture.  
Computer graphics and game systems are where I want to build my career, so that's where I spend my time.

---

## What I'm Building

**Stardust** - Real-time 3D N-Body Physics Engine

A gravitational simulation in C++ using Raylib 5.5 where multiple bodies exert mutual gravitational pull, collide, and explode. Core systems: Euler integration with sub-stepping, delta-time scaling, object pooling for explosion effects, sphere-sphere collision detection, and additive-blend wireframe explosion rendering.

**Problems I solved:**

**1. Real planetary distances don't work on screen.**  
The actual solar system has planets too far apart to see simultaneously. I compressed orbital distances to keep everything visible while preserving relative scale and gravitational behavior. It's a deliberate design choice for an educational/game-like simulation - plausible, not physically exact.

**2. Planet textures rendered black.**  
Root cause: no lighting shader loaded, no light source in the scene. Raylib's 3D renderer doesn't assume lighting - without explicitly loading GLSL shaders and creating a light, objects render with zero light contribution. Fixed by implementing a Phong lighting pipeline (lighting.vs / lighting.fs) and placing a point light at the Sun's position.

-> [Repository link](https://github.com/dhavalp16/Stardust.git)

---

## Active Learning

**Low-Level C++ - The Cherno Series**  
Working through memory architecture, pointers, stack vs heap allocation. Building comprehension from first principles.

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

---

## Contact

[LinkedIn](https://www.linkedin.com/in/dhavalp16) · dhavaljpanchal1602@gmail.com · Mumbai, India
