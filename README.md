<h1 align="center">Python Project Template</h1>

<p align="center">
<a href="https://github.com/tyrionhuu/python-project-template/blob/main/LICENSE"><img alt="License: MIT" src="https://black.readthedocs.io/en/stable/_static/license.svg"></a>
<a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
</p>
This is a repository for Python project templates, with Poetry as the package management tool.
It uses black and isort to reformat the code. And flake8 is used to detect potential faults and format inconsistencies.

## Prerequisites

This project uses [Poetry](https://python-poetry.org/) for dependency management. You can install it following the instructions [here](https://python-poetry.org/docs/#installation).

Python 3.13 is required to run this project to avoid compatibility issues.

As for the virtual environment, you can use any tool you like.

It is not necessary but totally fine to use [Conda](https://docs.conda.io/en/latest/) to manage the Python environment. You can install it following the instructions [here](https://docs.conda.io/en/latest/miniconda.html).

## Steps

1. Clone this repository

    ``` shell
    git clone git@github.com:tyrionhuu/python-project-template.git
    cd python-project-template
    ```

2. Create a virtual environment

   1. **conda**
   
    ``` shell
    conda create -n python-project-template python=3.13
    conda activate python-project-template
    ```
   
   2. **poetry**
   
    ``` shell
    poetry env use python3.13
    poetry shell
    ```
   
3. Install the dependencies with Poetry

    ``` shell
    poetry install
    ```

    Then Poetry should already activate the virtual environment for you. If not, you can activate it manually.

4. Install the pre-commit hooks, which is optional

    ``` shell
    pre-commit install
    ```
