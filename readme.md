# CompBioAsia 2023
## Introduction to Machine Learning Workshop - Exploring small molecule potency

by [@carlosmr12](https://twitter.com/carlosmr12)

## Colab Notebooks

The material is divided into classification and regression and can be accessed via [Google Colab Notebooks](https://colab.research.google.com/github/carlosmr12/compbioasia2023/blob/master/lecture1_classification.ipynb).

## Local installation

Alternatively, if you want to run it locally, we suggest you use [anaconda](https://docs.anaconda.com/free/anaconda/install/) (or [miniconda](https://docs.conda.io/en/latest/miniconda.html)) to manage a virtual environment and install dependencies.

1. First create an environment with the following command:

```bash
$ conda create -n compbioasia
```

2. Then, install dependencies via pip:


```bash
$ conda activate compbioasia

$ conda install python=3.10

$ pip install -r requirements.txt
```

3. And finally, running the notebook

```bash
$ conda activate compbioasia

$ jupyter lab
```
