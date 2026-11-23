# AGENT.md — SWS-SIGNATURE

## Creative brief (user-owned)
The user explicitly wants a **cinematic 3D samurai character as the main protagonist, with a story**. This is not a dark editorial/minimal portfolio. Do not revert to that direction.

## Art direction
Concept: THE GUARDIAN'S OATH — an interactive cinematic chronicle. The samurai is a real 3D character, not a still illustration or decorative icon. Use dramatic framing, a blood-red moon, layered silhouettes, atmospheric fog, embers, cinematic lighting, film grain, letterbox opening, deliberate typography and scroll-led story chapters. The narrative metaphor connects discipline/service to real IT work. Keep the factual CV separate from the samurai fiction.

## Story beats
Prologue / The Guardian's Oath → Chapter I The Oath (preparation) → Chapter II The Path (fiber/network/server connections) → Chapter III The Watch (troubleshooting and user support) → Field Record (actual employment) → Armoury (real projects) → Discipline (education and leadership) → Next Chapter (contact).

## 3D character
Use the CC0 Samurai Commander GLB: `https://cdn.3dassets.dev/assets/39186/v1/model.glb` (3.9k triangles; idle, bow, wave; CC0 1.0). The GLB endpoint was checked and returns a valid binary glTF. Use model-viewer with clear camera framing, visible fallback, loading/error states. Do not replace the character with a 2D image. Keep mobile and reduced-motion support.

## Performance and accessibility
Static HTML/CSS/vanilla JS, no heavy game engine. Keep ember canvas capped to ~54 particles, DPR <= 1.5, no scroll-jacking, pause/limit nonessential motion for prefers-reduced-motion. Keep focus states, keyboard navigation and semantic headings. Use lazy/reveal transitions only where helpful.

## Content integrity
Never invent employment, dates, education, certifications, metrics, testimonials, clients or outcomes. Never claim RDP / remote desktop experience. Use “nearly five years”, not “5+ years”. Keep UWP S1 in progress. Project statuses: ERP Multi Talent — In Development; Fun Run UWP — Development / Prototype; Finova — UI/UX Prototype (Auto-Split frontend simulation); Greedy Nearest Neighbor — Academic Project.

## Technical / Git safety
GitHub Pages-compatible relative paths. Preserve CV pages and all current assets. No secrets, .env, private keys, DB dumps. Do not delete files, alter repository settings or force-push. Main only.