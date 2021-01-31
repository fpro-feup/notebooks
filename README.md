# Notebooks

FPRO Notebooks to study before classes and to use during the class.

> See in the [Preface](00-preface.ipynb) how to download the notebooks and how to open your working copy.

## Development

The following instructions are relevant if you want to setup the [jupyterbook](https://jupyterbook.org/intro.html) environment used for the [Github Pages action](https://github.com/fpro-feup/notebooks/blob/master/.github/workflows/gh-pages.yml). __Kids__, this mean you probably won't need this.

### Prerequisites
- Python 3.0+
- pip
- virtualenv (optional)

### Install Dependencies

```shell
# setup virtual environment (optional)
$ virtualenv venv # only needed the first time 
$ source venv/bin/activate

# install dependencies
$ pip install -r ci-requirements.txt 
```

### Useful Commands

```shell
# build the book
$ jupyter-book build .
```

For additional commands and options checkout [jupyterbook's docs](https://jupyterbook.org/start/build.html).

