# Miller Indices Visualizer — v3

A simple, standalone browser app for exploring crystal structures, Miller planes, and atomic stacking.

## Run it

Open `index.html` in a modern browser. No installation, external libraries, downloads, build step, or server is required.

## Version 3 features

- Simple Cubic (SC), Body-Centred Cubic (BCC), Face-Centred Cubic (FCC), and Hexagonal Close-Packed (HCP) views
- Visible coordinate axes, with a/b/c labels for HCP and x/y/z for cubic cells
- Drag to rotate the crystal
- Zoom in/out buttons and mouse-wheel zoom
- Light, Dark, and Sepia themes
- Separate **Miller Planes** and **Stacking Explorer** tabs in the same HTML file
- Layer-by-layer teaching views for BCC, FCC, and HCP stacking
- Responsive layout for desktop and mobile

## Scientific notes

This is a lightweight educational illustration rather than a full crystallographic simulation. The HCP cell includes visible top and bottom boundary sites and middle-layer interior sites. Its Miller-plane input remains a simplified three-index illustration; proper HCP crystallography commonly uses four-index Miller–Bravais notation. The stacking tab illustrates BCC alternating planes and the close-packed FCC (ABCABC) and HCP (ABAB) sequences.

## File

- `index.html` — the complete app with all HTML, CSS, and JavaScript included.
