# EMHO project page

Project website for **EMHO: EMbodied Agent Harness Optimization via Experience Traces**.

This static page contains the author list and affiliations, the framework overview, the abstract, the paper’s complete main results table, and qualitative analysis figures. arXiv and Code links are marked Coming soon.

## Local preview

Run `python3 -m http.server 8765` in this folder, then open `http://localhost:8765`.

## GitHub Pages

Publish this repository from the `main` branch and root (`/`) folder in **Settings → Pages**. No dependencies or build command are needed.

## Editing

- `index.html`: text, author list, table, and resource buttons.
- `style.css`: page layout and styling.
- `overview.webp`, `recovery.webp`, and `behaviors.webp`: figures from the paper.

All 204 numeric results and the bold formatting match the paper’s main table. EMHO scores are split-wise maxima over optimization iterations; search and held-out maxima can occur at different iterations.

The website code is newly authored, with design inspiration from [CounterCurate](https://countercurate.github.io/).
