# OilTrace — Team AlgoRise

Technical report for **Smart India Hackathon 2026, Problem 26143**.

OilTrace turns a single satellite observation of an oil slick into a four-stage
investigation: SAR detection, a backward OpenDrift/OpenOil hindcast to a probable
source region, deterministic AIS attribution, and a forward counterfactual that
tests whether each candidate could actually reproduce the observed slick.

## Contents

| File | Description |
|---|---|
| `index.html` | The full technical report. Self-contained: 13 inline SVG diagrams and charts, no build step, no JavaScript. |

## Viewing

Open `index.html` in any browser.

To publish it on the web, enable **GitHub Pages** in Settings → Pages, serving
from the `main` branch root. The report is then served at the Pages URL.

To produce a PDF, open the file in Chrome and print to PDF with
**Background graphics** enabled so the tinted tables and diagram fills survive.

## Report sections

1. Executive summary
2. Problem and context
3. The investigation loop
4. System architecture
5. Stage 1 — SAR detection
6. Stage 2 — Backward hindcast
7. Stage 3 — AIS attribution
8. Stage 4 — Forward counterfactual
9. Replay and visualization
10. API contract
11. Data model
12. Demonstration walkthrough
13. Reliability engineering
14. Validation and results
15. Limitations
16. Comparison to prior work
17. Roadmap
18. Reproducibility

Appendices: metrics and model maturity, glossary, references.
