# Class Contrastive Explanations and Generating Complex Stories from Machine Learning Models

In order to provide a better explanability for machine learning models in healthcare are, we provide an implementation for class contrastive analysis for Pima dataset.

Class contrastive analysis is a technique to explain black-box machine learning models [1].

In addition to this approach, Mark W. Craven and Jude W. Shavlik proposed extracting Thee-Structured representations of trained networks in 1993.

We use the TREPAN implementation in "Extracting tree-structured representations of trained networks" : Craven,Shavlik 1993 from github user: @abarthakur.

https://github.com/abarthakur/trepan_python


# Quick Installation

Install Anaconda (Python distribution)

and install all packages by running the following command at the Terminal

```python

pip install -r requirements.txt

```


# Data

Download the data from

https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database


# Files

The script `simple_2D__pima_heatmap.ipynb` does the following things:

1. Trains a simple 3-layer neural network on the pima dataset
2. Provides Data centric explanation like outlier detection
3. Provides double feature class contrastive analysis


Figure 3.1 is generated in `pima_heatmap.ipynb`.

Figure 4.1 is generated from `pima_heatmap.ipynb`.

Figure 4.2 is generated from `2D_pima_heatmap.ipynb`.

Figure 4.3 is generated from `3D_pima_heatmap.ipynb`.

Figure 4.4 is generated from `4D_pima_heatmap.ipynb`.

Figure 4.7 is generated from `2D_pima_heatmap.ipynb`.

Figure 4.8 is generated from `opposite2D_pima_heatmap.ipynb`.



# Manuscript and citation

Forthcoming


# Contact

Yujia Yang and Soumya Banerjee

sb2333@cam.ac.uk


# References

1. Banerjee S, Lio P, Jones PB, Cardinal RN (2021) A class-contrastive human-interpretable machine learning approach to predict mortality in severe mental illness. npj Schizophr 7: 1–13.

