# Week 5 & 6

## Progress Made

- Finishing creating data for APOKSAC mass prediction by merging APOKSAC and APOGEE data
  - Created RFR and Polynomial Regression model for APOKSAC mass prediction
  - Determine the appropriate `log g` required is around 3-3.5 Solar Masses for APOGEE

## Questions

- Lithium
  - Unsure about the expected Lithium changes
    - Lithium Abundance is observed to decrease
    - Do I just need to track Li_Fe?
    
- What is the best way to look at Deep Mixing?
  + Chris created bins and looked at the max and min
  + Not sure if this is the best way to do it?

## Goals for next meeting

- Redo analysis with `log g < 3`
  + The current one is `log g < 3.5`, which is far more generous
- Sort out GALAH and K2 data
  + Currently there are only two matches
    * This might be to do with the data only having 999999 stars (there was an option for unlimited numbers)
    
- Compare mass distribution between GALAH and APOGEE
  + Investigate GALAH 
    * C/N vs log g 
    * Li/Fe vs log g
    
- Research a way to investigate deep mixing
  + Creating bins and computing C/N vs log g
  + Is there a way to compute luminosity and use that as a measure of whether something is a red giant vs log g
  + Use numpy and create a polynomial that describes the relationship between the data points that are given?

- Investigate weird shapes in the data
  + What is expected is just a drop in C/N
  + In some groups, we can see that
  + However, there is a noticeable drop in C/N that doesn't align with the rest of the data points
  
- Start writing the report so that I can get feedback on it early

## Feedback

- al_fe 
  + aluminum 
  + need to change this
  
- EPIC id
  + Change string to eliminate white space strip
  + Vizier has a X-match
  + 
  
- Globular Clusters
  + Parallel branches
  + Not present in lower mass
  + Take low C/N abundance
    * `ra`, `dec` + `rv`
    * PMRA + PMDec (proper motion)
    * Low C/N ones should have similar parameters

- Lin 2009
  + Lithium abundance vs surface gravity
  
- Lagarde 2019
  + Has models for C/N vs log g
  
- Prove deep mixing doesn't occur over a certain mass
  + Make a larger bin starting from 4 -> 2, 1.5,...
  + Is there a point where the deep mixing stops
  
- AGB
  + A phase after red giant after no helium in the core
  + Can tell from Astroseismology
  

  Hypothesis for low C/N stars
  - AGB or Globular Clusters
  - delta nu
    + frequency
  - delta p