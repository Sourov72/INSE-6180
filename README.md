# INSE 6180 Project - Network Intrusion Detection Project

This repository contains code and resources for a network intrusion detection project that explores various feature engineering techniques and their impact on deep learning models, focusing on the Anomal-E graph neural network (GNN) model.

## Project Overview
The primary goal of this project is to investigate how feature selection and feature fusion affect the performance of deep learning models for network intrusion detection. We implemented strategic feature engineering to assess its impact on detection accuracy, using the Anomal-E model as a case study.

## Repository Contents
- **decision_tree_with_xg_boosting.ipynb.ipynb**: The Jupyter Notebook where we implemented feature selection using Decision Tree classifier with and without XGBoosting to choose important features.
- **fusion_network.ipynb**: The Jupyter Notebook where we implemented the feature fusion technique with DL method.
- **Improved_Anomal_E_cicids2018_v2.ipynb**: The Jupyter Notebook where we implemented various improvements and tests on the Anomal-E model.
- **anomal_e_venv_requirements.txt**: The requirements file for the Conda virtual environment used for running the `Improved_Anomal_E_cicids2018_v2.ipynb` Jupyter Notebook.
- **README.md**: This README file.

## Getting Started
To set up the Conda virtual environment and run the code, follow these steps:

1. **Clone the repository**:
      ```bash
      git clone https://github.com/Sourov72/INSE-6180.git
      ```

2. **Install dependencies**:
   Navigate to the repository directory and create the required Conda environment.
     ```bash
     cd INSE-6180
     conda create --name anomal_e_env --file anomal_e_venv_requirements.txt
     conda activate anomal_e_env
      ```
3. **Run the code**:
After activating the environment, you can execute the Jupyter Notebook Improved_Anomal_E_cicids2018_v2.ipynb or other scripts in the repository.

## Original Anomal-E Code
The original Anomal-E code can be found [here](https://github.com/waimorris/Anomal-E). This repository contains the baseline code on which this project is based.




