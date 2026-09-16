---
output:
  pdf_document: default
  html_document: default
---
# The deterministic underpinnings of demographic stochasticity

This is the data and code for: 

Kowalski, J.J., Gillies, G.J., & Germain, R.M. The deterministic underpinnings of demographic stochasticity. Submitted to *Ecology Letters* September 2026. 

**This repository consists of 3 scripts used for data cleaning, analysis, and plotting. They are located in the working directory and include:**

01_data_clean.Rmd: This script contains the raw growth and germination data for *Bromus hordeaceus* from the initial drought experiment and the raw demographic data for *Bromus hordeaceus* from the follow-up drought experiment and converts them (via cleaning and wrangling) into individual data frames for statistical analysis. 

02_stats.Rmd: This script contains all analyses referenced in the manuscript. 

03_data_vis.Rmd: This script generates all plots found in the manuscript. Note that cosmetic errors were corrected and final formatting details were completed in Affinity Designer where care was taken to not impact the display of quantitative data. 



**There are __ data files within the raw_data subfolder used in this analysis:**

germ1 : Weekly growth data (height) for B. hordeaceus in the first drought experiment (2021-2022) AFTER the seed cull. It contains 600 observations and 21 columns. 

| Column header | Data type | Description |
| :------------ | :---------| :---------- |