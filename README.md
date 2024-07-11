# OrthoMortPred
# OrthoMortPred: In-Hospital Mortality Prediction for Orthopedic Patients

## Overview
This repository contains the code and data used in developing a predictive model for in-hospital mortality among orthopedic patients. The study was conducted using data from the Central Lisbon University Hospital Center, spanning from 2021 to 2023.

## Repository Contents
- `data/`: Contains the anonymized dataset and data dictionary
- `notebooks/`: Jupyter notebooks detailing each step of the analysis
- `src/`: Python scripts for preprocessing, feature selection, and modeling
- `models/`: Trained model and associated metadata
- `results/`: Figures and performance metrics
- `docs/`: Additional documentation on methodology and ethical considerations

## Requirements
To run the code in this repository, you'll need Python 3.8+ and the following libraries:
- pandas
- numpy
- scikit-learn
- lightgbm
- shap
- matplotlib
- seaborn

You can install all dependencies using:
pip install -r requirements.txt

## Usage
1. Clone the repository:

git clone https://github.com/frpcarvalho/OrthoMortPred.git

2. Install dependencies:

pip install -r requirements.txt

3. Run the notebooks in numerical order to reproduce the analysis.

## Methodology
The study employed machine learning techniques, specifically the LightGBM classifier, to develop a predictive model. Feature selection was performed using the SelectFromModel method with GradientBoostingClassifier. Model performance was evaluated using cross-validation and metrics such as precision, recall, and AUC-ROC.

## Key Findings
- Overall model accuracy: 93%
- AUC-ROC: 0.93
- Top predictors: emergency admission date and time, age, and pre-operative days

## Ethical Considerations
This study was approved by the Ethics Committee of the Central Lisbon University Hospital Center. All data were anonymized prior to analysis to protect patient privacy.

## Contact
For questions or collaborations, please contact Corresponding author: Filipe Ricardo Carvalho frcarvalho@ualg.pt


## Citation
under publication



## License
This project as no license
