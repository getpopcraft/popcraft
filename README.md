<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/media/wordmark-white.png">
  <img src=".github/media/wordmark.png" alt="PopCraft" width="380">
</picture>

### The design tool that actually pops.

Vector UI, raster painting, pixel art, comic pages and whiteboards — all in one file, all drawn on the GPU.

[![Download](https://img.shields.io/github/v/release/getpopcraft/popcraft?label=download&style=for-the-badge&color=EC008C)](https://github.com/getpopcraft/popcraft/releases/latest) [![macOS](https://img.shields.io/badge/macOS-12%2B-231F20?style=for-the-badge)](https://github.com/getpopcraft/popcraft/releases/latest) [![Open in browser](https://img.shields.io/badge/or%20just%20open-popcraft.app-FFED00?style=for-the-badge&labelColor=231F20)](https://popcraft.app)

</div>

<br>

<div align="center">
  <img src=".github/media/editor-design.png" alt="The PopCraft editor with a landing page open" width="900">
</div>

<br>

## ⚡ Get it

**Mac app** — grab the `.dmg` from **[the latest release](https://github.com/getpopcraft/popcraft/releases/latest)**, open it, drag PopCraft to Applications. Apple silicon, macOS 12 or later.

**Or don't install anything** — [popcraft.app](https://popcraft.app) runs the whole thing in a browser. Any browser with WebGPU: recent Chrome, Edge or Safari.

The desktop app adds tabs (one file per tab, each in its own process), and loads plugins, widgets, fonts, themes and agent skills straight out of local folders.

<br>

## 💥 What's in it

### ✏️ SWOOSH! — Design & prototype

Frames, auto layout, real components with variants, styles and variables. Wire screens together into something clickable, then hand it off with CSS, React, Tailwind, SwiftUI or Compose.

<img src=".github/media/prototype.png" alt="Prototype mode with connections between frames" width="49%"><img src=".github/media/dev-mode.png" alt="Dev mode inspecting a layout" width="49%">

### 🎨 SPLAT! — Paint

93 brushes across 13 groups — pencils, inkers, calligraphy, oils, watercolour, airbrush, spraypaint, halftone grit. Pressure and tilt, stroke stabilization, perspective and isometric guides.

**Bring your own:** Procreate `.brush` and `.brushset` files import straight in.

<img src=".github/media/draw-mode.png" alt="Draw mode with the brush library open" width="900">

### 👾 BEEP! — Pixel & sprite studio

A full sprite editor living inside your design file. Indexed palettes (PICO-8, DB32, Endesga 32, Game Boy), pixel-perfect strokes, symmetry, frames with onion skin, and tilemaps.

Export a GIF or a game-ready sprite sheet with an Aseprite-compatible atlas.

<img src=".github/media/pixel-art.png" alt="A sprite open in the pixel editor" width="900">

### 💬 KRA-KOOM! — Comics

Not a template pack. Real trim sizes the direct market prints at, panels that are actual masks, balloons with tails that point, spreads that know they're two pages on one sheet — and a live GPU halftone that exports to SVG as vector dots.

Thirty-three page layouts ship with it, from a nine-panel grid to a pulp cover.

<img src=".github/media/comic-page.png" alt="A six-panel comic page in the editor" width="900">

### 🗣️ HEY! — Multiplayer

Live cursors, follow and spotlight, threaded comments with @mentions, version history with named versions, and branches. Edits merge instead of overwriting.

### 🎉 BAM! — Whiteboards

**PopCorn** boards are the same canvas in another mode: stickies, washi tape, stamps, a timer and dot voting. When the workshop's over, switch to Design and keep going in the same file.

<img src=".github/media/board.png" alt="A brainstorm board" width="900">

### 🧩 KLIK! — Plugins & API

Build commands, side panels and interactive canvas widgets, publish them to the marketplace, or drive the whole thing over the REST API. Reskin the editor with a theme.

→ [Example plugins](https://github.com/getpopcraft/plugins) · [Plugin docs](https://popcraft.app/docs/plugins) · [REST API](https://popcraft.app/docs/api)

<br>

## 🎬 Also in the box

|  |  |
| --- | --- |
| **Templates** | Business cards, brochures, posters, resumes, slides, social, email, web, app, boards, comics |
| **Print** | Bleed, fold guides, imposition, booklets, preflight, CMYK PDF, CSV bulk-create |
| **Animation** | Build-in animations, a keyframe timeline, smart animate, springs |
| **Export** | PNG · JPG · WebP · SVG · PDF · GIF · MP4 · PPTX · sprite sheets · code |
| **Effects** | Shader fills, progressive blur, glass, noise, texture, halftone — live on the GPU |
| **Type** | Variable fonts, OpenType features, text on a path, your own font files |

<br>

## 📚 Docs

Everything is at **[popcraft.app/docs](https://popcraft.app/docs)** — [getting started](https://popcraft.app/docs/getting-started) · [designing](https://popcraft.app/docs/designing) · [drawing](https://popcraft.app/docs/drawing) · [pixel art](https://popcraft.app/docs/pixel-art) · [comics](https://popcraft.app/docs/comics) · [boards](https://popcraft.app/docs/boards) · [prototyping](https://popcraft.app/docs/prototyping) · [exporting](https://popcraft.app/docs/exporting) · [collaborating](https://popcraft.app/docs/collaborating).

<br>

## 🤔 About this repository

This repo is where the **desktop releases** live — the builds, and nothing else. PopCraft isn't open source, so there's no application code here.

- **Something broken?** [Open an issue](https://github.com/getpopcraft/popcraft/issues) or head to [support](https://popcraft.app/support).
- **Building a plugin?** The examples and API types are at [getpopcraft/plugins](https://github.com/getpopcraft/plugins).
- **Press kit?** [popcraft.app/press](https://popcraft.app/press).

Use of PopCraft is covered by the [Terms of Service](https://popcraft.app/legal/terms) and the [Privacy Policy](https://popcraft.app/legal/privacy) — see [TERMS.md](TERMS.md).

<div align="center">
<br>
<sub>Made with WebGPU, and an unreasonable number of halftone dots.</sub>
</div>
