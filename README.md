# 150226

## Energy dashboard flow
- Import `dashboard.json` into Node-RED Dashboard 2 (`/dashboard` path) for the energy meter view.
- Use the per-graph start/stop buttons to pause or resume chart updates and the zoom ± buttons to refine the timeline.
- Logged samples appear in the table with timestamps; `Export CSV` writes `/tmp/energy-data-log.csv` and `Clear log` resets the table.
