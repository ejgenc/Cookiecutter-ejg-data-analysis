# Personal Data Analysis/Science Project Template

This is a Cookiecutter template that i personally use for my data analysis/science projects. The template is based on a version of the ![DrivenData Cookiecutter Data Science project template.]("https://drivendata.github.io/cookiecutter-data-science/") It is a heavily simplifed version that only includes tools that facilitate Readme file creation, environment creation and DAG structure implementation.

## Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

```
$ pip install cookiecutter
```

or

```
$ conda config --add channels conda-forge
$ conda install cookiecutter
```

## To start a new project using this template:
------------

If you are using the project for the first time, run the following in a terminal:
```
cookiecutter https://github.com/ejgenc/Cookiecutter-ejg-data-analysis
```

## The resulting directory structure
------------

--------
```
    ├── LICENSE            < - License for the codes responsible in creating this data analysis projects.
    |
    ├── README.md          <- The top-level README for the users of this project.
    |
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling and visualization.
    │   └── raw            <- The original, immutable data dump.
    │
    │
    ├── eda_notebooks      <- Jupyter notebooks that have data explorations. These files were not created with external viewers in mind.
    |                         You can explore them if you wish. However, a good viewing experience is not promised.
    |
    |
    |── media              <- Contains internally generated figures and external photos. Internally generated figures come with a license.
    |    ├── external_media <- Images and media downloaded from third party resources. A .txt file of references and attribution is included.
    │    ├── figures        <- Data visualizations generated through scripts
    |                                             
    |
    |
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    |
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    |
    |
    |── self documentation <- Contains notes and checklists about various procedures.
    |
    |
    ├── src                         <- Source code for use in this project.
    │   |
    │   │
    │   ├── data_preparation        <- Scripts to download or generate data
    │   |
    |   |── data_analysis           <- Scripts to generate intermediary datasets to base visualizations on.                           
    |   |   
    │   |──data_visualization      <- Scripts to create visualizations.
    |   |
    │   └── helper_functions        <- Helper functions that help in data preparation, analysis or visualization.
    |   
    ├── tests                       <- Contains test modules that test the data analysis pipeline.
    |   |
    |   ├── unit_tests              <- Contains unit tests that test custom functions
    |   |
    |   ├── data_quality_tests      <- Contains data quality tests that test raw, processed and intermediary datasets.
    |                        
    |
    |── environment.yml    <- A .yml file for reproducing the analysis environment.
    |
    │
    |── dodo.py            <- A file that contains all the information needed to run automation package Doit. Used to implement DAG structure.
    |
    |
    |── setup.py           <- A file that contains information about the packaging of the code.
    |
    |
    |── .gitignore         <- A file to specify which folders/files will be flagged with gitignore
    |
    |── .env               <- A file that can contain sensitive information such as passwords, hash keys etc. Flagged with .gitignore.
    |                            ATTENTION! DO NOT COMMIT THIS FILE TO GIT!
    |
    |
```
--------


