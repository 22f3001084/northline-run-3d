# Asset attribution

The following visual assets were made for this project:

- **3D kit** (`blender/out/kit.glb`): authored procedurally by
  `blender/build_kit.py` + `be6.py` + `ambulance.py` (Blender 5.2). No
  downloaded models.
- **Title / report / backdrop art and icons**: project-generated images in
  `src/assets/img/`.
- **Answer cards, sensor diagrams, glows**: drawn at runtime on canvas.

**Audio**: project-supplied mp3 clips in `src/assets/audio/` plus synthesised
cues (WebAudio, `src/sound.ts`). The bundled Suhana recordings cover the fixed narration. Browser speech
synthesis (prefers `en-IN`) is available for other lines.

**Fonts** (bundled for offline use): Inter and Chakra Petch — SIL Open Font
License 1.1.

**Libraries** (MIT): three.js, React, Zustand, framer-motion, Howler, @dnd-kit.

## Ferrari 458

[Ferrari 458 Italia](https://sketchfab.com/models/57bf6cc56931426e87494f554df1dab6) by vicent091036, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Reused from the project's HydroWorks build, adapted with red paint, wheel animation and a sensor pod, and rendered in a new workshop scene. The selectable cockpit is original, procedural geometry.
