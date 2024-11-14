# Chemistry
PGDip Data Science in Chemistry
Using RDKit

Project Overview
This project involves analyzing various chemical molecules using SMILES strings and generating molecular properties such as atomic weights, number of atoms, valence electrons, and aromatic bonds. The chemical descriptors are computed using RDKit, and molecular data is retrieved from PubChem using PubChemPy. The goal is to provide a comprehensive analysis of molecular structures and visualize them using RDKit's visualization tools.

Instructions for Running the Project

To run this project, follow these steps:

1. Setting Up the Environment
Clone the Repository or Download the Files:

Clone the repository or download the project files to your local machine.
Open Google Colaboratory:

Open Google Colaboratory in your web browser.

Upload the ipynb file:
Upload the ipynb file (Assignment2Chem.ipynb) to your Google Collab session.

2. Uploading the Dataset
Upload the solubility.csv File:

The dataset used in this project is stored in the submission folder and is called solubility.csv. To upload this file to your Colaboratory session:
Click on the "Files" tab on the left-hand side of the Colaboratory interface.
Click on the "Upload" button and select the solubility.csv file from your local machine.

3. Running the Code

Before running the notebook, ensure that you have the following Python packages installed:
pip install rdkit-pypi
pip install pubchempy

Run the Notebook:

Once the dataset is uploaded, run each cell in the notebook sequentially. The notebook includes code for data exploration and visualization.

Analyze the Results:

Review the printed molecular properties and the visualized molecular structures. Analyze the chemical formulas and other computed descriptors to gain insights into the molecular data.

Dependencies
The project uses the following Python libraries:

pandas
numpy
matplotlib
rdkit
pubchempy


These libraries are available in Google Colaboratory by default. If you are running the notebook on a different platform, ensure these dependencies are installed. You can install them using the following commands:

pip install pandas==2.0.3 numpy==1.24.3 scikit-learn==1.3.0 matplotlib==3.7.1 

Conclusion

This project demonstrates the application of RDKit and PubChemPy for molecular analysis and visualization. By following the instructions above, you can replicate the analysis and explore the molecular properties and structures of various chemical compounds.

_________________________________________________


