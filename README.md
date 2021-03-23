# ML-project-fairness-aware-classification
ML Final Group Project, Fairness-Aware Classification Approaches, Skoltech 2021

## Requirements
For Adaptive Sensitive Reweighting model `scipydirect` was used. `scipydirect` - [a python wrapper to the DIRECT algorithm](https://scipydirect.readthedocs.io/en/latest/install.html). The quickest way to install is to type: 
```
pip install scipydirect
```
To install [scipydirect](https://github.com/andim/scipydirectyou) you will need the following prerequisites: python 2.7 or 3.x, a FORTRAN compiler such as gfortran (for example, for Mac OS X: [gcc](https://formulae.brew.sh/formula/gcc#default)), numpy, matplotlib.

## Datasets
Four datasets were used: [Adult Income Dataset](https://www.kaggle.com/wenruliu/adult-income-dataset?select=adult.csv), [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing), [COMPAS dataset](https://github.com/propublica/compas-analysis), [KDD Census income dataset](http://archive.ics.uci.edu/ml/datasets/Census-Income+(KDD)). They are also available in this repository, in Adaptive Sensitive Reweighting folder, except for KDD dataset. It could be downloaded [here](http://archive.ics.uci.edu/ml/machine-learning-databases/census-income-mld/), `census-income.data.gz` file.

## Structure
In the folder AdaFair there is a python implementation of the AdaFair algorithm proposed by [Iosifidis & Ntoutsi](https://dl.acm.org/doi/abs/10.1145/3357384.3357974)

In the folder SMOTEBoost there is a python implementation of the SMOTEBoost algorithm introduced by [Chawla et al.](https://link.springer.com/chapter/10.1007/978-3-540-39804-2_12)

In the folder Adaptive Sensitive Reweighting there is a python implementation of the ASR+CULEP model introduced by [Krasanakis et al.](https://dl.acm.org/doi/abs/10.1145/3178876.3186133)
