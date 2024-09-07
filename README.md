# DSML Template Repository

This is a basic template repository for DSML projects, built using Miniconda as the package manager and utilizing Docker for reproducibility.

## Prerequisites

Before using this template, you need to have the following installed on your system:

* Miniconda: This is the light-weight version of Anaconda that we'll use to manage our project dependencies. You can download it from the [official Miniconda website](https://docs.conda.io/en/latest/miniconda.html).
* Docker: This is a containerization platform that will help us create reproducible environments for our projects. You can install Docker using the instructions on the [official Docker website](https://www.docker.com/get-started).

## Getting Started

1. Install Miniconda and follow the prompts to create a new environment.
2. Create a new directory for your project and navigate into it in your terminal.
3. Clone this repository into your project directory using `git clone`.
4. Run `conda env create -f environment.yml` to create a new environment based on the configuration in `environment.yml`.
5. Activate the new environment using `source activate dsml` (on Linux/Mac) or `activate dsml` (on Windows).
6. You're now ready to start working on your project!

## Dependencies

The `environment.yml` file specifies the following dependencies:

* Python 3.12
* Linters and formatters: PyLint, Flake8, Isort, Black
* Testing framework: pytest
* Data science libraries: NumPy, Pandas, Seaborn
* Jupyter notebook

**License**

This repository is released under the [MIT License](https://opensource.org/licenses/MIT).

