# tda_book_notebooks
This repository contains Jupyter notebooks accompanying TDA book

# how-to

* create and activate working environment

```
conda env create -f environment.yml --prefix conda-env
conda activate conda-env
```

* view a notebook, do some work

example:

```
jupyter notebook gaussians_qct_intro.ipynb
```

If you access the notebook for the first time, and see the request for password,
then copy-paste the link given in the terminal to your browser.
This will set a cookie in your browser and you won't need to use the token again
([explanation](https://jupyter-notebook.readthedocs.io/en/stable/security.html)).

* deactivate environment

```
conda deactivate
```

