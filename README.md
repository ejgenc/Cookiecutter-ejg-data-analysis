# Personal Data Analysis/Science Project Template

This is a Cookiecutter template that i personally use for my data analysis/science projects. The template is based on a version of the ![DrivenData Cookiecutter Data Science project template.]("https://drivendata.github.io/cookiecutter-data-science/") It is a heavily simplifed version that only includes tools that facilitate Readme file creation, environment creation and DAG structure implementation.

## Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```

## To start a new project, run:
------------

    cookiecutter https://github.com/GITHUB LINK


## The resulting directory structure
------------

The directory structure of your new project looks like this: 

--------
```
    ├── LICENSE            < - License for the codes responsible in creating this data analysis projects.
    |
    |
    |
    ├── README.md          <- The top-level README for developers using this project.
    |
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
        ├── external_media <- Images and media downloaded from third party resources. A .txt file of references and attribution is included.
    │   ├── figures        <- Data visualizations generated through scripts
    |                                             
    |
    |
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │
    |
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    |
    |
    |── environment.yml    <- A .yml file for reproducing the analysis environment.
    |
    │
    |── dodo.py            <- A file that contains all the information needed to run automation package Doit.
    |
    ├── src                         <- Source code for use in this project.
    │   |
    │   │
    │   ├── data_preparation        <- Scripts to download or generate data
    │   │   └── prepare_data.py     <- Final script to run all cleaning and prepration subscripts.
    |   |
    |   |── data_analysis           <- Scripts to generate intermediary datasets to base visualizations on.                           
    |   |   └──analyze_data.py      <- Final script to run all analysis subscripts.
    │   │
    │   └── visualization           <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize_data.py   <- Final script to run all visualization subscripts.
```
--------


