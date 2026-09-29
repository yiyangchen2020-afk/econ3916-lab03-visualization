Honest vs. Misleading Visualizations
Objective
To examine how visualization choices can change the interpretation of economic data and to build a more transparent workflow for evaluating and presenting quantitative evidence.
Methodology
- Recreated Anscombe’s Quartet to compare datasets with nearly identical summary statistics but very different visual patterns.
- Calculated a Lie Factor of 49.0 for a truncated-axis revenue chart and redesigned the visualization using a more honest scale.
- Compared four visual framings of real average hourly earnings using FRED AHETPI data adjusted to 2020 dollars.
- Applied a four-step EDA workflow—structure, distributions, relationships, and anomalies—to World Bank GDP data covering 262 countries across 64 years.
- Built an interactive wage chart that allows users to switch between nominal and real earnings, change the time window, adjust the y-axis floor, and compare linear and log scales while tracking the Lie Factor.
Key Findings
Anscombe’s Quartet showed that similar means, variances, correlations, and regression results can hide very different underlying data structures. The truncated-axis example produced a Lie Factor of 49.0, demonstrating how axis choices can greatly exaggerate the apparent size of a change. The wage analysis also showed that time windows, inflation adjustment, and axis scaling can lead to very different interpretations of the same series. Overall, the lab reinforced the importance of combining summary statistics with visualization and checking how design choices affect the story told by economic data.
