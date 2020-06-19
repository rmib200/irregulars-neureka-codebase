# Seizure Detection Codebase used in Neureka Challenge 2020

This repository contains the code of the *Biomed Irregulars* submission to the Neureka Challenge 2020. The *Biomed irregulars* team consists of PhD students from the the ESAT-STADIUS research group at KU Leuven: C. Chatzichristos, J. Dan, A.M. Narayanan, N. Seeuws, K. Vandecasteele.

The seizure detection algorithm is based on the fusion of multiple attention U-nets, each operating on a distinct view of the EEG data. The outputs of the different U-nets are fused by an LSTM network. More information about the methods and results can be found in the preliminary version of the paper [neureka_ieee_spmb.pdf](https://github.com/mabhijithn/irregulars-neureka-codebase/raw/public/neureka_ieee_spmb.pdf).


## Code: Content 
1. `library/` - This folder contains the general functions used accross modules: data loading, re-referencing, resampling and filtering.
2. `training/` - Contains the code to train the Wiener filters, U-nets and LSTM models.
3. `evaluate/` - Contains the code to run the seizure detection pipeline on unlabelled data.

While the intent of the code is to allow deceminatation and re-use of our pipeline and model architecture. We realize the code is not *click & run* and documentation is sometimes lacking. We do invite you to contact us through email or as a github issue to improve quality and understanding of the code.




  
