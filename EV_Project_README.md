# Texas DCFC Charging Station Network – Tableau Project

## Overview
This Tableau project focuses on identifying optimal locations for installing **Direct Current Fast Charging (DCFC)** stations across the state of Texas, United States. The goal is to facilitate long-distance electric vehicle (EV) travel, reduce **range anxiety**, and address common adoption barriers by leveraging clustering analysis and federal/state infrastructure guidelines.

## Objectives
- Establish a strategic network of DCFC charging stations across Texas to support long-distance travel.
- Address range anxiety and accessibility concerns for EV owners.
- Align station placement with **federal spacing requirements** and **state incentive programs**.
- Maximize coverage for both urban and rural areas using a data-driven approach.

## Methodology
1. **Data Classification**
   - Categorized Texas counties as either **urban** or **rural**.
   - Applied different station placement strategies for urban and rural regions.

2. **Urban Area Approach**
   - Focused construction along the **Electric Alternative Fuel Corridor** and rest areas.
   - Ensured compliance with **Federal Highway Administration** guidance (stations every ~50 miles and within 1 mile of interstate exits).

3. **Rural Area Approach**
   - Prioritized station installation near **county seats** to maximize accessibility.

4. **Clustering Analysis**
   - Performed clustering on existing DCFC charging station locations to identify service gaps.
   - Computed centroids and measured **Euclidean distances** between stations and gaps.
   - Determined an average station spacing of ~54 miles, leading to an estimate of **67 stations needed along key corridors**.

5. **Targeted Rest Areas & County Coverage**
   - Identified **69 rest areas** suitable for DCFC stations (totaling 276 chargers).
   - Planned additional stations for the **223 rural counties** without existing chargers.

## Key Findings
- Texas had only **302 fast chargers** as of Dec 2022, concentrated mainly in urban areas.
- EV adoption remains low (0.33% of total vehicle registrations in 2021) but is expected to grow rapidly with incentives.
- Federal and state programs, including the **NEVI Plan**, support DCFC deployment with funding and rebates.
- Clustering analysis confirmed that a 50–54 mile interval between chargers optimizes long-distance travel coverage.
- Total estimated cost for implementation: **$64.6M**.

## Tools and Technologies
- **Tableau** – Data visualization and geographic mapping.
- **Excel / CSV** – Data cleaning and preparation.
- **Clustering Analysis (Euclidean Distance)** – Optimal charger spacing calculation.

## Dashboard
View the live Tableau dashboard here: [**Tableau Public Link**](https://public.tableau.com/app/profile/parth.milind.bhingarde/viz/Group6_EV_final/Combine)

## Report
Read the full project presentation here: [**Google Drive Presentation**](https://docs.google.com/presentation/d/1Hy9ZzksekAJIiMDivO0w9dKJLQ5RKogb/edit?usp=drive_link&ouid=102191787702317834573&rtpof=true&sd=true)

## Conclusion
Deploying ~67 corridor stations, 276 rest area chargers, and county-seat stations in rural areas can significantly reduce range anxiety and improve EV adoption rates in Texas. This plan combines **federal compliance, geographic analysis, and clustering insights** to create a cost-effective, scalable charging network.

## Future Improvements
- Incorporate **traffic flow and EV adoption forecasts** to refine station placement.
- Model **seasonal and peak travel patterns** to optimize charger availability.
- Include **renewable energy integration** for sustainable charging solutions.

---
