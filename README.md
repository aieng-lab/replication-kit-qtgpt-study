# Replication package

This repository contains the code and data in a study on the ability of large language models to impersonate public speakers in political debates.

## Requirements
- Python 3 (tested with Python 3.10)

## Structure
- `data/`: Contains the data used in the experiments, including the debate questions, answers, generated answers, speaker biographies, linguistic markers, code book of the free text answers, and the results of the manual coding.
- `figures/`: Contains the figures generated in the analysis.
- `markers/`: Contains helper files with lists of linguistic markers required for the calcuation of the linguistic surface.
- statistical_analysis.ipynb: Jupyter notebook with the statistical analysis of the data.
- calc_lingustic_features.ipynb: Jupyter notebook with the code to calculate the linguistic features that describe the linguistic surface.

## Usage example for Ubuntu 22.04

Exectute the following commands in the terminal to clone the repository and install the required packages.

```bash
git clone git@github.com:aieng-lab/replication-kit-qtgpt-study.git
cd replication-kit-qtgpt-study
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

You can then start Jupyter Lab and open it in a browser to view and execute the Juypter notebooks.

```bash
jupyter lab
```
