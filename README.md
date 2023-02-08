# Data Science Cookie Cutter template


## Tools used in this project
* [hydra](https://hydra.cc/): Manage configuration files
* [MLflow](https://mlflow.org/): An open source platform for managing the end-to-end machine learning lifecycle
* [DVC](https://dvc.org/): Data version control
* [Poetry](https://python-poetry.org/): Dependency management 
* [Prefect](https://www.prefect.io/): Orchestrate and observe your data pipeline 
* [Pydantic](https://docs.pydantic.dev/): Data validation using Python type annotations 
* [pre-commit plugins](https://pre-commit.com/): Automate code reviewing formatting
* Makefile: Create short and readable commands for repeatable tasks
* [GitHub Actions](https://docs.github.com/en/actions): Automate your workflows, making it faster to build, test, and deploy your code
* [pdoc](https://github.com/pdoc3/pdoc): Automatically create an API documentation for your project
## Project structure
```bash
.
├── data            
│   ├── final                       # data after training the model
│   ├── processed                   # data after processing
│   ├── raw                         # raw data
├── docs                            # documentation for your project
├── .gitignore                      # ignore files that cannot commit to Git
├── Makefile                        # store useful commands to set up the environment
├── models                          # store models
├── notebooks                       # store notebooks
├── .pre-commit-config.yaml         # configurations for pre-commit
├── pyproject.toml                  # dependencies for poetry
├── README.md                       # describe your project
├── src                             # store source code
│   ├── __init__.py                 # make src a Python module
│   ├── config.py                   # store configs 
│   ├── process.py                  # process data before training model
│   ├── run_notebook.py             # run notebook
│   └── train_model.py              # train model
└── tests                           # store tests
    ├── __init__.py                 # make tests a Python module 
    ├── test_process.py             # test functions for process.py
    └── test_train_model.py         # test functions for train_model.py
```

## How to use this project

Install Cookiecutter:
```bash
pip install cookiecutter
```

Create a project based on the template:
```bash
cookiecutter https://github.com/ericyaang/data-science-template
```

## Other templates

* [cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science)
  * [by Khuyen Tran](https://github.com/khuyentran1401/data-science-template)
  * [EasyData](https://github.com/hackalog/easydata)
  * [Example of a reproducible machine learning model](https://github.com/cmawer/reproducible-model)
* [Lightning-Hydra-Template](https://github.com/ashleve/lightning-hydra-template)
* [kedro](https://github.com/quantumblacklabs/kedro/)

## Resources

* [Build a Reproducible and Maintainable Data Science Project](https://khuyentran1401.github.io)
* [Made with ML](https://madewithml.com/)
