# Building Machine Learning Models on Carbohydrolytic-active Enzymes


## Description
- CS286CazymesGridSearch.ipynb contains the code for training each Multilayer Perceptron (MLP) model. Upload and run in Google Colab
- CS286_Enzymes_In_Cow_Rumen.ipynb contains the code for other ML techniques we tried such as SVM, Random Forest, etc. Upload and run in colab colab as well.
- fastaData.zip contains all of the fasta files used to train the MLP models. Upload to Google Drive for running with CS286CazymesGridSearch.ipynb or CS286_Enzymes_In_Cow_Rumen.ipynb
- mlpModelWeights.zip contains the MLP weights trained using the above dataset and code. Models are sklearn MLPClassifiers and can be loaded using pickle. Example below.
```
import pickle
classifier = pickle.load(open(mlpFilePath, 'rb'))
```


## About
This repository is the code and dataset files for the final project for CS286: Topics in Sequence-based Machine Learning
for Bioinformatics. Instructor: William “Bill” Andreopoulos

The group members are David Bui and Sushant Mane 

The code maybe used for educational and commercial use under no warranties. For questions on this project and code please reach out to: david.bui01@sjsu.edu