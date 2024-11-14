# Chemistry
PGDip Data Science in Chemistry
Putting it Together

Project Overview
This assignment involves analyzing hydrocarbons using their SMILES representations to predict their melting and boiling points. The project utilizes RDKit to compute molecular properties such as atomic weight and the number of aromatic rings. The goal is to build predictive regression models for melting and boiling points based on these molecular features and evaluate their performance. Visualization of model predictions and actual values is also a key component.

Instructions for Running the Project

To run this project, follow these steps:

1. Setting Up the Environment
Clone the Repository or Download the Files:

Clone the repository or download the project files to your local machine.
Open Google Colaboratory:

Open Google Colaboratory in your web browser.

Upload the ipynb file:
Upload the ipynb file (Assignment4Chem.ipynb) to your Google Collab session.

2. Uploading the Dataset
Upload the hydrocarbons.csv File:

The dataset used in this project is stored in the submission folder and is called solubility.csv. To upload this file to your Colaboratory session:
Click on the "Files" tab on the left-hand side of the Colaboratory interface.
Click on the "Upload" button and select the solubility.csv file from your local machine.

3. Running the Code

Before running the notebook, ensure that you have the following Python packages installed:
!pip install rdkit-pypi
!pip install openpyxl
!pip install pubchempy
!pip install scikit-learn

Run the Notebook:

Once the dataset is uploaded, run each cell in the notebook sequentially. The notebook includes code for data exploration and visualization.

Analyze the Results:

Review the performance of the regression models by examining metrics such as RMSE and R². Evaluate the scatter plots comparing actual and predicted boiling and melting points to gain insights into the model's predictive accuracy.

Dependencies
The project uses the following Python libraries:

pandas
numpy
matplotlib
rdkit
pubchempy
scikit-learn


These libraries are available in Google Colaboratory by default. If you are running the notebook on a different platform, ensure these dependencies are installed. You can install them using the following commands:

pip install pandas==2.0.3 numpy==1.24.3 scikit-learn==1.3.0 matplotlib==3.7.1 

Conclusion

This assignment demonstrates the application of RDKit for molecular property extraction and regression modeling for predicting boiling and melting points of hydrocarbons. By following the instructions above, you can replicate the analysis, assess the performance of different regression models, and visualize the results to understand the relationship between molecular features and thermal properties.

_________________________________________________


