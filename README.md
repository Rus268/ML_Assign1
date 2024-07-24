# ML_Assign1

## Description

This is a Machine Learning project base on the assignment 1 requirement for the assignment of machine learning in RMIT University Master of AI degree

## Goal

The goal is to simulate a end to end machine learnin project and select and train a machine learning model that capable of addressing the task:

> “Predict if a given in ICU would not develop a sepsis (Sepsis Negative / class 0) or
> will develop sepsis (Sepsis Positive / class 1) during their ICU stay.”

## Dependencies

Include in the project folder is the YAML file that include all the dependencies for the notebook to run properly. 

It it is recommend to use conda to manage all of the dependencies to avoid any issues. If you don't have conda please follow the instruction on https://docs.anaconda.com/miniconda/ to install on your system. Once done on you shell enter.

```shell
conda env create -f environment.yml
conda activate myenv
 ```

The environment file use "myenv" for the environment name when create as default. If you wished to replace it please feel free to do so just ensure to replace the conda activate <env_name> with your own environment name.
