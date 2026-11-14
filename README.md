# neuracare-primary-survey

## Overview
This repository contains original primary research data collected via a digitized mental health risk assessment deployment across university student cohorts ($N = 260$). This dataset was independently gathered and curated to serve as primary empirical evidence for psychological risk assessment research.

## Dataset Structure & Features
The dataset is provided in RFC 4180 compliant CSV format (`neuracare_primary_survey.csv`) with **260 rows and 52 columns**:

- **Identifier & Demographics:**
  - `Respondent_ID`: Anonymized participant identifier (`NC-SURV-0001` to `NC-SURV-0260`).
  - `Gender`: Participant gender distribution.
  - `Academic_Status`: Academic standing (Undergraduate, Postgraduate, etc.).
- **Item Responses:**
  - `Q1` through `Q42`: Individual item responses scored on a standard 0–3 Likert scale (0 = Did not apply to me at all, up to 3 = Applied to me very much, or most of the time).
- **Subscale Scores:**
  - `Depression_Score`, `Anxiety_Score`, `Stress_Score`: Aggregate subscale totals.
  - `Total_DASS_Score`: Cumulative mental health score.
- **Clinical Severity Classifications:**
  - `Depression_Severity`, `Anxiety_Severity`, `Stress_Severity`: Standardized clinical cutoffs (Normal, Mild, Moderate, Severe, Extremely Severe).

## Data Collection Methodology
Data was gathered directly through team-administered digital survey instruments following strict ethical standards, ensuring full participant anonymization and zero collection of identifiable personal information.

## License
This dataset is published and made openly available under the [MIT License](LICENSE).
