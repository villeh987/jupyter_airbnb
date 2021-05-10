# JODA course project
This project has been implemented as a single Jupyter notebook.

## How to run the notebook
**NOTE**: It is recommended to install the requirements using Conda in a virtual environment. Otherwise there could be problems with some dependencies. You also have to have jupyter notebook installed

1. Clone repo / unzip files

2. Create conda virtual environment, install requirements and activate the environment
`````
conda create -y --name myenv python=x.x
conda install -y -q -c conda-forge --name myenv --file requirements.txt
conda activate myenv
`````

3. Install jupyter notebook in the virtual environment

````
conda install jupyter 
````

4. Run the notebook with

````
cd PROJECT_FOLDER
jupyter notebook JODA.ipynb
````

