# JODA course project
This project has been implemented as a single Jupyter notebook.
This project utilizes data from [Inside Airbnb](http://insideairbnb.com/). The purpose of this project is to analyze and visualize data from Airbnb listings. The goal is to analyze the correlation between different variables from the data, and to find out which variables have the most effect on user reviews. The accuracy of the results are attempted to be analyzed by machine learning techniques.

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

