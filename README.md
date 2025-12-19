## SCREAM: Stream Characterization with Error-Aware Machine Learning

This repository contains code for SCREAM, a weakly supervised machine learning framework for characterizing Milky Way stellar streams.
SCREAM is based on the CATHODE anomaly detection framework and is applied here to the GD-1 stellar stream.
The model is trained on Gaia DR3 astrometric and photometric data cross-matched with DESI Legacy Imaging Survey DR9 photometry.
A key feature of SCREAM is the explicit incorporation of measurement uncertainties into the training procedure.
The framework uses minimal prior information and does not apply post-processing to model outputs.
Model predictions are evaluated using agreement with STREAMFINDER labels and validated using DESI radial velocity data, which are not used during training.
This repository supports the analysis and results presented in the accompanying research report.