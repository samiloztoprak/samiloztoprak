# Şamil Öztoprak

**Gameplay Programmer** · Unreal Engine 5 & C++ · Unity & C#
Istanbul, Turkey · [samiloztoprak@gmail.com](mailto:samiloztoprak@gmail.com) · [LinkedIn](https://www.linkedin.com/in/samiloztoprak)

I have 5 years of professional experience building gameplay systems in Unreal Engine 5 with C++ and Blueprints. My main areas are combat and melee systems, AI navigation and movement, physics-based hit reactions and game feel. Now I am also building mobile puzzle games with Unity and C#.

---

## Featured Work

### SmoothPath — AI Path Smoothing Plugin (UE5 / C++)
**[View on Fab](https://fab.com/sellers/SamilOztoprak)**
<img width="1280" height="720" alt="smoothpath_banner" src="https://github.com/user-attachments/assets/9766a3ec-85cc-45a4-b4cb-991fb74ade33" />

My own plugin, published on Fab. I designed and wrote everything myself.

- Overrides Unreal's navmesh pathfinding (`FNavMeshPath`, `ARecastNavMesh`)
- Custom funnel algorithm with offset parameters
- Catmull-Rom spline processing, so AI characters follow smooth paths instead of sharp corners

### Black State — Motion Blur Game Studio (UE5 / C++)
**[Watch the trailer](https://www.youtube.com/watch?v=FJP2comhcN8)**
<img width="1280" height="720" alt="blackstate_takedown" src="https://github.com/user-attachments/assets/b2d34eb9-4f45-41ae-9fce-d9686cf94a5d" />

Team project. I worked on it for 5 years, first as Gameplay Programmer, then as Mid Game Developer. My main systems:

- Asynchronous melee and takedown system
- Physics-based hit reactions with the Physical Animation Component
- Flying AI movement and AI steering behaviors
- Sequencer-driven camera work for takedowns
- Many gameplay features: weapons, movement abilities (vault), doors and interactions

### Match-3 Puzzle Game (Unity / C#) — in progress

**[See Repository](https://github.com/samiloztoprak/match3)**

<img width="300" height="533" alt="gameplay_4" src="https://github.com/user-attachments/assets/074cede2-f71e-42ad-b9c3-5a94caa34753" />

A Match-3 game I am building to show clean, testable game architecture.

- **Pure C# core** with no Unity references, so all game rules can be tested with NUnit without opening Unity
- **Command pattern** for moves: each turn and all cascades are resolved first, then the presentation layer replays them step by step with animations
- Obstacles (boxes, chains) and a **data-driven shape detection** system for match shapes
- **Object pooling** for pieces and particles, zero GC allocation at runtime (checked with the Unity Profiler)

---

## Skills

**Languages:** C++, C#, Python
**Unreal Engine 5:** Gameplay Framework, Gameplay Ability System (GAS), Blueprints, AI / Navmesh, Sequencer, Physical Animation
**Unity:** C#, architecture separated from MonoBehaviour, NUnit / Unity Test Runner, Profiler, object pooling, DOTween
**Tools:** Visual Studio, Git, Perforce
