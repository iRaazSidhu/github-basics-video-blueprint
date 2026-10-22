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
- **Video:** not generated in this repository at the planning stage.
- **Storyboarding:** 30 short visual beats, approximately 2 seconds each.
- **Visual assets:** build a small set of reusable master visuals (target: 8–10), then create crops, zooms, pans, highlights and transitions from those sources. Do not create 30 separate images by default.
- **Look:** dark, clean tech explainer; restrained green accents; legible interface labels; consistent lighting, scale and typography.
- **Canvas:** 16:9 landscape, designed for YouTube.

## Repository map
- `script/narration.md` — voice-over script in natural Hinglish.
- `script/scene-breakdown.csv` — timing, narration, visual direction and asset mapping for each beat.
- `storyboard/storyboard.md` — visual language, scene sequence and reusable-asset plan.
- `assets/` — finalized visual assets, grouped by master visual rather than duplicated per scene.

## Asset naming
Use descriptive, stable names such as:
- `ui-repository-create.png`
- `ui-file-tree.png`
- `git-commit-timeline.png`
- `git-diff-view.png`
- `git-push-pull-diagram.png`
- `git-branch-pr-merge.png`
- `privacy-public-private.png`

Prefer WebP or optimized PNG for raster assets and SVG for diagrams. Keep individual files reasonably small. Don't store rendered video exports, voice recordings, caches, dependencies or temporary renders in this repository unless there is a specific reason.

## Current status
- [x] Repository verified
- [x] Initial narration and scene plan added
- [x] Reusable-visual strategy documented
- [ ] Review voice-over pacing
- [ ] Create / source approved master visual assets
- [ ] Review factual accuracy and UI depiction
- [ ] Edit final video externally

## Accuracy note
Git is the version-control system; GitHub hosts remote repositories and collaboration features. A commit records a snapshot of tracked changes. Push sends local commits to a remote; pull fetches and integrates remote changes. A pull request proposes and facilitates review of changes before merging.
