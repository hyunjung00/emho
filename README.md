# EMHO project page

Project website for **EMHO: EMbodied Agent Harness Optimization via Experience Traces**.

This static page contains the author list and affiliations, two episode-comparison videos directly below the title, a single-column abstract, the framework overview, main and shared-harness results, and qualitative analysis figures. It uses a white background, one sans-serif font stack, and restrained navy/blue accents. Navigation and manipulation videos sit side by side on larger screens and stack on phones. All result tables are always visible and fit the page without horizontal scrolling. arXiv and Code links are marked Coming soon.

## Local preview

Run `python3 -m http.server 8765` in this folder, then open `http://localhost:8765`.

## GitHub Pages

Publish this repository from the `main` branch and root (`/`) folder in **Settings → Pages**. No dependencies or build command are needed.

## Editing

- `index.html`: text, author list, table, and resource buttons.
- `style.css`: page layout and styling.
- `overview.webp`, `recovery.webp`, and `behaviors.webp`: figures from the paper.
- `assets/videos/manipulation.mp4`: spatial manipulation, episode 39; initial harness on the left and evolved harness on the right.
- `assets/videos/navigation.mp4`: long-horizon navigation, episode 43; initial harness on the left and evolved harness on the right.
- `assets/videos/*-poster.jpg`: poster frames for the two videos.

The 204 numeric results and bold formatting in the two main benchmark tables are preserved from the paper. Additional shared-harness comparisons are drawn from Table 3. Main EMHO scores are split-wise maxima over 10 optimization iterations; search and held-out maxima can occur at different iterations. Held-out results are retrospective summaries, not a single search-selected harness's generalization estimate. Held-out scores and trajectories are not supplied to the optimizer.

The supplied videos are silent H.264 MP4 files with web-compatible pixel format and faststart metadata. Native playback controls and inline mobile playback are enabled, with no autoplay. The source videos were losslessly remuxed; the imagery was not recompressed.

The website code is newly authored, with design inspiration from [CounterCurate](https://countercurate.github.io/).
