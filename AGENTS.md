# CODING AGENTS: READ THIS FIRST

This repository started as a **handoff bundle** from Claude Design (claude.ai/design).

A user mocked up designs in HTML/CSS/JS using an AI design tool, then exported the bundle so a coding agent could implement the designs for real.

## Status

- `index.html` (Overview page) — **implemented** at the repo root, deployed via GitHub Pages.
- `project/*.html` (Collage, Studio, Events, Design, Contact) — **still raw design prototypes**, not yet polished into production pages.

A future agent's likely job is to take the remaining prototypes in `project/` through the same treatment.

## What you should do — IMPORTANT

**Read `project/index.html` in full** as the reference design (it's the source the implemented `index.html` was built from). Read it top to bottom — don't skim. Then **follow its imports**: open every file it pulls in (shared components, CSS, scripts) so you understand how the pieces fit together before you start implementing.

**If anything is ambiguous, ask the user to confirm before you start implementing.** It's much cheaper to clarify scope up front than to build the wrong thing.

## About the design files

The design medium is **HTML/CSS/JS** — these are prototypes, not production code. Your job is to **recreate them pixel-perfectly** in whatever technology makes sense for the target codebase (React, Vue, native, whatever fits). Match the visual output; don't copy the prototype's internal structure unless it happens to fit.

**Don't render these files in a browser or take screenshots unless the user asks you to.** Everything you need — dimensions, colors, layout rules — is spelled out in the source. Read the HTML and CSS directly; a screenshot won't tell you anything they don't.

## Bundle contents

- `README.md` — public-facing project description
- `AGENTS.md` — this file
- `index.html` — implemented Overview page (built from `project/index.html`)
- `project/` — the original `ALE - PORTFOLIO` design bundle (HTML prototypes, assets, components)
