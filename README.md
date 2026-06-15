# MaMoTo – Mathematical Modelling Tool

MaMoTo is a browser-based workspace for mathematical modelling. It provides an infinite, pannable canvas on which users arrange content cards — text, sketches, voice notes, and 3D models — to document and structure their modelling process.

## Project Status

**Prototype running.** The main modelling workspace (`mathmodel-v0.4.html`) is functional. The 3D editor (`3dmodule-v0.1.html`) has been separated into its own development harness due to its complexity and will be reintegrated into the main tool once it is ready.

## Files

| File | Description |
|------|-------------|
| `mathmodel-v0.4.html` | Main modelling workspace (current prototype) |
| `3dmodule-v0.1.html` | 3D editor — standalone dev harness |
| `example.json` | Example project data for testing and demonstration |

## Features

- Infinite canvas with pan and zoom
- Grid-based card layout for organising modelling steps
- Content types: text, sketches, 3D models, voice notes
- Media library sidebar for managing created assets
- Project save/load via JSON

## Tech Stack

- Vanilla JavaScript (ES modules), no build step required
- [Three.js](https://threejs.org/) v0.160.0 for 3D rendering
- Google Fonts: DM Serif Display, DM Mono, Instrument Sans

## Usage

Open `mathmodel-v0.4.html` directly in a browser. No server or installation needed.
