# Temp_Code_2

A small React + TypeScript data-visualization app (originally published as "bank-merge-co-task-2").

## What this repository is
This project is a frontend that visualizes tabular/time series data using React and Perspective libraries from JPMorgan. It loads sample data from `test.csv` and displays interactive charts/components located in `src/`.

## Tech stack
- React (create-react-app)
- TypeScript / TSX
- @jpmorganchase/perspective and perspective-viewer-highcharts
- react-scripts

## Quick start
1. Install dependencies:
   ```
   npm install
   ```
2. Run the app locally:
   ```
   npm start
   ```
3. Open http://localhost:3000

## Important files
- `package.json` — project dependencies and scripts.
- `src/` — main application code:
  - `src/App.tsx` — application entry / layout.
  - `src/Graph.tsx` — graph/visualization component.
  - `src/DataStreamer.ts` — data loading/streaming logic.
- `test.csv` — sample data used by the app.

## Notes about languages
Although GitHub may report the repository language as Python in some views, the codebase under `src/` is primarily TypeScript/JavaScript. You can update language detection by adding a `.gitattributes` to mark or exclude large non-source files.

## Next steps / suggestions
- Add this README to the repository (or let me add it for you).
- Add a LICENSE file and minimal contributing instructions if you want to share the project.
- Optionally add a short architecture or data-flow diagram and sample screenshots.
