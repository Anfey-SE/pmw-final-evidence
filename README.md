# PMW Internship — Final Evidence Page

Final portfolio and certificate evidence page for the PreserveMy.World × TechRealm internship, Platform & Web Engineering track, Team Indus.

**Live site:** [https://pmw-final-evidence.vercel.app/]

## What this is

A single-page evidence record tying together every module of the internship — artifacts, module-by-module status (graded / pending review / excluded), verified attendance hours, a personal reflection, and next steps. Built to be readable by a certificate reviewer in under two minutes, with every claim linking directly to real proof.

The design is intentionally built around PreserveMy.World's own visual language (deep ink-teal base, calm typography, evidence-first tone) rather than reusing the look of my other PMW artifacts, since this page represents the whole internship rather than one project.

## Sections

- **Hero** — name, track, team, and an honest status line (graded vs. pending)
- **The Artifacts** — glass-card index of the six strongest deliverables, each linking to the live/deployed proof
- **Module Log** — all 30 modules mapped individually, with status badges (Graded, Pending Review, Excluded, In Progress). Module 3 (an ungraded icebreaker task) is explicitly marked rather than omitted.
- **The Ledger** — real certificate attendance hours (36h 30m of a 50h target, as shown on the PMW dashboard at time of writing)
- **Field Journal** — a first-person reflection on what the internship actually taught me
- **What's Next** — concrete follow-up work planned on the underlying artifacts
- **Closing** — direct links to LinkedIn, GitHub, and DEV.to

## Tech stack

- Vanilla HTML/CSS/JS, no build step
- Canvas-based ambient particle field ("fireflies") and static topographic contour lines, both respecting `prefers-reduced-motion`
- Deployed via Vercel

## Run locally

No build step required — clone and open `index.html` in a browser, or serve the folder:

```
git clone https://github.com/Anfey-SE/pmw-final-evidence.git
cd pmw-final-evidence
python3 -m http.server 8000
# then open http://localhost:8000
```

## Role & context

Built by Amna Hafeez (Team Indus) as the final deliverable of the PMW × TechRealm internship, Platform & Web Engineering track — closing out ten weeks of work across ML, AR/3D visualization, and heritage documentation tooling.
