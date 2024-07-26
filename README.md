# ML_Assign1

## Description

This is a Machine Learning project base on the assignment 1 requirement for the assignment of machine learning in RMIT University Master of AI degree

## Goal

The goal is to simulate a end to end machine learnin project and select and train a machine learning model that capable of addressing the task:

> “Predict if a given in ICU would not develop a sepsis (Sepsis Negative / class 0) or
> will develop sepsis (Sepsis Positive / class 1) during their ICU stay.”

## Set Up Using Conda (recommended)

Include in the project folder is the YAML file that include all the dependencies for the notebook to run properly.

It it is recommend to use conda to manage all of the dependencies to avoid any issues. If you don't have conda please follow the instruction on https://docs.anaconda.com/miniconda/ to install base on your system requirement. Once done on you shell enter.

```shell
conda env create -f environment.yml
conda activate myenv
 ```

The environment file use "myenv" for the environment name when create as default. If you wished to replace it please feel free to do so just ensure to replace the conda activate <env_name> with your own environment name.

## Using Python Virtual Environment

In case the above method does not work or the method above does not work you can create a new Python virtual environment using the provided requirements.txt

If you prefer to use requirements.txt or if the above method does not work, you can create a new Python virtual environment and install the dependencies from requirements.txt.

### Windows

1. Create a Virtual Environment:

```shell
python -m venv myenv
```

2. Activate the Virtual Environment:

```shell
myenv\Scripts\activate
```

3. Install Dependencies:

```shell
pip install -r requirements.txt
```

### Linux and macOS

1. Create a Virtual Environment:

```shell
python3 -m venv myenv
```

2. Activate the Virtual Environment:

```shell
source myenv/bin/activate
```

3. Install Dependencies:

```shell
pip install -r requirements.txt
```