# polyML - machine learning prediction of polymer properties

In this project, we use machine learning models for the prediction of polymer properties. The input to our machine learning models are fingerprints that are computed based on the polymer chemical structure. The output of the models is the tensile strength of the polymer.


## Objective
Predict the tensile strength of polymers based on their chemical structure.


## Data

The data is collected from the following websites
- polymerdatabase.com
- ...


### Format

| polymer smiles | fingerprint | tensile strength at break |
| -------------- | ----------- | ------------------------- |
| *CC*           | [1,2,3,0]   | 3                         |
| *CCO*          | [1,0,3,0]   | 3.1                       |
| *CC(C)*        | [10,2,3,0]  | 3.2                       |

## Rough plan

1. Curate and clean data 
2. Use clustering for outlier detection
3. Fingerprint
4. Normalize fingerprints
5. Train ML model
6. Deploy 
