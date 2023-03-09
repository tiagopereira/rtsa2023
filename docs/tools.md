# Software and Tools


## Programming language

This course can be followed using the Python programming language.

Besides the programming language used to run code, jupyter notebooks have a text component using the Markdown language. It will be used extensively in your project reports, and you are encouraged to get more familiar with it. The [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is a good reference. Familiarity with LaTeX is also important, but mostly to write equations, which can be included in Markdown using LaTeX syntax.

## Jupyter


We will make extensive use of Jupyter notebooks and widely-used python packages. If you don't currently have it, it is strongly recommended you install a python environment in your laptop, and bring it to all classes, also lectures! 

The recommended way to install the necessary packages is through conda (or mamba) from the conda-forge channel. *Installing through pip will most likely lead to problems, especially if you use Windows.* You can install the necessary packages into a new conda environment using the [`environment.yml`](https://github.com/tiagopereira/rtsa2023/blob/master/environment.yml) from the repository, using `conda env create -f environment.yml`.

If you are unfamiliar with installing python environments, we will help you out in the first week.

??? warning "Python 3.11 is not recommended"
    During the later stages of the course we will use [`numba`](https://numba.pydata.org/) to speed up calculations with python. At the time of writing, `numba` does not work with the latest 3.11 python version. We recommend you use python 3.10 or 3.9 for the course.

