# MatthewX-Repo
All Code pertinent to Matthew's modeling work
## Current Work Done:
Residual Model where performance on "mechanistic" features is optimized and boosted with the inclusion of the Child Behavioral Checklist (CBCL) features.
Note: The code for this model and the saved weights can be found in the **"Residual Model"** Folder
### Model Metrics:
When CBCL features are available: AUC = 0.7783
When CBCL features are **not** available: AUC = 0.6749

### Important note if using model:
The current saved residual model is not fully optimized, but achieves close to optimal performance. If optimization is desired, the hyperparameters will need to be tuned using a hyperparameter tuning technique.
