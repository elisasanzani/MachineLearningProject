# Z boson decay classification
Repository with my project for Advanced Machine Learning PhD exam. 

I am tackling the classification problem of the Z boson decays into 2 electrons or 2 muons. 

Details of the dataset and the data selection can be found in the [Colab Notebook](https://github.com/elisasanzani/MachineLearningProject/blob/main/Zboson_decay.ipynb) present in this repository, where also the code is presented.

The used datasets (10000 events each) are present in this repo and downloaded from here also in the Notebook.

## Notebook structure

- Data preparation: the datasets are merged and shuffled. The target labels are created
- Data visualisation: the features distributions are studied and if needed modified to increase their separation
- Classifiers implementation: three classifiers are implemented and then separately improved (via grid search methods) to evaluate the best performing one
- Neural Network implementation: a NN is implemented and its performance is optimised and tested

 
