# Hi — My name is Dmitry Belousov
I'm a junior Unity developer who enjoys building playable prototypes, gameplay systems and small polished experiences. I focus on clean, component-driven C# code in Unity and learning better game feel, AI, and optimization through hands-on projects.

- 🎮 Role: Junior Unity Developer — gameplay, systems, UI, basic shaders and audio
- 🌱 Currently learning: gameplay programming, optimization, AI behaviours, polish and UX
- 📫 Contact: dmni.belousov@gmail.com

## Skills
- Unity (projects include Assets, ProjectSettings, Packages)
- C# (component-based gameplay code)
- Gameplay systems: player movement, camera, enemies, quests, vehicles
- UI, input system, audio, prefabs, scene composition
- Familiar with Zenject / UniRx / UniTask (used in architecture-focused prototype)

## Projects

### Shooter — Third-person shooter prototype
https://github.com/AlexChichibabin/Shooter
A third‑person shooter prototype that demonstrates full gameplay loop work: player movement (including crouch/jump/aim/shoot), animations/rigging, multiple enemy types (patrolling drones and soldiers with detection, pursuit and shooting), vehicles (driveable + shooting), item interactions (pickups, ladders, door codes), quest triggers, save/respawn flow, and surface-specific audio/visual impacts. Project contains a structured Scripts folder (Player, ThirdPersonCamera, PatrolPath, Drone, Vehicle, Weapon, Quest, SaveSystem) and uses Unity input actions. Good demo of systems integration, scene layout (greybox → whitebox) and audio layering.

### NeuralDecay — Card game (Gwent‑style) prototype
https://github.com/AlexChichibabin/NeuralDecay
A cyber‑punk themed card game prototype modeled after Gwent. Implements Drag & Drop card handling, per-field score recalculation, match/round state machine (prepare → player turn → end round → end match), multiple card types (normal/special/elite) and fields (melee/support/ranged), UI menus with animated backgrounds, deck customization UI, sound & music, and a simple AI opponent. Well-suited to show UI workflows, game state management, and bespoke card logic.

### RestaRatio — Cooking-sim systems sandbox (architecture-focused)
https://github.com/AlexChichibabin/RestaRatio
An Overcooked-like cooking simulator built as a sandbox for scalable game system architecture. Emphasizes modularity and maintainability using:
- Dependency Injection (Zenject)
- Reactive programming (UniRx)
- Async logic (UniTask)
- Addressables for asset management
Implemented systems include orders lifecycle, player-object interactions, event-driven state updates and clear separation of responsibilities — a strong example of engineering-focused game architecture.

### Gnomopocalypse — C# Unity project
https://github.com/AlexChichibabin/Gnomopocalypse
A Unity project in C# (assets, scenes and project settings present) that appears to be an active prototype with game assets and data. The repo structure indicates scenes, assets, and supporting metadata; useful for demonstrating scene composition and asset pipeline work.

---

## How to open / run these projects
All projects are Unity projects (they contain Assets/, ProjectSettings/, and Packages/). The fastest way to open any project:
1. Clone the repo to your machine.
2. Open the project folder in the Unity Editor version that matches the project's packages (open the Editor and choose "Open Project").
3. Open the main scene(s) inside Assets/Scenes and press Play.

Note: For projects using Addressables or specific packages (Zenject, UniRx, UniTask, Input System), ensure those packages are present in the Package Manager or restored on first open.

---

Thanks for visiting — I build quick prototypes and iterate fast to learn gameplay, systems and polish.
