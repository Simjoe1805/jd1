# Coding Instruction and Code Map

## Purpose of This File
This document tracks every important project file, what it does, and why it exists.
Update this file whenever you add, remove, or significantly change code.

## How to Use
1. Before coding: check this file to see the current architecture.
2. After coding: update the relevant row and changelog section.
3. Keep descriptions simple so the project stays readable over time.

## File Inventory (Current)
| File | Type | Purpose | Status |
|---|---|---|---|
| `.gitattributes` | Git config | Normalizes text files and line endings. | Active |
| `README.md` | Documentation | Explains project vision, emotional intent, and high-level structure. | Active |
| `prd.md` | Documentation | Defines product requirements, user flow, and acceptance criteria. | Active |
| `codinginstruction.md` | Documentation | Tracks code files and responsibilities for maintainability. | Active |
| `index.html` | Frontend markup | Hosts the interactive scene flow, narrative text, and inline MVP logic for navigation and parallax. | Active |
| `style.css` | Frontend styles | Controls first person visual atmosphere, animation, transitions, and responsive layout. | Active |

## Planned Implementation Files
| File | Type | Purpose | Status |
|---|---|---|---|
| `app.js` | Frontend logic | Handles scene progression, input handling, and runtime effects. | Planned |
| `assets/images/*` | Media assets | Stores scene backgrounds, overlays, and symbolic visual elements. | Planned |
| `assets/audio/*` | Media assets | Stores ambient loops and scene transition audio. | Planned |

## Suggested Code Responsibilities
1. `index.html`
   - Define scene wrapper structure.
   - Include semantic containers for narrative text and controls.
2. `style.css`
   - Implement first person illusion effects (layer depth, parallax cues, fades).
   - Implement responsive layouts for mobile and desktop.
3. `app.js`
   - Manage scene state index.
   - Advance or replay scenes on click, tap, or keyboard input.
   - Trigger scene-specific animations and optional audio events.

## Naming Conventions
1. Use lowercase kebab-case for CSS classes and IDs where possible.
2. Use descriptive JavaScript names (example: `currentSceneIndex`, `goToNextScene`).
3. Keep scene data grouped in arrays or objects for easy editing.

## Update Rules
1. Add every new code file to the inventory table.
2. If a file purpose changes, update its purpose text immediately.
3. If a file is deprecated, mark status as `Deprecated` and note replacement.

## Change Log
- 2026-05-21: Created initial documentation map for the project and planned implementation files.
- 2026-05-21: Added `index.html` and `style.css` as active MVP implementation files.
