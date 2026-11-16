# CHROMATIC PHANTOM

A touchable art laboratory for soft, inflated, morphing mathematical forms coated in luminous milky chromatic color. **No glitch look.**

## First playable phase

- **Opal Mitosis:** moving, smooth-union implicit blobs; drag one to reshape the connected silhouette.
- **Resonance Bellies:** an angular harmonic membrane; tap and drag to excite local waves.
- **Pressure Garden:** discrete inflated cells that push each other and relax to target positions. A reduced artistic force model, not calibrated fluid mechanics.
- **Chromatic Phantom material:** milky near-white interiors, contour-dependent colored fringe, soft radiance, pearlescence, and subtle background echoes.
- **Creative controls:** 7 sample color families, custom JSON palette imports (2–8 #RRGGBB stops), independent optical knobs, editable Surprise Me, Reseed, Undo/Redo, New Design with confirmation.
- **Save/export:** local save and restore, PNG, editable state JSON import/export; 1:1, 9:16, 16:9, 3:4, 4:3.

## View it free on GitHub Pages

This project is a **static, single-file HTML/WebGL2 app**, with no external asset dependencies and no API keys. Use GitHub's **Settings → Pages → Deploy from a branch → main / (root)**. Once Pages is enabled, the expected URL is:

https://merrypranxter.github.io/chromatic_phantom/

This is a prospective URL, not a claim Pages is currently enabled. The root \`index.html\` is the actual app. You can also run \`npm install && npm run dev\` with the optional Vite configuration.

**No Netlify action was invoked to build this app.** If this repository was previously linked to Netlify automatic deploys, manage that separately in its settings.

## What's honest

This phase models **optical appearance artistically**, using GLSL distance fields, numerical gradient normals, RGB palette ramps and expressive glow. It does not claim calibrated thin-film spectra, fluid simulation, or volumetric light transport.

PNG export is real. **GIF and MP4 exports are not yet implemented** and are on the roadmap. A saved state captures model parameters, positions, palette, and clock; a deterministic seed does not make arbitrary stateful pressure trajectories exact loops.

Mobile performance and iPhone Safari rendering still need real-device verification. The app uses WebGL2 and honors \`prefers-reduced-motion\`.

## Roadmap

See [docs/ROADMAP.md](docs/ROADMAP.md) for the engine expansion, optical-material modularization, mathematical feedback/breeding, touch upgrades, and verified export pipeline.
