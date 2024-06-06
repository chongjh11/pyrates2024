[![DOI](https://zenodo.org/badge/810518001.svg)](https://zenodo.org/doi/10.5281/zenodo.11508492)
# pyrates2024
### Project idea: 
Plotting the results from **Pylith** of a 2D transect:
1. Displacement from model and observation
2. Analysis of results

### Workflow (outline) 

| Steps | Input | Output | Code   |
|-------|-------|--------|------  |
|Running a 2D example from Pylith| Example model |  | Pylith |
|Pylith generates displacement | | Displacement product in `.hdf5` | Pylith|
|Plot displacement along with geometry in python | Displacement, geometry||Python|
|Plot the difference between observation and model|||Python|
|Do simple RMSE, stats calculation|||Python|

