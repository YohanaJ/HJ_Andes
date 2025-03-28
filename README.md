# Andean Ecoregion Floras Homogenization Analysis

This repository contains R code and data used for the analysis described in the paper:

**Homogenization and differentiation of Andean ecoregion floras driven by non-native plants: the role of political and environmental factors**

This study examines whether non-native plants drive floristic homogenization or differentiation among Andean ecoregions and explores the relationship of these patterns with geographic, climatic, and political variables.

## Project Overview

**Abstract:**  
*Aim:* Non-native plants could cause floristic homogenization or differentiation, yet such studies in mountain regions are limited. This work analyzes whether non-native plants contribute to increasing or decreasing the similarity of plant assemblages among Andean ecoregions and explores the association of these patterns with geographic, climatic, and political factors.  
*Location:* Andes mountains (South America).  
*Time period:* Present.  
*Major taxa studied:* Vascular plants.  
*Methods:* Native and non-native plant species compositions for 34 Andean ecoregions were obtained from GBIF and GRIIS databases. For each pair of ecoregions (n=496), the Jaccard similarity index was calculated separately for native and non-native species, and a homogenization index was derived. Regression analyses were then conducted to relate the homogenization index with geographic distance, climatic distance, and political similarity (i.e., countries involved).  
*Results:* The homogenization index ranged from 0.001 to 0.006. Overall, 37.7% of ecoregion pairs became more similar, while 34.7% became less similar, suggesting both homogenization and differentiation occur due to non-native plant introductions. The homogenization index was significantly negatively related to climatic distance, positively related to political similarity, and showed no significant relationship with geographic distance.  
*Main Conclusions:* Non-native plant introductions can drive both floristic homogenization and differentiation among Andean ecoregions. Differences in country policies appear to counteract the homogenizing effect of non-native species, particularly in ecoregions with similar environmental conditions.

## Repository Structure

 dataset/ # Contains all the input CSV files used in the analysis. 
 scripts/ # R scripts for data cleaning, analysis, and visualization.


## Requirements

- **R version:** 4.4.0
- **R packages:** `tidyr`, `dplyr`, `vegan`, `ggplot2`, `reshape2`, `ggpmisc`

