# optimal_tensor_basis

# Overview
This code accompanies the paper "On the generalizability of data-driven turbulence modelling" by Ryley McConkey, Eugene Yee, and Fue-Sang Lien. For more information, please see the manuscript.

# Files
All work was completed in the notebook `optimal_tensor_basis.ipynb`. The notebook is organized by sections, from data preprocessing to generating the plots in the paper. 

# Data
The main data source is `komegasst.csv`, from Version 4 of this dataset: [https://www.kaggle.com/datasets/ryleymcconkey/ml-turbulence-dataset](https://www.kaggle.com/datasets/ryleymcconkey/ml-turbulence-dataset) The geometry data used for plot generation is provided in the `plots` folder for convenience, but is not necessary for machine learning.

# Dependencies 
The conda environment was frozen into `requirements.txt`. These requirements should be sufficient for running all of the machine learning code. Note that we used a docker container (`tensorman` on Pop!_OS) for GPU enabled tensorflow computations. The conda environment can be created from the requirements file using `conda create --name <envname> --file requirements.txt`






