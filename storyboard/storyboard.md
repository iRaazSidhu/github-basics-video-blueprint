# Storyboard & Visual System

## Creative goal
Explain GitHub fundamentals through one consistent visual language. Viewers should understand each concept from the visual before reading small details. This is a planning document only: no rendered video, voice recording, or final artwork is included yet.

## Format
- Aspect ratio: 16:9 landscape.
- Working duration: ~60 seconds.
- Scene beats: 30 × ~2 seconds; timing will be conformed to the final voice-over.
- Language: Hinglish in Roman script.
- Look: modern, dark tech explainer with restrained green accents, neutral text, clean spacing, precise UI-inspired diagrams and limited motion.
- Text: keep overlays short; narration carries the full explanation.
- Accessibility: high contrast, readable type, avoid relying only on color to signal meaning.

## Reusable visual strategy
**Target: 8–10 master visuals, not 30 unique images.** One master asset may power several scene beats through crop, zoom, pan, masking, highlights, labels, or animated overlays. Avoid repeatedly generating near-identical images.

| Master ID | Master visual | Scenes | Reuse strategy |
|---|---|---|---|
| M01 | Abstract code world / laptop to online storage | S01–S02 | Wide establishing image; crop into code details; animate file tiles toward repository |
| M02 | Repository overview UI | S03–S05 | Reframe from title to file list to activity/history pane |
| M03 | Create repository form + folder analogy | S06–S07 | One interface composition and one simple folder-to-tree transition, preferably vector/UI |
| M04 | Project file tree with code and image assets | S08–S10 | Sequentially highlight HTML/CSS, JS/images, then show full tree |
| M05 | Git commit/history graph | S11, S13–S16 | Reuse the same timeline; reveal nodes over time and select versions |
| M06 | Code diff before/after | S12, S17 | Same diff view; first establish the change, later highlight additions/removals |
| M07 | Local/remote repository flow | S18–S21 | One diagram; animate push left-to-right and pull right-to-left |
| M08 | Branch, pull request and merge graph/UI | S22–S25 | Same graph plus a focused PR review panel; branch later rejoins main |
| M09 | Public/private visibility visual | S26–S28 | Same settings panel; transition lock/private to globe/public |
| M10 | Recap and end card | S29–S30 | Built from existing icons/labels and repository motifs; no new photorealistic image required |

## Asset-making order
1. Lock the core visual tokens: background, accent, type scale, UI radius, line weight and icon style.
2. Create M02 (repository UI) and M04 (file tree) first; they establish the screen and component style.
3. Create vector-based diagrams M05, M07 and M08 so lines, nodes and labels remain crisp and easy to animate.
4. Create M03, M06 and M09 as UI compositions consistent with the established style.
5. Derive M01 and M10 from the same palette and existing elements.
6. Produce scene crops/overlays only after master assets are approved.

## Accuracy guardrails
- Git is the version-control system; GitHub is the hosting and collaboration platform.
- A repository contains project files and their version history. Avoid suggesting that GitHub is only a cloud-drive folder.
- A commit records a snapshot of tracked changes.
- Push sends local commits to a remote; pull fetches and integrates remote changes.
- A branch supports independent work. A pull request proposes changes for discussion/review and eventual merge; it is not the same as a merge.
- Private visibility restricts access; public repositories can be viewed by others.
- UI mockups are explanatory, not promised to match every current GitHub interface pixel-for-pixel.

## Editing guidance
- Use each two-second scene as a visual beat, not necessarily a hard cut.
- Prefer continuous motion and matched composition over flashing between many screenshots.
- When a master visual appears in adjacent scenes, move the crop or highlight to match the narration.
- Keep on-screen text to one short label or phrase at a time.
- Add the generated voice-over only during editing; conform scene durations to its real timing.
- Do not commit final video exports, caches, temporary project files or voice files into this repository by default.

## Status
- [x] Repo verified and writable
- [x] Narration draft committed
- [x] 30-beat timing CSV committed
- [x] Master-visual strategy and accuracy guardrails committed
- [ ] Approve script wording and final voice-over length
- [ ] Design master visuals
- [ ] Review visual assets before editing
