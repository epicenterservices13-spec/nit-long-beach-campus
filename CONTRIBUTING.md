# Contributing to NIT Long Beach Campus

Thank you for investing your engineering acumen into the **National Institute of Technology, Long Beach** digital twin and curriculum engine.

## Architectural Principles
1. **Zero Bloat:** All 3D WebGL modules must remain ultra-performant, capable of rendering at 60 FPS on mobile ARM and low-spec tablets.
2. **Mechanical Fidelity:** Machine specs, classroom dimensions, and electrical busway ratings must adhere strictly to real-world industrial standards (ASME, NEC NFPA 70, OSHA).
3. **Atomic Commits:** One file per commit. Clean, descriptive imperative commit messages.

## Development Workflow
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/advanced-turbine-bay`).
3. Commit your changes atomically (`git add <file> && git commit -m "feat(<file>): add description"`).
4. Push to your branch and submit a Pull Request.

## Coding Guidelines (Three.js)
- Use standard `THREE.InstancedMesh` for high-repetition geometry (pillars, chairs, windows).
- Clean up geometries and materials on scene changes to prevent WebGL memory leaks.
- Ensure touch and keyboard accessibility are never compromised.
