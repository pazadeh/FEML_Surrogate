# Surrogate modelling of protein networks using nanoFE simulations and machine learning

This repository contains the codes and trained models presented in paper titled "A NanoFE Simulation-based Surrogate Machine Learning Model to Predict Mechanical Functionality of Protein Networks from Live Confocal Imaging". The preprint of the paper can be found in: 

https://www.biorxiv.org/content/10.1101/2020.03.27.011239v2

In summary, this paper respresent a method for carrying out an automatic analysis of the structure-function relationship in cytoskeletal protein networks. This is done by combining computation confocal imaging, nanoFE simulations and unregulated data mapping (machine learning). The method includes 3 different steps:

  1. live 3D confocal imaging and image processing (for detailed explanation take a look at Asgharzadeh et al. 2018 Acta Biomaterialia), for extracting structural features of the biopolymers networks, 
  
  2. in-silico mechanical experiments for extracting the mechanical traits of the biopolymers networks, and
  3. gradient boosting models to map the structural features to the mechanical traits.
