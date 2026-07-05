# Spatial Pattern of Trees

## Project Overview

This exercise applies classical spatial statistics to forest trees using Fisher’s index, Clark-Evans nearest-neighbour spacing, chi-square testing for infected-tree randomness, Ripley’s \(L(t)\) function, and Moran’s continuous index for tree-diameter autocorrelation. The workflow is used to interpret clustering, regularity, and randomness in forest stands. 

## Objectives

- Assess tree spatial pattern using Fisher’s index.
- Estimate stem density per hectare.
- Evaluate spacing in a young stand using Clark-Evans \(R\).
- Test whether infected trees are randomly distributed.
- Analyze point patterns with Ripley’s \(L(t)\).
- Compute spatial autocorrelation in tree diameter using Moran’s index. 

## Data

- Excel-based plot data for seedling stands
- Distance-based young-stand data
- Infected-tree distribution data
- Drone-derived point-pattern data
- Tree-diameter data for autocorrelation analysis :contentReference[oaicite:12]{index=12}

## Methodology

### Task 1: Fisher’s Index
The exercise uses ten seedling-stand plots of 25 m² each to determine the spatial pattern from stem counts. The diary reports a Fisher’s index of about **1.604**, suggesting a slightly uniform distribution, and estimates **2760 stems per hectare**. 

### Task 2: Clark-Evans Index
For the young stand, tree-to-tree distances were analyzed with the Clark-Evans index. The diary reports **R = 0.218**, indicating strong clustering and suggesting that thinning may be needed. 

### Task 3: Chi-square Randomness Test
The infected-tree pattern was tested against randomness using a chi-square test. The diary reports **χ² = 51.91**, which is greater than the critical threshold **49.80**, so randomness was rejected. :contentReference[oaicite:15]{index=15}

### Task 4: Ripley’s \(L(t)\)
Drone-derived tree coordinates were analyzed using Ripley’s \(L(t)\) function in R. The exercise materials describe this as a point-pattern analysis, and the diary interprets the result as more regular at short distances and approaching randomness at larger distances. 

### Task 5: Moran’s Continuous Index
Tree-diameter autocorrelation was analyzed using Moran’s continuous index, with Geary’s \(C\) suggested as an additional comparison. Neighbours were defined within a 3 m radius. :contentReference[oaicite:17]{index=17}

## Main Outputs

- Fisher’s index and stem-density estimate
- Clark-Evans \(R\) value
- Chi-square test result
- Ripley’s \(L(t)\) interpretation
- Moran’s index for diameter autocorrelation 

## Skills Demonstrated

- Spatial statistics in forestry
- Point-pattern analysis
- Tree spacing interpretation
- Randomness testing
- Spatial autocorrelation
- Forest stand structure assessment 
