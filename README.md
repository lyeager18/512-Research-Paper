# The Micro-Spatial Impact of China's Belt and Road Initiative on Perceptions of Economic Security and Threats in Southeast Asia

**Status:** Proposal complete. Data collection in progress.

## Research question
Does living near Chinese-financed infrastructure make citizens feel more economically secure, or does it raise concerns about strategic dependence and lost sovereignty?

- **H1:** Proximity to visible transportation infrastructure (e.g., high-speed rail, highways) increases perceptions of local economic opportunity and positive views of Chinese economic engagement.
- **H2:** Proximity to resource-extraction or energy projects increases anxieties about national sovereignty and strategic economic vulnerability.

**Countries:** Indonesia, Malaysia, Cambodia, Vietnam, the Philippines, Thailand

## Approach
Spatial difference-in-differences / event study. Survey respondents living near a completed Chinese-financed project (treated) are compared with respondents farther away (control), before and after project completion. Effects are estimated separately by project sector (transport, energy, resource extraction).

Respondent locations are built from the sampling frames in each Asian Barometer country technical report (province, district, commune) and geocoded to administrative boundaries.

## Data sources
| Data | Source | Used for |
|---|---|---|
| Chinese-financed project locations, sectors, dates | AidData, Geospatial Global Chinese Development Finance Dataset v3.0 (Goodman et al. 2024) | Treatment |
| Individual perceptions | Asian Barometer Survey, Waves 3-5 | Outcomes |
| Local economic conditions | VIIRS and DMSP-OLS nighttime lights | Controls |
| Administrative boundaries | GADM / geoBoundaries | Geocoding |

See `data/README.md` for access instructions. **Raw survey data is not included in this repository.**

## Repository structure
```
proposal/   Research proposal
data/       Data documentation only (raw and cleaned data are not committed)
code/       Numbered scripts, run in order
output/     Tables and figures
notes/      Log of research decisions
```

## Reproducing the analysis
1. Request the Asian Barometer data (see `data/README.md`) and download the public sources listed there.
2. Place raw files in `data/raw/` (ignored by Git).
3. Run the scripts in `code/` in numerical order.

## Limitations (planned)
- Project placement is not random.
- Respondents may not know a project is Chinese-financed.
- Surveys are repeated cross-sections, not a panel of places.
- Few respondents may live near any given project, especially extraction projects.
- Social desirability may affect answers about China in some countries.
