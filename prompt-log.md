- Initial Prompt
"You are a Senior Humanitarian Data Analyst. I have attached the official West & Central Africa Cadre Harmonisé (CH) food security dataset. Filter this data to 'Nigeria' (adm0_name == 'Nigeria'). For the latest recorded exercise year, identify the top 5 states (adm1_name) with the highest population in Phase 3–5 (phase35) and generate a summary table and a bar chart comparing them."

- Prompt for the finalized clean_nigeria_food_security.csv:
Filter this dataset strictly where adm0_name == 'Nigeria'. Select only the following columns: adm1_name, adm2_name, exercise_year, exercise_label, chtype, population, phase_class, phase1, phase2, phase3, phase4, phase5, phase35.

Next, engineer two new calculated columns: 
- crisis_percentage: (phase35 / population) * 100 rounded to 1 decimal place.
- severity_label: Map phase_class (1 = 'Phase 1: Minimal', 2 = 'Phase 2: Stressed', 3 = 'Phase 3: Crisis', 4 = 'Phase 4: Emergency', 5 = 'Phase 5: Famine').

Sort by exercise_year (descending) and phase35 (descending), and export as a clean CSV.
