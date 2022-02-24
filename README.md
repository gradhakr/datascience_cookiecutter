# Cookiecutter template for DS/ML/AI projects
Cookiecutter template for Data Science projects - template assumes a prototyping phase (using Jupyter notebooks) and a productionising phase.

## Prerequisites
The main prerequisite is to have cookiecutter installed. Instructions on how to install and use cookiecutter are available [here](https://github.com/cookiecutter/cookiecutter).

## Usage instructions
The template can be used by issuing the following command:
```
cookiecutter gh:gradhakr/datascience_cookiecutter
```

You will then be asked to provide a name for the project (which will also be the parent project folder name - so best to not use any spaces here) as well as other project-related info that will be used to auto-populate the README template.

This cookiecutter creates the following file/folder structure for you to work with:
```
datascience_project/
├── config
├── data
│   ├── db
│   ├── external
│   ├── interim
│   ├── processed
│   └── raw
├── environment.yml
├── Makefile
├── models
├── notebooks
├── plots
├── README.md
├── reports
├── requirements.txt
├── scripts
└── src
```

>_**Note:**_ The .gitignore provided within the template is empty (by design). You will need to populate it according to your use case. A default github python .gitignore (as of 24th Feb 2022) is provided in the parent folder of this repo.

