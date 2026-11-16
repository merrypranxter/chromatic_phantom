# CHROMATIC PHANTOM — Master Roadmap

## Artistic North Star

Use soft, bulbous, slowly morphing geometry to show **milky near-white fluorescence, lavender haze, cobalt outlines, hot coral edges, and soft spectral optical boundaries**. No scanlines, VHS, tearing, block noise, or glitch aesthetics. The color and material should respond to meaningful mathematical features.

## Phase 01 — Playable proof of concept (implemented)

Three visibly distinct mathematical generator modes: smooth SDF union (Opal Mitosis), angular harmonic membrane (Resonance Bellies), and force-driven cell cluster (Pressure Garden). All three use the same optical renderer and controls. Editable paletted material, responsive mobile canvas, direct manipulation, JSON and PNG.

### Verification still needed

- iPhone Safari WebGL2 shader compile, pointer/touch latency, battery and resolution testing.
- PNG dimensions at different aspect ratios; preserved color through Photos/CapCut.
- Cross-browser shader and WebGL context restoration QA.
- Visual comparison against the supplied reference video's *optical feel*, not its animation.

## Phase 02 — Optical material as portable subsystem

Split GLSL material into a reusable module. Typed inputs: signed distance, surface normal, thickness, optional curvature, phase, region ID and palette. Distinguish physically grounded optical paths from illustrative neon grading. Apply Scattering Syndicate/Thickness Thief to thickness-dependent haze and transmission. Add physically motivated iridescence with Iridescent Organist only when real normal, view and film-thickness data exist. Preserve source palettes exactly; obtain full palette collection from verified repositories.

## Phase 03 — Deepen the mathematics

- True conserved Cahn–Hilliard phase separation with bounded timesteps, invariants, meaningful fusion/pinch events.
- Membrane eigenmode decomposition instead of purely stylized angular harmonics, optionally Bessel/spherical-harmonic geometries.
- Pressure/curvature flow with explicit forces, boundaries, and numerical integration diagnostics.
- Capillary surface transport and wetting.
- Void growth with actual topology changes and pore connectivity.
- Quasicrystal pillows with real phason neighborhood changes.
- Differentiated morphogen anatomy; true reaction–diffusion on curved surfaces.
- Nematic director fields driving anatomy rather than painted stripes.

Each should have an engine-specific structural control and be measurably different, not a recolor.

## Phase 04 — Touch, composition, palette vault and discovery

Direct push/pinch/inflate/divide where the math supports it. Undoable atomic gestures, protection brushes, editable per-region palettes, save/load checkpoints, parameter-space discovery and Surprise Me retaining full editability. Mobile UI: artwork on top, compact tabs and draggable split panel. No blank background-only presets.

## Phase 05 — Causal crossbreeding

Handoff Blacksmith checks typed fields, grid sizes, coordinate spaces, boundary conditions, clocks, color spaces and ownership. Causality Switchboard validates real bidirectional feedback, stable integration, identical-seed ON/OFF experiments. Breed mechanisms, not just screenshots.

## Phase 06 — True 3D and export

Three.js geometry where needed; actual normal/curvature/thickness fields and camera-based iridescence. Preserve a fast WebGL2 2D/2.5D path for mobile. Offline deterministic frame capture independent of low-resolution preview. Actual GIF89a and H.264 MP4 encoders, high bitrate, 1:1/9:16 and optional other ratios. Validate loop closure for periodic systems. Never claim irreversible stateful growth is natively loopable.

## Specialist routing

- **Mechanisms:** Curvature Cartel, Resonance Luthier, Capillary Cult, Morphogenesis Department, Surface Dweller, Phason Smuggler.
- **Optics & color:** Scattering Syndicate, Thickness Thief, Iridescent Organist, Chromatic Choreographer, Color Topologist, Palette Necromancer.
- **Art quality & interactions:** Gesture Witch, Novelty Inquisitor, Composition Witch, Parameter Cartographer.
- **Integration & reliability:** Handoff Blacksmith, Causality Switchboard (actual feedback only), Rendering Survivalist, Loop Surgeon, Shader Exorcist, Gamut Gremlin.
- **Computation:** Wolfram only when a concrete symbolic/numerical question benefits from it.

## Hosting discipline

GitHub Pages by default; no paid services. No automatic Netlify deployment. Keep dev independent of export quality. Verify behavior before claiming passes.
