# Angry Birds Physics (Grade 12 Mechanics Simulation)

A browser-based **Angry Birds–style physics lab** built as a **Grade 12 mechanics simulation**. You launch a bird with a slingshot, try to destroy all pigs, and (most importantly) see the underlying physics update live—projectile motion, Hooke’s law (spring), work–energy, and collision/impulse concepts.

This project is packaged as a simple, single-file experience: open the HTML file in a browser and start experimenting.

---

## What this project is

This isn’t meant to be a full commercial Angry Birds clone. It’s a **destructive physics sandbox** designed to make core high-school physics ideas feel interactive:

- Pull back a slingshot (spring)
- Release and watch projectile motion (with wind/gravity effects)
- Collide with targets (impulse/energy transfer)
- Track “win” progress by destroying pigs

---

## Key learning concepts visualized

The UI is built around real-time readouts so you can connect gameplay to equations:

### Projectile Motion
Live stats update as you aim and launch, including:
- launch angle (θ)
- initial speed (v₀)
- max range (R)
- peak height (H)
- flight time (T)

### Hooke’s Law (Slingshot / Spring)
As you stretch the slingshot:
- displacement (d)
- max force (F_max)
- average force (F_avg)
- work done by the spring
- elastic potential energy (½kx²)
- oscillation period

### Work–Energy
The simulation surfaces energy components such as:
- kinetic energy (½mv²)
- gravitational potential energy (mgh)
- total system energy
- work done (ΔE framing)

### Collision Physics
On impacts, it reports collision-related quantities like:
- impulse (Δp = FΔt)
- impact energy
- (plus an angular momentum reference shown in the UI)

---

## Gameplay / interaction

- **Goal:** destroy all pigs to win the level.
- **Core mechanic:** drag the bird back to set the launch, then release to fire.
- **Levels:** includes a “Next” flow to move through scenarios/levels.

---

## Controls & shortcuts

The simulation includes built-in hotkeys for faster testing:
- **P**: Pause
- **R**: Reset
- **N**: Next level
- **H**: Toggle hitboxes
- **S**: Toggle sidebar

---

## Physics parameters you can change

The sidebar exposes key variables so you can run “what-if” experiments:
- **Gravity (g)**
- **Spring constant (k)**
- **Mass (m)**
- **Wind**

It also includes quick presets (e.g., *Zero‑G*, *Heavy*) to instantly demonstrate how the same launch behaves under different conditions.

---

## What’s in this repository

- A single main HTML file containing the simulation experience.
- Minimal repository structure (no build system required).

This makes it easy to share as a standalone demo and to run locally without installing anything.

---

## Limitations / notes

- This is an educational simulation and uses simplified modeling choices to keep it interactive and understandable.
- This project is inspired by Angry Birds–style mechanics, but it is not an official Rovio product.
- No license file is included yet—add one if you plan to reuse/distribute it broadly.

---

## Suggested next improvements (if you want to expand it)

- Add a short “teacher mode” with guided prompts (e.g., *predict the range before launching*)
- Add experiment logging (save parameter sets + results)
- Add more levels focused on specific concepts (pure projectile, pure energy, pure impulse, etc.)
- Add a small results export (CSV/PDF) for lab submissions
