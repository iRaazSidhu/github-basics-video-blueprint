# Storyboard & Visual System

## Creative goal
Explain GitHub fundamentals through one consistent visual language. Viewers should understand each concept from the visual before reading small details. This repository contains the plan and editable SVG master artwork; no rendered video or voice recording is included.

## Format
- Aspect ratio: 16:9 landscape.
- Working duration: ~60 seconds.
- Scene beats: 30 × ~2 seconds; timing will be conformed to the final voice-over waveform.
- Language: Hinglish in Roman script.
- Look: modern, dark tech explainer with restrained green accents, neutral text, clean spacing, precise UI-inspired diagrams and limited motion.
- Text: keep overlays short; narration carries the full explanation.
- Accessibility: high contrast, readable type, avoid relying only on color to signal meaning.

## Reusable visual strategy
**10 master visuals power 30 scene beats.** One master asset can support multiple beats through crop, zoom, pan, masking, highlights, labels or animated overlays. Avoid repeatedly generating near-identical images.

| Master ID | Master visual | Scenes | Reuse strategy |
|---|---|---|---|
| M01 | Abstract code world / laptop to online storage | S01–S02 | Wide establishing frame; crop into code details; animate file tiles toward remote storage |
| M02 | Repository overview UI | S03–S05 | Reframe from title to file list to activity/history pane |
| M03 | Create repository form + folder analogy | S06–S07 | Pan across the form; use a matched transition into the project tree |
| M04 | Project file tree with code and image assets | S08–S10 | Sequentially highlight HTML/CSS, JS/images, then show the full tree |
| M05 | Git commit/history graph | S11, S13, S15–S16 | Reuse the same timeline; reveal nodes over time and select checkpoints |
| M06 | Code diff before/after | S12, S14, S17 | Reuse the same code comparison; highlight selected changes, additions and removals |
| M07 | Local/remote repository flow | S18–S21 | One diagram; animate push left-to-right and pull right-to-left |
| M08 | Branch, pull request and merge graph/UI | S22–S25 | Reuse the graph and pull request panel; animate branch joining main after review |
| M09 | Public/private visibility visual | S26–S28 | Same side-by-side composition; transition lock/private to globe/public |
| M10 | Recap and end card | S29–S30 | Reuse existing concepts and labels; no new artwork required |

## Visual master files
See [assets/README.md](../assets/README.md) for a linked index of the ten SVGs. They are original explanatory vector mockups, not exact screenshots of any promised current GitHub interface.

## Production order
1. Review this visual system and the SVG masters.
2. Generate the voice-over separately, then measure its actual duration.
3. Adjust scene cut points to the spoken phrases; let adjacent beats flow where possible.
4. Build crops/highlights from the master SVGs; keep labels in separate editable overlays when practical.
5. Check every Git/GitHub concept for accuracy before publishing.
6. Export the finished video outside this repository.

## Accuracy guardrails
- Git is the version-control system; GitHub is the hosting and collaboration platform.
- A repository contains project files and their version history. Avoid suggesting GitHub is only a cloud-drive folder.
- A commit records a snapshot of tracked changes.
- Push sends local commits to a remote; pull fetches and integrates remote changes.
- A branch supports independent work. A pull request proposes changes for discussion/review and eventual merge; it is not the same as the merge.
- Private visibility restricts access; public repositories can be viewed by others.
- UI mockups here are for explanation and are not promised to match every current GitHub interface pixel-for-pixel.

## Editing guidance
- Treat each two-second scene as a visual beat, not necessarily a hard cut.
- Prefer continuous motion and matched composition over flashing between many screenshots.
- When the same master appears in adjacent scenes, move the crop or highlight to match the narration.
- Keep on-screen text to one short label or phrase at a time.
- Add the generated voice-over only during editing; conform scene durations to its real timing.
- Do not commit final video exports, caches, temporary project files or voice files into this repository by default.

## Status
- [x] Repo verified and writable
- [x] Scene-synced narration committed
- [x] 30-beat timing CSV committed
- [x] Ten editable SVG master visuals committed
- [x] Accuracy guardrails documented
- [ ] Review the generated voice-over pacing
- [ ] Review visual assets before editing
- [ ] Assemble the final edit externally
