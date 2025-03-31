# Andean Ecoregion Floras Homogenization Analysis

This repository contains R code and data used for the analysis described in the paper:

**Homogenization and differentiation of Andean ecoregion floras driven by non-native plants: the role of political and environmental factors**

This study examines whether non-native plants drive floristic homogenization or differentiation among Andean ecoregions and explores the relationship of these patterns with geographic, climatic, and political variables.

## Repository Structure

Pre-processing includes
 1) Climate variables: code and shapefile for extracting climate variables for each ecoregion in Google earth engine
 2) Jaccard_&_homogenization_index: Distance matrix and code for calculating jaccard and homogenization index
Dataset/ # Contains all the input CSV files used in the analysis. 
Script/ # R scripts for data analysis, and visualization.


## Requirements

- **R version:** 4.4.0
- **R packages:** `tidyr`, `dplyr`, `vegan`, `ggplot2`, `reshape2`, `ggpmisc`

