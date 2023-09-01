# Regional GDP
A UC Berkeley **ECON148: Data Science for Economists** project.

### Introduction
In this project, we aim to examine economic performance at the county level, utilizing real Gross Domestic Product (GDP) data spanning the last twenty years. While GDP is predominantly examined as a national macroeconomic metric, regional heterogeneity also play a significant role in shaping economic growth and business cycle fluctuations. To delve into these regional variations in economic performance, particularly during economic recessions, we employed a dataset focused on county-level real GDPs, sourced from the Bureau of Economic Analysis (BEA). The analysis file can be found [here](https://github.com/lettaisabel/Regional-GDP/blob/main/proj01.ipynb).

**Skill sets applied in this project include:**
- Using the `Pandas` library to wrangle a real-world dataset.
- Utilized the `matplotlib` library to execute comprehensive data visualizations.

### Data sources:
The main dataset we use in this notebook is ["CAGDP9: Real GDP in Chained Dollars by County and MSA"](https://www.bea.gov/data/gdp/gdp-county-metro-and-other-areas) from the Bureau of Economic Analysis (BEA). It provides a comprehensive measure of the gross domestic product of counties, metropolitan statistical areas, and some other local areas in the United States from 2001 to the present. Accessed Jan 2023. **We used a subset of the full dataset (about 50%) that includes some of the industries available in the original dataset.**

We also used the ["United States Counties Database"](https://simplemaps.com/data/us-counties) from Simplemaps.com. Specifically, we will use the geographic data of U.S. counties (i.e., latitude and longitude) to create the visualizations in the last section. Accessed Jun 2022. 
