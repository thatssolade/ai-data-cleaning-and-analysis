# Predictive Food Security & Crisis Analysis (Cadre Harmonisé / IPC)

A generative AI-driven analysis of UN Cadre Harmonisé humanitarian data tracking acute food insecurity across 14,000+ Nigerian administrative records from 2015 to 2026.

## Objective
Extract actionable regional crisis alerts, calculate population severity ratios, and forecast seasonal food stress across Nigerian states using prompt-assisted data pipelines.

## Stack & Data Source
- **Data Source:** Cadre Harmonisé / IPC West & Central Africa Dataset 
- **Tools:** Gemini (Google AI workflow), Google Sheets, Python
- **Key Metrics:** IPC Phase 3–5 Population, Coping Strategy Indices (rCSI), Projected Severity Delta

## Key Findings
- **High-Risk Zones:** Identified key LGAs in the North-East and North-West where projected Phase 3+ populations surged by over 25% year-over-year.
- **Seasonal Delta:** Projected acute food insecurity peaks consistently between June and August (lean season) across monitored agricultural zones.

## Repository Contents
- `data/`: Contains raw vs. clean dataset exports.
- `prompt-log.md`: Step-by-step breakdown of system prompts used for transformation.

## Key Insights Uncovered

- **Geographic Concentration of Crisis (Phase 3–5):**

The highest populations in acute food insecurity cluster in northern states (such as Borno, Kaduna, Katsina, Kano, Zamfara, and Sokoto), alongside high urban caseloads in Lagos due to sheer population density.

- **Seasonal Vulnerability (Lean Season Spike):**

The Jun-Aug (lean season) assessment cycles show consistent 15%–30% spikes in phase35 populations compared to post-harvest (Sep-Dec) assessments.

- **Emergency (Phase 4) Pockets:**

Tracking the phase4 indicator isolates specific LGAs in conflict-affected regions that have crossed into critical humanitarian emergency thresholds.
