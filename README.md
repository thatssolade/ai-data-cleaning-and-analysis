# Nigeria Acute Food Security & Crisis Analysis (2015–2026)

An empirical data analysis project utilizing Generative AI (Gemini) and Python to parse, clean, and analyze over 14,700 UN Cadre Harmonisé (CH) / IPC humanitarian records across 28 Nigerian states and 668 LGAs.

## Problem Statement
Humanitarian datasets from international monitoring bodies often span multiple countries, dozens of sparse survey metrics, and unstandardized severity classes. This project demonstrates how to structure, filter, and extract regional crisis indicators using prompt-assisted data workflows.

## Objective
Extract actionable regional crisis alerts, calculate population severity ratios, and forecast seasonal food stress across Nigerian states using prompt-assisted data pipelines.

## Stack & Methodology
- **Data Source:** UN Cadre Harmonisé / Integrated Food Security Phase Classification (IPC)
- **Tools:** Gemini (Google AI Workflow), Google Sheets, Python (`pandas`, `matplotlib`, `seaborn`)
- **Key Engineered Features:**
  - `crisis_percentage`: `(phase35 / population) * 100` (Acute crisis ratio)
  - `severity_label`: Natural language classification mapping numerical phase codes to standardized humanitarian tiers (Phase 1–5).

## Key Findings
- **Crisis Epicenters:** Borno (3.78M), Kaduna (3.27M), and Katsina (3.25M) record the highest aggregate populations in Phase 3–5 (Crisis/Emergency).
- **Urban Food Stress:** High population density and urban inflation in Lagos account for over 2.69M individuals in Phase 3+ food stress.
- **Emergency Pockets:** Isolated 17 local government assessment units in critical Phase 4 (Emergency) requiring targeted intervention.

## Repository Structure
- `data.md`: Contains raw multi-country source data and the prompt-cleaned Nigeria subset (`Tracking Acute Food Insecurity & Crisis Projections in Nigeria (2015–2026) - Nigeria_Analysis.csv`).
- `prompt-log.md`: Natural language prompting sequence used for data slicing and formula generation.
- `visuals.md`: Multi-year trend lines and state-level bar charts.

## Strategic & Humanitarian Recommendations
1. **Targeted Aid Allocation:** Prioritize early relief staging in Kala/Balge, Mobbar, and Bama, where acute crisis levels exceed 60% of total LGA populations.
2. **Urban Safety Nets:** Expand subsidized food access in high-density consumer hubs (e.g., Alimosho, Lagos) to counter inflation-driven urban Phase 3 spikes.
3. **Lean-Season Early Warning:** Schedule buffer stock distributions prior to the June–August window to mitigate the historical 25%+ projected lean-season deterioration.
