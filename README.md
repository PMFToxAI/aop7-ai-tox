# aop7-ai-tox
This repository contains accompanying code for "Predicting Chemicals' Toxicity Pathway of Female Reproductive Disorders using AOP7 and Deep Neural Networks" by authors: Natasa Sukur, Nemanja Milosevic, Kristina Pogrmic-Majkic, Bojana Stanic, Nebojsa Andric.

# Requirements

We use conda to manage dependencies. To replicate our environment use:

    conda env create -f conda-env.yml

# Structure

    data/ --> assay data
    raw_data_comptox --> source data from CompTox
    sac, skec, skeec --> model inference results
    downloader.ipynb --> assay downloader
    extractor.ipynb --> data preparation script for NN models
    finder.ipynb --> EDA notebook with various data experiments
    fix-smiles.ipynb --> ChemPlusID helper to find mising SMILES
    nn_prod{1,2,3}.ipynb --> SAC, SKEC, SKEEC model trainer notebooks
    inference_prod{1,2,3}.ipynb --> SAC, SKEC, SKEEC model inference notebooks
    conda-env.yml --> conda environment
