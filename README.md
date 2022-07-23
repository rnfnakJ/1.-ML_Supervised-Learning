# Supervised Learning

## Pre-requisites
  * GT GitHub account
  * See [this document](README.md) on [jcha64/CS-7641_Supervised-Learning](https://github.gatech.edu/jcha64/CS-7641_Supervised-Learning/) repository
  * miniconda installed
  * Download refined data files (optionally you can find their original data files.)

### Install minicoda & make an environment to run this project.
  1. To run this project, you need to install [miniconda](https://docs.conda.io/en/latest/miniconda.html) based on your OS environment.
  2. After installing miniconda, you need to make a new environment via _**`conda env create --file environment.yaml`**_ command with [environment.yaml](environment.yaml) file.
  3. Then activate the named `AI` environment through _**`conda activate AI`**_ command.

### Download original data files and preprocess them before running the jupyter notebook script.
  1. To download original data files, you can find following URLs.
     * [default of credit card clients.xls](https://archive.ics.uci.edu/ml/machine-learning-databases/00350/default%20of%20credit%20card%20clients.xls) which comes from a [UCI ML repository](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients#).
     * [wine.csv](https://bit.ly/wine_csv_data) which comes from a [UCI ML repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)
  2. As described in the analysis document, the files are modified and refined.  You can find refined versions through following links.
     * [default of credit card clients.xls](default&#32;of&#32;credit&#32;card&#32;clients.xls)
     * [wine.csv](wine.csv)

## Run various ML jobs

### Run a jupyter notebook session.
  1. Just simply run a jupyter lab session through _**`jupyter-lab`**_ command.
  2. You can run whole cells or one by one cell to follow up each ML method after loading each jupyter notebook file.
     * [credit.ipynb](credit.ipynb): to run supervised learning methods onto [default of credit card clients.xls](default&#32;of&#32;credit&#32;card&#32;clients.xls) file.
     * [wine.ipynb](wine.ipynb): to run supervised learning methods onto [wine.csv](wine.csv) file.
