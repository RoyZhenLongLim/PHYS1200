# Week 2

## Progress Made
- Data from APOGEE and GALAH have been cleaned
- A sizeable chunk of the code required to create a RFR model has been created
    - Most of it was Chris's code being repurposed.

## Questions to ask
- Not sure how to tackle the K2 data set
  - I think I need to match K2 data set with the GALAH dataset to determine the stars
  - Afterwards, determine the mass from the shared data and use in the ML model
    
- Not sure how to tackle the APOKSAC data
    - Do not include the chemical abundance that would be required in order to
    - I think we need to do something similar to K2

- What are the overlaps between data?
  - I.e. what stars do which data set include?

- GAIA vs GALAH?
  - Not sure what GAIA mean
  - It looks like GAIA was a project involving the GAIA spacecraft which aims to categorize 1% of all stars (100 billion 
    stars)

## TODO: Reminder
- `data_processing.ipynb`
    - [x] There are rows with null values
        - Figure out how to remove then
    - Sort out APOKSAC and K2 data
- `mass_model.ipynb`
    - Keep working on this
- Research
    - [ ] First Dredging
    - [ ] Scikit-learn packages (anything that can be used to predict mass)
    - [ ] Overlap between K2, APOKSAC, APOGEE and GALAH datasets
