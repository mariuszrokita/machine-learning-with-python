# Introduction
...

# Getting started

## Virtual environment

```shell
conda create --name mlpython python=3.7 jupyter
conda activate mlpython
```

## Install dependencies

```shell
pip install --upgrade pip
pip install -r requirements.txt
```

It is also worth installing the Jupyter Notebook Extensions:

```shell
pip install jupyter_contrib_nbextensions && jupyter contrib nbextension install
```