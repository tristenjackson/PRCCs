# PRCCs
This function serves as a means of calculating the partial rank correlation coefficients (PRCCs) of a set of equally sized (n,1) input arrays, p1, p2,... where the last input is the response of the model for each iteration of the given parameters. The output of this function is a vector of the PRCC for each parameter provided, with a corresponding bar plot. For optimal usage, ensure an appropriately large number of iterations for each parameter and model response. Stratified sampling techniques are suggested for obtaining these iterations of parameters, so as to limit the computational burden of this function. Most practical applications of partial rank correlation coefficient analysis take place in uncertainty and sensitivity analysis, particularly in biological systems with comparatively high degrees of parameter uncertainty. These are used as a means of exploring a system's parameter space while attempting to control for the impacts of other parameters on the response, allowing each of them to be analyzed simultaneously. This is typically used, in comparison to a partial correlation coefficient test, in circumstances of nonlinear but monotonic relationships between a function and its parameters.

Developed in Matlab version 2022a; expected compatibility all versions later than 2006a. Please contact tjackson@math.fsu.edu with any questions, recommendations, or feedback.

Where applicable, please cite as:

Tristen, M. Jackson. (2022). Partial Rank Correlation Coefficient Function in Matlab. Zenodo. https://doi.org/10.5281/zenodo.7222052
