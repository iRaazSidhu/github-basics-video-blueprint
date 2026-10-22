# GitHub Explained Visually — Video Blueprint

A scene-by-scene production blueprint for a concise Hinglish explainer about GitHub fundamentals.

## Goal
Create a ~60-second landscape explainer that visually teaches:
- What GitHub and a repository are
- Storing code and small assets
- Git commits and change history
- Push and pull
- Branches and pull requests
- Public vs private repositories

## Production approach
- **Voice-over:** generated separately by the creator.
- **Video:** not generated in this repository; assemble externally after the voice-over is ready.
- **Storyboard:** 30 short visual beats, approximately 2 seconds each. Conform the final cut to the real voice-over timing.
- **Visual assets:** 10 original, editable SVG master visuals are provided. Reuse them across scenes with crops, zooms, pans, highlights and overlays instead of creating 30 separate images.
- **Look:** dark, clean tech explainer; restrained green accents; legible interface labels; consistent scale and typography.
- **Canvas:** 16:9 landscape, designed for YouTube.

## Repository map
- `script/narration.md` — scene-synced voice-over script in natural Hinglish.
- `script/scene-breakdown.csv` — 30-beat timing map with voice-over, visual direction, asset mapping and edit treatment.
- `storyboard/storyboard.md` — visual language, reuse plan, accuracy guardrails and editing approach.
- `assets/README.md` — visual asset index and reuse guidance.
- `assets/masters/` — 10 original SVG master visuals.

## Asset guidance
The SVG masters are 1920 × 1080 (16:9), editable and suitable for cropping or zooming. They are explanatory mockups, not guaranteed pixel-perfect captures of current GitHub screens. Keep source SVGs as masters; export optimized PNG/WebP only when needed by the editor.

Do not store rendered video exports, voice recordings, caches, dependencies or temporary renders here unless there is a specific reason.

## Current status
- [x] Repository verified and writable
- [x] Initial narration added and synced to scene beats
- [x] 30-beat scene timing CSV added
- [x] Visual storyboard and accuracy guardrails documented
- [x] 10 reusable SVG master visuals created
- [ ] Review voice-over pacing against the generated waveform
- [ ] Review all visuals and labels before final edit
- [ ] Assemble and export the final video externally

## Accuracy note
Git is the version-control system; GitHub hosts remote repositories and collaboration features. A commit records a snapshot of tracked changes. Push sends local commits to a remote; pull fetches and integrates remote changes. A pull request proposes and facilitates review of changes before merging.
