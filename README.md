# VWP Monitoring Dashboard — Nui Phao

Standalone HTML dashboard for vibrating-wire piezometer monitoring at the Nui Phao mine.

## Open

Open `index.html` in a modern browser. The dashboard works offline and includes its data in the HTML file.

## Data source

Data was prepared from `East Open Pit - Piezometers (updating).xlsx` in the VWP project folder. The page groups sensors from the same borehole, matching the original Excel charts: VWP1-1, VWP1-2, and VWP1-3 are shown together, while VWP2-1 and VWP2-2 form the second group. It also includes rainfall from `Precipitation`. Latest VWP reading: 1 October 2026.

To refresh the dashboard, rebuild the embedded data from the latest workbook and replace `index.html`.
