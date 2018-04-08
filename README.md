# Installation instructions for Python4Scientists Tutorial	

### Install Python using Anaconda

You first need a distribution of python, download and install the Anaconda 3.6 distribution which you can get from [here](https://www.anaconda.com/downloads).

### Get the Python4Scientists repository from Github

Clone the [Python4Scientists](https://github.com/nejaz1/Python4Scientists) repository onto your system using the following commands. For example, in  MacOSX open up a terminal window and go to the directory you want to install Python4Scientists in and type the following commands:

```
mkdir Python4Scientists
git clone git@github.com:nejaz1/Python4Scientists.git
```

### Create encapsulated environment to work in

Use the condo package manager to setup a new environment and install the package dependencies specified in the `environment.yml` file using the following commands in terminal:

```
cd Python4Scientists
conda env create -f environment.yml
```

### Run the Spyder python environment

Switch to the newly created environment and run `sypder` using terminal:

```
source activate pythontutorial
spyder
```



