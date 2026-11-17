# sethulakshmisanthosh.github.io

My personal site — product analytics and data science.

**Live:** https://sethulakshmisanthosh.github.io
**Editable version (Claude artifact):** https://claude.ai/artifact/X9wz2n7XgggG4smu1ap3cu

## What's here

One static page, no build step and no dependencies to install.

| File | What it is |
|---|---|
| `index.html` | The whole site — markup, styles and scripts in one file |
| `photo.webp` | Portrait used in the hero |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

The page is a single dark theme by design. It uses Instrument Serif, Manrope and
JetBrains Mono from Google Fonts; everything else is hand-written — the particle
field behind the hero is Canvas 2D, the project pop-ups are native `<dialog>`
elements, and every animation is skipped when the visitor has reduced motion
turned on.

## Sections

- **Hero** — an A/B switch that reframes the same person two ways
- **Experiment** — a small A/B test simulator you can actually run
- **Work** — selectable project cards; the detail and the numbers live inside the pop-ups
- **Story** — background, the path so far, and what I do outside work
- **Contact**

## Editing it

```bash
git clone https://github.com/SethulakshmiSanthosh/SethulakshmiSanthosh.github.io.git
cd SethulakshmiSanthosh.github.io
open index.html          # it runs straight from the file system
```

Push to `main` and GitHub Pages redeploys in under a minute.

Project content lives in the `W` array near the top of the script block in
`index.html` — one object per project, with its title, summary, bullet points
and tools. Add or reorder entries there and the gallery, the filters and the
pop-up navigation all follow.
