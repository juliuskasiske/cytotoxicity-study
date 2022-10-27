# cytotoxicity-study
Analysis, statistical testing and visualization of the suitability of different materials for artificial bone growth
## 1. Languages/technologies used
- R (data.table, ggplot2)
## 2. Mathematical/statistical concepts used
- Two sample students t-test & welsh test
- Non-parametric monte-carlo permutation test

## 3. Motivation and Procedure
In medicine, occasional needs for artificially grown bone structures may arise, yielding a need to research
best possible materials to use, such that optimal solutions can be fielded across care units.
This research compares seven materials growing on osteosarcoma cells and osteoblasts. The measurements
and lab research was conducted by my colleague, a medical student, who measured multiple extinction values
in each group across eight different scaffolds and then recorded means and standard deviations across these
scaffolds and measurements. After she generated the necessary data, I had three key tasks:
1. **Data Wrangling**, where I needed to tidy and manipulate data sets in order to properly plot the results
and test them against null hypotheses.
2. **Data Visualization**, which encompassed choosing appropriate plots and building a custom ggplot2-
theme.
3. **Hypothesis Testing**, including validating various assumptions that different testing methods make and
choosing the most appropriate one based on these assumptions holding in each particular case.
