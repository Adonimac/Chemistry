# Chemistry
PGDip Data Science in Chemistry
Solubility Prediction

Project Overview
This assignment uses SMILES string embeddings and molecular descriptors to predict the aqueous solubility (LogS) of chemical compounds. The chemical descriptors in the model are computed using RDKit and the RandomForestRegressor from scikit-learn.

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
pip install rdkit-pypi deepchem dgl

Run the Notebook:

Once the dataset is uploaded, run each cell in the notebook sequentially. The notebook includes code for data exploration, preprocessing, model training, evaluation, and visualization.
Analyze the Results:

Review the output, including metrics, Mean Squared Error, Root Mean Squared Error,R-Squared and feature importance analyses.

Dependencies
The project uses the following Python libraries:

pandas
numpy
scikit-learn
matplotlib
rdkit
deepchem
dgl


These libraries are available in Google Colaboratory by default. If you are running the notebook on a different platform, ensure these dependencies are installed. You can install them using the following commands:

pip install pandas==2.0.3 numpy==1.24.3 scikit-learn==1.3.0 matplotlib==3.7.1 seaborn==0.12.2

_________________________________________________


