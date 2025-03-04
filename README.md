Computational Drug Discovery: Download Bioactivity Data

Overview

This repository contains a Jupyter Notebook for collecting and preprocessing bioactivity data from the PubChem database. The workflow utilizes pubchempy to retrieve chemical and biological data, aiding computational drug discovery research.

Additionally, exploratory data analysis (EDA) is performed by evaluating drug-likeness using Lipinski's Rule of Five and extended drug-like descriptors.

Features

Accesses the PubChem database to retrieve bioactivity data.

Preprocesses collected data for further computational analysis.

Performs exploratory data analysis (EDA) on drug-like properties.

Evaluates Lipinski's Rule of Five and extended drug-like descriptors.

Includes installation and setup instructions for required dependencies.

Installation

To run this notebook, ensure you have Python installed along with the required dependencies:

pip install pubchempy pandas numpy matplotlib seaborn rdkit

Usage

Clone this repository:

git clone https://github.com/your-username/repository-name.git
cd repository-name

Open the Jupyter Notebook:

jupyter notebook "collection and pre-processing of pubchem data.ipynb"

Run the cells step by step to:

Download and process bioactivity data.

Perform exploratory data analysis (EDA) on drug-like properties.

Evaluate compounds using Lipinski’s Rule of Five.

Data Source

This project retrieves data from PubChem, which is the world's largest freely accessible chemical information database.

Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.
