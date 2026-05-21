# NASA Artemis II HRP Data Methodology Challenge
## Within-Subject Longitudinal Baseline Comparison Framework

### Overview
This repository contains the methodology demonstration for the NASA Artemis II 
Human Research Data Methodology Challenge. The analysis applies a within-subject 
baseline comparison framework to NHANES 2017-2018 proxy data, focusing on sleep 
and stress indicators in an astronaut-like cohort.

### Repository Contents
- HRPchallenge.ipynb — Main analysis notebook
- baseline_comparison.png — Sleep and stress deviation plots
- sleep_vs_stress.png — Subject profile scatter plot
- data/ — Downloaded NHANES data files

### Requirements
- Python 3.x
- jupyter
- pandas
- numpy
- matplotlib
- scipy

### Reproduction Instructions
1. Clone this repository
2. Open Terminal and navigate to the folder
3. Install dependencies by running:
   pip3 install jupyter pandas numpy matplotlib scipy requests
4. Launch Jupyter by running:
   jupyter notebook
5. Open HRPchallenge.ipynb
6. Click Kernel > Restart & Run All
7. All outputs and plots will be generated automatically

### Dataset
NHANES 2017-2018 (National Health and Nutrition Examination Survey)
Downloaded automatically from CDC public servers when notebook is run.

### Methodology
Within-subject baseline comparison using population-level statistics 
from an astronaut-like cohort (adults 25-55, college educated) as the 
reference baseline. Four simulated subjects are compared against this 
baseline using standardized deviation scores across sleep duration and 
psychological stress indicators.
