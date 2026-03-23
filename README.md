# Evaluating Paper Reviewer AI Models

## TL;DR

Generate paper reviews using popular LLMs and compare them with the official paper reviews from human experts. The primary goal is to identify any inherent biases present in the LLMs. 

## Project Overview

**View the presentation:** [presentation.pdf]
**Explore the analysis notebook:** [analysis.ipynb](notebooks/analysis.ipynb)

## Environment

- Python: 3.9.20
- JupyterLab 4.3.5

See 'requirements.txt' for full dependencies 

Install dependencies:
'''bash
pip install -r requirements.txt
'''

## Workflow

### 0. Data Generation

The dataset was compiled by aggregating model-generated outputs into a structured JSON format. 
 
### 1. Data Pre-processing

[preprocessing_data.ipynb](notebooks/preprocessing_data.ipynb)

This notebook is for the data annotation, feature creation, data cleaning and pre-processing step used to generate the data. Note: Does not need to be run to use or explore the analysis notebook. Data is stored in 'LLM output data/'  

### 2. Analysis

Main analysis is performed in [analysis.ipynb](notebooks/analysis.ipynb) 







