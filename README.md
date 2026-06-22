# ascii-bridge

Interactive demonstration: a language model **authors** ASCII art of a subject from its name
alone, then an image-to-image diffusion bridge is applied along a denoise ladder. In
`gemini-embedding-2` space we measure how far each stage travels toward a real photograph of
the subject — and find the bridge rescues even the crudest machine glyph-art (1/9 → 9/9 correct
subject) into the right photoreal image.

**Live:** https://tinycrops.github.io/ascii-bridge/ — drag the slider.

Static site (no backend). Frontend in `frontend/`, deployed to GitHub Pages by
`.github/workflows/pages.yml`.
