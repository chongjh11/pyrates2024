# pyrates2024
### Project idea: 
Plotting the results from Pylith:
1. Displacement from model and observation
2. Analysis of results

### Workflow (outline) 

| Steps | Input | Output | Code   |
|-------|-------|--------|------  |
|Running the example from Pylith| Example model |  | Pylith |
|Pylith generates displacement | | Displacement product in .hdf5 | Pylith|
|Plot displacement along with geometry in python | Displacement, geometry||Python|
