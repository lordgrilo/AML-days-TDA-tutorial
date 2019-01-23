# AML-days-TDA-tutorial

Resources for the tutorial on Topological Data Analysis at [Applied Machine Learning Days 2019](http://appliedmldays.org/). 


## Workshop summary
We will introduce elements of the theory of topological data analysis (TDA) and show the participants how to apply standard topological data pipelines, such as persistent homology and Mapper, to datasets of different origin (spatial data, word embeddings, brain networks). We will also show how TDA can be used for feature engineering or as a preprocessing step in standard machine learning pipelines, and how to assess the significance of the unearthed features. Finally, since TDA outputs can sometimes be of difficult interpretation, we will guide the participants through some common pitfalls in the interpretation and provide some examples of successful applications. 


## Instructions
 - I recommened downloading the repository before the tutorial and check the required packages (below). 
 Note that the ```data``` folder is heavy (around 300mb) due to the dataset of fMRI timeseries. It will be useful during the workshop, but you might want to download only some of the timeseries in case you have issues with space.
 - **Notebooks and more material will be uploaded shortly before the tutorial on Saturday 26th.**

## Requirements
Please install the following packages (stay tuned the list might grow...):

- Jupyter notebook
- [scikit-tda](https://scikit-tda.org)
- [dionysus2](http://mrzv.org/software/dionysus2/)
- Cython
- ripser
- ipywidgets
- keras
- plotly
- umap
- pillow