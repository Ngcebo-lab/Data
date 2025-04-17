Computational Drug Discovery: From PubChem to Machine Learning

Overview

This repository contains a Jupyter Notebook workflow for collecting, cleaning, and processing molecular bioactivity data from the PubChem database, preparing it for machine learning applications in drug discovery.

The pipeline includes:

•	Retrieval of bioactivity data using pubchempy

•	Preprocessing and curation of SMILES and pIC50 values

•	Evaluation of drug-likeness using Lipinski’s Rule of Five

•	Calculation of molecular descriptors using PaDEL-Descriptor

•	Structuring the dataset for supervised ML modeling

Features

•	Download Bioactivity Data from PubChem by compound identifiers (CIDs)

•	 Extract & Align Molecular Data using SMILES and activity labels (pIC50, bioactivity class)

•	Clean and Structure the dataset for compatibility with ML pipelines

•	Perform EDA (Exploratory Data Analysis) on drug-likeness properties

•	Calculate Molecular Descriptors using PaDEL-Descriptor (Java-based tool)

•	Prepare Machine Learning Datasets for classification and regression tasks

Installation

To run this notebook, ensure you have Python and Java installed along with the required dependencies:

bash

CopyEdit

pip install pubchempy pandas numpy matplotlib seaborn rdkit

PaDEL-Descriptor (Java) is also required. Download it here:

 https://github.com/ecrl/padelpy#installing-padel-descriptor

Usage

Clone this repository:

bash

CopyEdit

git clone https://github.com/your-username/repository-name.git

cd repository-name

Open the Jupyter Notebook:

bash

CopyEdit

jupyter notebook "collection and pre-processing of pubchem data.ipynb"

Follow the steps to:

1.	Download and process bioactivity data from PubChem
   
3.	Match CIDs with SMILES and activity values
   
5.	Clean the dataset and evaluate drug-like properties
   
7.	Generate molecular descriptors using PaDEL
   
9.	Save a clean descriptor matrix and labels for ML modeling

Data Source

Data is retrieved from PubChem — the world’s largest free chemical database.

Contributing
Interested in contributing or collaborating? Feel free to fork the repo, open an issue, or submit a pull request.

License
This project is licensed under the MIT License – see the LICENSE file for details.

