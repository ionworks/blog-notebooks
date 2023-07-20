# Ionworks blog notebooks
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ionworks/blog-notebooks/blob/main/)

This repository hosts the notebooks that support the posts in the [Ionworks blog](https://ion-works.com/blog). You can either run them [in the cloud using Google Colab](https://colab.research.google.com/github/ionworks/blog-notebooks/blob/main/) or locally.

## 🚀 Installation
In order to run the notebooks locally you will need to installing a number of packages. We recommend installing within a [virtual environment](https://docs.python.org/3/tutorial/venv.html) in order to not alter any python distribution files on your machine.

PyBaMM is available on GNU/Linux, MacOS and Windows. For more detailed instructions on how to install PyBaMM, see [the PyBaMM documentation](https://pybamm.readthedocs.io/en/latest/install/GNU-linux.html#user-install).

### Linux/Mac OS
To install the requirements on Linux/Mac OS use the following terminal commands:

1. Clone the repository
```bash
git clone https://github.com/ionworks/blog-notebooks
```
2. Change into the `blog-notebooks` directory 
```bash
cd blog-notebooks
```
3. Create a virtual environment
```bash
virtualenv env
```
4. Activate the virtual environment 
```bash
source env/bin/activate
```
5. Install PyBaMM and Jupyter
```bash 
pip install pybamm jupyter
```
6. Launch Jupyter notebook
```bash 
jupyter notebook
```
7. You can check the notebooks in your browser.

### Windows
To install the requirements on Windows use the following commands:

1. Clone the repository
```bash
git clone https://github.com/ionworks/blog-notebooks
```
2. Change into the `blog-notebooks` directory 
```bash
cd blog-notebooks
```
3. Create a virtual environment
```bash
python -m virtualenv env
```
4. Activate the virtual environment 
```bash
env\Scripts\activate
```
where `env` is the path to the environment created in step 3 (e.g. `C:\Users\'Username'\env\Scripts\activate.bat`).

5. Install PyBaMM and Jupyter
```bash 
pip install pybamm jupyter
```
6. Launch Jupyter notebook
```bash 
jupyter notebook
```
7. You can check the notebooks in your browser.

As an alternative, you can set up [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/about). This allows you to run a full Linux distribution within Windows.
