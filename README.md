- All flux data has been compiled and cut down to only days 0 through 6 of differentiation in 'all_compiled_flux_trunc.csv'.
- columns are as follows
- CHIR: dose of CHIR administered
- control: 1 if this well was control (no cells seeded)
- seed: has original cell seeding density in thousands if that was documented
- cTnT: quantified positive cTnT signal (cardiac troponin). e.g. .461 -> 46.1% of the well was positive
- expID: month number corresponding to which plate this well was cultured on. for example 8 = August experiment
- wellNum: the well number 
- all data after is flux data, one observation recorded per 15 minutes

**This does not include the october data as we have not stained/imaged/quantified cTnT as of today 10/21/22
October data can be found in 'oct' folder**


EMD data and feature extraction (Catch22) found in emd folders. Two interpolation methods were attempted, pchip and cubic spline. pchip looks better
