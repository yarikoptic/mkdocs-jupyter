# mkdocs-jupyter: Use Jupyter Notebooks in mkdocs

[![PyPI version](https://badge.fury.io/py/mkdocs-jupyter.svg)](https://pypi.org/project/mkdocs-jupyter)
[![Python package](https://github.com/danielfrg/mkdocs-jupyter/workflows/Python%20package/badge.svg)](https://github.com/danielfrg/mkdocs-jupyter/actions)

- Add Jupyter Notebooks directly to the mkdocs navigation
- Feel and look the regular Jupyter Notebook style inside mkdocs pages
- Option to execute the notebook before converting
- Show ipywidgets (requires execution of the notebook)
- Support for mkdocs TOC

![mkdocs-jupyter](https://raw.githubusercontent.com/danielfrg/mkdocs-jupyter/master/screenshot.png)

## Usage

```
pip install mkdocs-jupyter
```

In your `mkdocs.yml`:

```
nav:
- Notebook: notebook.ipynb

plugins:
  - mkdocs-jupyter
```
