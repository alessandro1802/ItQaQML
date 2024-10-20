# Introduction to Quantum Information and Quantum Machine Learning

## Set-up
```shell
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Convert to pdf
Install `pandoc` and [TeX](https://nbconvert.readthedocs.io/en/latest/install.html#installing-tex) e.g.:
```shell
brew install pandoc
brew install --cask mactex
```

Convert a notebook to pdf with:
```shell
jupyter-nbconvert --to pdf path_to_notebook.ipynb
```
