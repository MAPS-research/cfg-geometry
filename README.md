# Learning to Be Guided: project page

Static single page. No build step.

- `index.html`: all content, styles (top `<style>` block, color and font tokens in `:root`) and scripts.
- `assets/fig2.png`: Figure 2 from the manuscript. Replace with a transparent PNG or SVG export of the same name to match the page background.

Preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.

External dependencies (loaded from CDN): Google Fonts (IBM Plex Sans, IBM Plex Mono, Source Serif 4) and MathJax 3.2.2. Equations are written as TeX inside `\( \)` and `\[ \]`.

The interactive toy is the second `<script>` block at the end of the file. Key constants: `K` (classes), `D` (scale), `A1` (fixed alpha of the entangled row); the adjustable row's default alpha is the `value` of the `#a2` slider (log10).
