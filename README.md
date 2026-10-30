# Aviation Accident Analysis
Project Overview
This project analyses aviation accident records from 1983 onwards to compare safety outcomes across professionally built airplanes. It aims to identify aircraft makes and models with comparatively low fatal/serious injury fractions and aircraft destruction proportions.
Data and Methodology
The analysis uses the supplied AviationData.csv and USState_Codes.csv files.

The data is cleaned and filtered to:
- Accident records from 1983 onwards.
- Professionally built airplanes.
- Records with identifiable aircraft makes and models.
The analysis compares:
- Fatal and serious injuries as a proportion of occupants.
- Aircraft destruction proportions.
- Small and larger accident groups, using 20 occupants as the grouping threshold.
- Weather conditions and phase of flight.
Sample sizes and confidence intervals are considered when comparing makes and models.
Key Findings
The analysis notebooks contain the summary tables and visualisations comparing aircraft groups, manufacturers, models, weather conditions and phases of flight.

Main findings: Add the actual results from the completed analysis here, including the best-supported aircraft makes/models and their sample sizes.
Recommendations
Use the results to shortlist aircraft makes and models with comparatively low injury fractions and destruction proportions. Consider both measures, sample sizes and confidence intervals before making recommendations.

Small aircraft: Add the supported recommendation from the results.

Larger aircraft: Add the supported recommendation from the results.
Project Files
- Aviation_Accidents_Cleaning.ipynb – data cleaning and preparation.
- Aviation_Accidents_Data_Analysis.ipynb – statistical analysis, tables and visualisations.
- data/ – source and cleaned datasets.
Limitations
The dataset contains accident records but not total flights or flight hours. Therefore, the analysis compares accident severity outcomes; it cannot determine accident risk per flight. The small/larger aircraft grouping uses accident occupant counts, not certified seating capacity.