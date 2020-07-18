# Reccommendations-with-IBM

This repository contains code analyzing user interactions with articles on the IBM Watson Studio platform,
and also make recommendations of new articles users might be interested in.

### Table of Contents
1. [Prerequisites](#prerequisites)
2. [Data](#data)
3. [Files](#Files)
4. [Acknowledgements](#acknowledgements)

### Prerequisites<a name="prerequisites"></a>

*Steps to install*
- Install anaconda to manage your data environment [here](https://www.anaconda.com/products/individual)
- run conda -V on your terminal to confirm conda is installed and its in your path 
- To create conda environment with a specific python version run `conda create -n reccommendations-env python=3.7`
- To activate the virtual environment run `conda activate reccommendations-env`  or `source activate reccommendations-env`
- Next, you can add your virtual environment to Jupyter by running: `python -m ipykernel install --user --name=reccommendations-env`
- Check if its among the kernel list with `jupyter kernelspec list`
- conda install jupyter to install jupyter notebook
- run `conda install pip`
- check the `requirements.txt` file for the prerequisites
- run `pip install -r requirements.txt` to install necessary packages
- run `jupyter notebook` to start the interactive environment


### Data<a name="data"></a>
There are two categories of datasets utilized in this project.
articles_community.csv, user-item-interactions.csv

### Files<a name="Files"></a>
- Recommendations_with_IBM.ipynb: Code implementation for the recommendation of articles to users
- Recommendations_with_IBM.html: Same as the notebook but in html format.

### Acknowledgements<a name="acknowledgements"></a>
-  [IBM Watson Studio Platform](https://dataplatform.cloud.ibm.com/)
-  [Udacity](https://www.udacity.com/)
