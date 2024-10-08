# Geospatial Analysis for Effective Disaster Preparedness

**Canada’s geography and climate** make it particularly vulnerable to natural disasters, with **floods** being the most frequent and costly. Factors such as **heavy rainfall, storm surges, and inadequate drainage systems** contribute to these floods, posing significant threats to communities, property, and the environment across the nation.

## Overview

This study investigates **flood distribution and intensity** in Canada by analyzing the following datasets:
- **Historical Flood Events (HFE)**
- **Hydrometric Data** from the Water Survey of Canada
- **National Hydronetwork Dataset**

## Methodology

### Spatial Analysis

- **Gaussian Kernel Density Estimation (KDE)** is used to identify flood patterns and contributing factors, particularly focusing on the **five most affected provinces**.
- Both **non-parametric** and **parametric** methods are employed to estimate flood intensity.
  
### Non-Parametric Approach
- **Point pattern analysis** and **KDE** are applied to visualize **flood hotspots**, providing insights into spatial distribution patterns.

### Parametric Approach
- Explores the impact of **hydrometric factors**, specifically **discharge values**, on flood occurrences.
- A **detailed analysis of Quebec** is conducted by incorporating **discharge values** and **spatial coordinates**, offering a comprehensive understanding of **flood intensity patterns**.

## Predictive Analysis

To further enhance disaster preparedness, we predicted **peak discharge levels** for the years **2023 to 2026**, as the current hydrometric dataset includes data only up to 2022. Using **Integrated Nested Laplace Approximation (INLA)** for forecasting, we estimated the potential **timing of floods** by analyzing the projected rise in **peak discharge levels** over the coming years.

## Conclusion

This research contributes valuable insights for **disaster preparedness** and **risk mitigation** in Canada. By understanding flood distribution and intensity patterns through spatial analysis, policymakers and emergency planners can implement **more effective disaster management strategies** and better prepare for future flood events.
