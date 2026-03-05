# Innovent Executive Dashboard

Static executive control dashboard for Innovent Ops. Built and maintained by Leila Rhodes.

## Contents
- `index.html`: redirect shim so the root URL forwards to the live dashboard.
- `dashboard.html`: primary dashboard single-page app (no external build step, pure HTML/CSS/Chart.js).

## Hosting
Published via GitHub Pages from the `main` branch. Any commit to `main` automatically updates the public dashboard URL.

## Update Protocol
1. Edit `dashboard.html` in the workspace.
2. Run `npm test` (if future validation scripts are added) or simple HTML lint.
3. Commit changes and push to `main`.
4. Confirm that GitHub Pages redeploys (typically < 60 seconds).

Last major refresh: 2026-03-05 — new color system, expanded KPI set, and additional charts (velocity, pipeline, channel mix, radar follow-ups).
