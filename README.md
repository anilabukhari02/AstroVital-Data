# AstroVital
## Personalized Astronaut Health Intelligence System

AstroVital is a research-oriented prototype for exploring biological,
environmental, sleep, activity, and wellbeing data relevant to astronaut health.

## 1. Inspiration4 Astronaut Data

Includes:
- Serum metabolic and immune markers
- Complete Blood Count (CBC)
- Plasma metabolomics (ANP and RP-MTBE)

Main integrated dataset:
data/processed/Inspiration4/Inspiration4_integrated_serum_CBC_metabolomics.csv

Separate serum and CBC dataset:
data/processed/Inspiration4/OSD-575_OSD-569_serum_CBC_aligned.csv

The integrated dataset contains 4 astronauts and 24 observations.

## 2. External Human Reference Data

Source: MMASH

Includes:
- Sleep summaries
- Activity summaries
- Psychological scores
- RR-derived HRV measurements

MMASH participants are not astronauts. Their records remain separate
from Inspiration4 data.

## 3. Space Environment Data

Includes NASA environmental and radiation measurements such as:
- Radiation
- CO2
- Temperature
- Humidity

These measurements are maintained separately from astronaut biological data.

## 4. Supporting Biological Research

Additional NASA studies include research on:
- Muscle cells
- Endothelial cells
- Blood lymphocytes
- Smooth muscle cells
- Neuronal cell models
- Brain organoids (files pending)

These are supporting research datasets, not direct astronaut measurements.

## Repository Structure

- data/raw: Original downloaded data (excluded from GitHub)
- data/processed: Processed and integrated datasets
- metadata: Study metadata and sample information
- reports: Collection and quality-control reports

## Data Processing Principles

- Original raw datasets are preserved unchanged.
- Missing values are not automatically imputed.
- Different biological materials remain distinguishable.
- Datasets are aligned only when identifiers and metadata support it.
- External human reference data remains separate from astronaut data.

## Limitations

- Inspiration4 contains a small number of astronauts.
- Some datasets have missing measurements and different timepoints.
- MMASH is not a spaceflight dataset.
- Cell-based research is not direct astronaut health data.
- HRV metrics are exploratory and not clinically validated.
- AstroVital is a research prototype, not a medical diagnostic system.

## Data Sources

- NASA Open Science Data Repository (OSDR)
- NASA environmental and radiation datasets
- MMASH external human reference dataset

Consult original dataset documentation and licensing terms before reuse.

## Project Status

Data collection, selected processing, and main Inspiration4 integration
have been completed. The project is being prepared for GitHub.
