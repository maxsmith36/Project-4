# Project-4
This project analyzes potential bias within the Federal Emergency Management Agency’s (FEMA) National Risk Index (NRI), a tool used to evaluate natural disaster risk across U.S. communities. The NRI defines risk as a function of hazard probability and impact, incorporating factors such as expected annual loss, social vulnerability, and community resilience. While widely used, the methodology may produce different outcomes depending on how variables are defined and weighted.

Working on behalf of Risk Averse, LLC, this project performs a sensitivity analysis to examine how changes in inputs and assumptions influence NRI risk scores. In addition to evaluating the existing model, an alternative risk scoring method is developed using the same dataset to compare results and identify potential categorical bias.

The analysis focuses on census tract-level data for two selected states and integrates datasets from the FEMA NRI and the CDC Social Vulnerability Index (SVI). Data is cleaned, standardized, and merged to ensure consistency and reliability. Python, including libraries such as Pandas and GeoPandas, is used to conduct analysis, generate summary statistics, and create geospatial visualizations.

Key outputs include comparative tables, figures, and maps that illustrate differences between the NRI and the proposed model. These results are used to evaluate how varying definitions of risk can impact community classification and resource prioritization.

Overall, this project demonstrates how data modeling decisions can influence real-world outcomes, particularly in areas such as disaster preparedness and funding allocation. It emphasizes the importance of transparency, critical evaluation, and ethical considerations in engineering and data-driven decision-making processes.
