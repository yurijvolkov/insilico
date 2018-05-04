# Deep Feature Selection (DFS) exploration

In this work was done research about feature selection.

Our goal was to prove or to refute usefulness of DFS using our data.

DFS implemented as it described in https://pdfs.semanticscholar.org/ac2a/c075773cc936a206c3ebb2339376d586bcbd.pdf

Work was done as test task @ Insilico

## Technologies :
* **Language** : Python3.6
* **Deep learning library** : Tensorflow 1.4.1 

## Data:
Anonymized data was provided by Insilico company. 

It is located in **/data**.

Data contains 1105 samples and 1524 features. 

## Report:
Description of all experiments and statements located in **/main_text** file.

## Outcomes:
* DFS performs significantly better than Lasso if further we use neural network.
* MLP performs better with features selected by DFS then with original features.
* DFS is pretty computationally expensive.
