# BenchmarkStudy_CRISPRcas9

## Overview

**BenchmarkStudy_CRISPRcas9** provides a comprehensive comparison of leading computational tools for CRISPR-Cas9 off-target prediction, including data preprocessing, model implementation, and thorough evaluation. The repository is aimed at researchers and practitioners interested in benchmarking CRISPR-Cas9 guide RNA design methods and off-target analysis.

## Features

- End-to-end benchmarking pipeline for CRISPR-Cas9 off-target prediction tools
- Scripts for data preprocessing and formatting
- Implementations of multiple state-of-the-art prediction models
- Unified evaluation metrics and comparison framework
- Example datasets for testing

## Contents

- `data/` — Sample data and preprocessing scripts
- `models/` — Implementation of various CRISPR off-target prediction models
- `evaluation/` — Scripts for performance evaluation and result visualization
- `results/` — Example results and analysis
- `README.md` — Project documentation

## Installation

1. Clone this repository:
git clone https://github.com/anushkxa/BenchmarkStudy_CRISPRcas9.git
cd BenchmarkStudy_CRISPRcas9

3. Install dependencies:

Additional dependencies and setup instructions for specific tools may be provided in their respective folders.

## Usage

- Modify paths and parameters in `config.yaml` or relevant script files to match your system and dataset.
- Run data preprocessing:
python data/preprocess.py
- Train or evaluate prediction models:
python models/train_eval.py- Summarize and visualize results:
python evaluation/analyze_results.py

- Detailed usage instructions for each step are in the corresponding script or module.

## Supported Models

- cnnCRISPR: [https://github.com/LQYoLH/CnnCrispr.git](https://github.com/LQYoLH/CnnCrispr.git)
- PI-CRISPR: [https://github.com/florianst/picrispr.git](https://github.com/florianst/picrispr.git)
- DeepCRISPR: [https://github.com/bm2-lab/DeepCRISPR.git](https://github.com/bm2-lab/DeepCRISPR.git)
- CRISPROT: [https://github.com/bm2-lab/CRISOT.git](https://github.com/bm2-lab/CRISOT.git)
- CRISPR-IP: [https://github.com/BioinfoVirgo/CRISPR-IP.git](https://github.com/BioinfoVirgo/CRISPR-IP.git)

## Citing

If you use this repository or its results in your research, please cite appropriately. Citation files and BibTeX entries are provided in `CITATION.cff`.

## Contact

For questions, comments, or contributions, please open an issue or contact the maintainer: [anushkxa](https://github.com/anushkxa) [abhishek].

