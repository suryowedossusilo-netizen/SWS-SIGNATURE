# AGENT.md — SWS-SIGNATURE

## Design authority
Use the pinned official Taste Skill at `.agents/skills/design-taste-frontend/SKILL.md` and the full upstream package submodule at `.agents/plugins/taste-skill`. Read the relevant references before design changes. The user's explicit creative brief overrides conflicting default style restrictions: this portfolio must have one central interactive 3D samurai character and a narrative built around it.

## Creative direction
Concept: **THE GUARDIAN'S OATH**. A samurai is the central 3D character and a visual metaphor for discipline, vigilance, service and reliability—not a claim that the owner is a warrior. The story connects the oath, the path (network/infrastructure), the watch (troubleshooting and user support), the armoury (projects), and the next chapter (contact). Keep actual experience and metaphor clearly distinct.

## 3D and performance
Use one real, lightweight 3D character in the hero only. Current CC0 model: Samurai Commander, 3.9k triangles, animations idle/bow/wave, hosted at `https://cdn.3dassets.dev/assets/39186/v1/model.glb`. Use model-viewer, transparent stage, camera controls, keyboard accessibility, and a readable fallback. Do not add extra WebGL scenes, particle systems, shaders, scroll-jacking or multiple 3D contexts. Keep mobile and reduced-motion behavior usable.

## Content integrity
Never invent employment, dates, education, certifications, metrics, testimonials, clients or outcomes. Never claim RDP / remote desktop experience. Use “nearly five years”, not “5+ years”. Keep the UWP S1 degree in progress. Keep project statuses accurate: ERP Multi Talent — In Development; Fun Run UWP — Development / Prototype; Finova — UI/UX Prototype (Auto-Split frontend simulation); Greedy Nearest Neighbor — Academic Project.

## Technical constraints
Static HTML, CSS and vanilla JavaScript. No framework, build system, analytics, trackers, forms or chat widgets. Keep GitHub Pages-compatible relative paths. Respect keyboard access and `prefers-reduced-motion`.

## Git safety
Main only; no branches. Never add secrets, .env, private keys or database dumps. Do not delete files or alter repository settings without approval. Do not force-push. Preserve CV routes and existing assets. Report exact changes and checks.