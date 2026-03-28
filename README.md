<div align="center">

# `{ }` Awesome Claude Code Projects

### פרוייקטים אדירים עם קלוד קוד

**A curated showcase of mind-blowing projects built with [Claude Code](https://claude.ai) — presented in a glassmorphism Hebrew collage with live boid particles.**

[![Live Site](https://img.shields.io/badge/LIVE%20SITE-bjbodner.github.io-39E0CE?style=for-the-badge&logo=github&logoColor=white)](https://bjbodner.github.io/awesome-claude-code-projects/)
[![License: MIT](https://img.shields.io/badge/License-MIT-EF00A3.svg?style=for-the-badge)](./LICENSE)

<br/>

<img src="https://s.wordpress.com/mshots/v1/https%3A%2F%2Fbjbodner.github.io%2Fawesome-claude-code-projects%2F?w=1200&h=630" alt="Screenshot" width="720" />

</div>

---

## What is this?

A single HTML file that somehow contains:

- **17 awesome Claude Code projects** showcased in beautiful glassmorphism cards
- **200 boid particles** doing their best flocking-bird impression behind everything
- **Full RTL Hebrew layout** because why not make it harder
- **3D tilt effects** on hover because flat cards are boring
- **Animated gradient borders** that glow like they're radioactive
- **Zero dependencies** — no npm, no webpack, no node_modules black hole

The whole thing is one `index.html` file. Yes, really. The CSS, the JavaScript, the boid flocking algorithm, the particle system, all 17 project cards — it's all in there. Ship it anywhere.

## Features

| Feature | Description |
|---|---|
| **Glassmorphism Cards** | Semi-transparent frosted glass cards with blur — particles swim behind them |
| **Boid Particle System** | 200 particles with cohesion, alignment, separation, and mouse fleeing behavior |
| **Dark Mode Glass** | Dark navy background with translucent hero, cards, and footer |
| **3D Hover Tilt** | Cards tilt toward your cursor with perspective transforms |
| **Smart Thumbnails** | WordPress mshots API for live website screenshots |
| **Fully Responsive** | 3 columns → 2 → 1 with smooth breakpoints |
| **RTL Hebrew** | Right-to-left layout with Open Sans Hebrew font |
| **Zero Build Step** | Open the HTML file. That's it. That's the build step. |

## Quick Start

```bash
# Option A: Just open the file
open index.html

# Option B: Serve it locally
python3 -m http.server 8080

# Option C: Deploy it
# Push to GitHub → enable Pages → done
```

## Want to add a project?

Find the `PROJECTS` array in the `<script>` tag and add an object:

```javascript
{
  title: "שם הפרויקט בעברית",
  description: "תיאור קצר של מה שהפרויקט עושה",
  url: "https://example.com",
  imageUrl: "https://example.com",  // used for thumbnail generation
  type: "אפליקציה"                  // badge label
}
```

That's it. The card renders itself. No config, no rebuild, no drama.

## The Boid Particle System

The background particles use Craig Reynolds' [boid flocking algorithm](https://en.wikipedia.org/wiki/Boids) with three simple rules:

1. **Cohesion** — steer toward the average position of nearby boids
2. **Alignment** — match the average velocity of nearby boids
3. **Separation** — avoid crowding neighbors

Plus a bonus rule: **flee from the mouse cursor** because boids have a healthy sense of self-preservation.

Each particle has a unique color from a curated HSL palette (cyans, magentas, and golden accents) with varying alpha. They render on a fixed canvas behind all content, visible through the semi-transparent glass cards.

## Tech Stack

- **HTML** — 1 file
- **CSS** — embedded, ~370 lines of handcrafted glass
- **JavaScript** — embedded, boid physics + DOM rendering
- **External services** — Google Fonts (Open Sans), WordPress mshots (thumbnails)
- **Frameworks used** — 0
- **node_modules** — doesn't exist and never will

## Made With

Built by **[Benjy Bodner](https://github.com/BjBodner)** from **[LetsAI](https://letsai.co.il)** using Claude Code — because the best way to showcase Claude Code projects is with a Claude Code project.

## License

[MIT](./LICENSE) — do whatever you want with it.

---

<div align="center">

**[View Live Site](https://bjbodner.github.io/awesome-claude-code-projects/)**

*If you built something cool with Claude Code, open a PR and add it!*

</div>
