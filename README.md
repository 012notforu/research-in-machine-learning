# Research Engineering Portfolio — Interactive Physics Simulations

This repository contains a collection of interactive web-based simulations exploring phase field dynamics, gauge theory, and mathematical physics. All simulations run entirely in the browser with no server-side dependencies.

---

## Research Hub

**What is this?**  
`research-hub.html` is the main dashboard that organizes and links to all simulation files. Open it in your browser after starting a local server to access any simulation. Everything runs client-side with no data collection or external dependencies.

**Open locally:** <http://localhost:8000/research-hub.html>

---

## Quick Start

**Python (recommended):**
```bash
# From the repository root
python3 -m http.server 8000
# Then open: http://localhost:8000/research-hub.html
```

**Node.js (alternative):**
```bash
# From the repository root
npx http-server -p 8000
# Then open: http://localhost:8000/research-hub.html
```

---

## What's Included

### Phase Field Dynamics
- **Coherence-Curvature Sim**: 2D phase field visualization with curvature analysis
- **Lattice Phase Field Sim**: Discrete lattice-based phase field evolution
- **Wave to Grid**: Wave function discretization and grid transformation

### Gauge Theory & Topology  
- **Symbolic Gauge Lab**: Interactive gauge field visualization and manipulation
- **3D Torus Curvature Testing**: Three-dimensional toroidal surface analysis
- **Toroidal Phase Pattern Tracker**: Pattern detection and tracking on toroidal surfaces

### Field Dynamics & Diagnostics
- **Field Dynamics Lab**: Spin field diagnostics and visualization
- **Symbolic Fluid Dynamics**: Non-standard fluid simulation approaches

### Mathematical Models
- **EM-Inspired 2D Toroidal Model**: Electromagnetic-inspired toy model
- **Very Early Model**: Initial prototype and concept testing
- **N-ary Phasor Platform**: Multi-dimensional phasor analysis
- **Coherence Automata**: Cellular automata with coherence-based rules

---

## Purpose

This portfolio demonstrates practical approaches to computational physics and mathematical modeling:

- **Interactive experimentation**: Parameter adjustment and visualization
- **Reproducible results**: Deterministic simulations with seeded randomness
- **Educational value**: Clear, inspectable code for learning concepts
- **Research prototyping**: Rapid iteration on mathematical ideas

## Technical Approach

- **Client-side only**: No server dependencies, runs entirely in browser
- **Canvas-based rendering**: 2D/3D visualization using HTML5 Canvas and WebGL
- **Modular design**: Self-contained simulation files
- **Performance optimized**: Designed for smooth interactive experience

## Scope & Limitations

These are research prototypes intended for exploration and learning. They:
- Focus on mathematical and physical concepts
- Avoid sensitive or dual-use applications  
- Make claims only to the extent demonstrated by the code
- Are designed for educational and research purposes

## Contact

Matthew Gautier — see profile for contact information or open an issue in this repository.
