# flaught.github.io

Source for the Flaught home page, served at https://flaught.github.io via GitHub Pages (static, from `main` root).

- `index.html` — the page (self-contained, no build step, no Jekyll).
- `assets/flaught-demo.gif` — the demo recording (a copy of the one in `flaught/core`).
- `assets/social-preview.png` — used as the Open Graph image.

To preview locally:

```bash
python3 -m http.server --directory .
```

Content/voice matches `flaught/core`'s README — dry, precise, epistemically honest. Edits are direct to `main`; Pages rebuilds on push.