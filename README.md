# Strawberry Analysis Project

## Overview
This repository contains a comprehensive analysis of strawberry production in California and Florida, focusing on chemical treatments and production/sales comparisons between organic and conventional strawberries. The analysis examines USDA data to identify patterns in chemical usage, pricing, yields, and market trends.

## Project Structure
- `strawb_mar6.csv`: Main dataset containing strawberry farming data
- `my_functions.R`: Helper functions for data cleaning and processing
- `Strawberry_Analysis.qmd`: Quarto document containing the full analysis and code
- `Strawberry_Analysis.html`: html document containing the full analysis and code

## Research Questions
1. **Chemical Treatment Analysis**: Examines three chemical treatments (Captan, Spinetoram, and Acetamiprid) used in conventional strawberry farming, contrasting their application patterns between California and Florida.

2. **Organic vs. Conventional Comparison**: Analyzes production volumes, yields, acreage, and pricing differences between organic and conventional strawberries in both states, with attention to how these relationships change over time.

## Key Findings

### Chemical Treatments
- Captan (fungicide) shows significantly higher usage in California compared to Florida
- Spinetoram and Acetamiprid (insecticides) demonstrate much higher usage in Florida than California
- Usage patterns reflect regional differences in pest pressure, climate conditions, and management strategies

### Organic vs. Conventional Production
- California maintains substantially higher production volumes and acreage for both organic and conventional strawberries
- California achieves higher yields per acre compared to Florida
- Florida commands higher prices per CWT for its strawberries
- Organic strawberries maintain a significant price premium in both states (approximately 76% in California and 71% in Florida)

## Methods
- Data cleaning and processing using R and the tidyverse suite
- Statistical analysis of chemical usage patterns
- Comparative visualization of production metrics
- Price and yield analysis across different production systems

## Requirements
- R (version 4.1.0 or higher)
- Required packages: tidyverse, ggplot2, scales, knitr, kableExtra

## Usage
1. Clone this repository
2. Open the R project
3. Run the Quarto document to reproduce the analysis

## Acknowledgments
- Data sourced from USDA agricultural surveys
- Analysis methodology adapted from Boston University MA415/615 course materials
- Assistance from AI tools (ChatGPT, Claude) for code development and analysis
