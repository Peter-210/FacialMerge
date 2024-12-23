# Facial Merge

Dataset: https://www.kaggle.com/datasets/atulanandjha/lfwpeople\

IEEE conference paper is located in repo as "conferencePaper.pdf".

## Setup Guide

### 1. Virtual Environment

Note: Python version must be 3.10. [Download from here](https://www.python.org/downloads/release/python-31011/)

Note: CMake install needed for dlib
Go to cmake.org to download and setup cmake.\
Use `cmake --version` to check if the installation was sucessful.

Everything for this step is performed within the terminal

#### Create a virtual environment - `python -m venv .venv`

#### Activate the virtual environment - `.venv/Scripts/activate`

#### Deactivate the virtual environment - `deactivate`

### 2. Installations

Download with virtual environment activated within terminal

`pip install -r requirements.txt`

### 3. Run Project

#### Web UI
Run `python webui.py` and paste the provided local URL from the terminal output your your browser.

#### Jupyter Notebooks
Open file in a juypter notebook appliction and run the project.
