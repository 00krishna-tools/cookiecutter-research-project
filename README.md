
# New Research Project Template

This is a simple directory structure for developing new applied math, statistics, or machine learning projects. I
do not keep the code in this repository--other than perhaps some notebooks. Most of the code is developed in packages. 
This repository contains a journal and agenda and other project management items. The documents are written in emacs
org-mode.

### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5+
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/drivendata/cookiecutter-data-science


[![asciicast](https://asciinema.org/a/9bgl5qh17wlop4xyxu9n9wr02.png)](https://asciinema.org/a/9bgl5qh17wlop4xyxu9n9wr02)


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── {{cookiecutter.repo_name}}
│   ├── data
│   │   ├── external
│   │   ├── interim
│   │   ├── processed
│   │   └── raw
│   ├── docs
│   │   ├── data_sources_{{cookiecutter.repo_name}}.org
│   │   └── wiki_{{cookiecutter.repo_name}}.org
│   ├── models
│   ├── notebooks
│   ├── project_management
│   │   ├── agenda_{{cookiecutter.repo_name}}.org
│   │   └── journal_{{cookiecutter.repo_name}}.org
│   ├── README.md
│   ├── references
│   └── reports
│       └── figures
├── LICENSE
└── README.md

```


