# Week 2

## Progress Made
- Data from APOGEE and GALAH have been cleaned
- A sizeable chunk of the code required to create a RFR model has been created
    - Most of it was Chris's code being repurposed.

## Questions to ask
- Not sure how to tackle the K2 data set
    - Attempted to use 'pd.read_fwf'
        - Is there a recommended way that I should be sifting through the data?
    - Not sure what some symbol mean
        - Not sure how to interpret
- Not sure how to tackle the APOKSAC data
    - Do not include the chemical abundance that would be required in order to

## TODO: Reminder
- `data_processing.ipynb`
    - [x] There are rows with null values
        - Figure out how to remove then
    - Sort out APOKSAC and K2 data
    - Ask about determine the mass of the stars we are used
        - Think we need to match them up with the APOGEE Data
- `mass_model.ipynb`
    - Keep working on this
- Research
    - [ ] First Dredging
    - [ ] Scikit-learn packages (anything that can be used to predict mass)
    - [ ] Overlap between K2, APOKSAC, APOGEE and GALAH datasets
