# [SEC-302] Assignment 1 - AI Training Pipeline Attacks and Defenses
For this assignment, we will use `uv` as a package and project manager to make sure we use the same python and dependency versions. `uv` is a single tool to replace `pip`, `pip-tools`, `pipx`, `poetry`, `pyenv`, `twine`, `virtualenv`, and more. If you haven't tried `uv` before, head over to the website to check it out and install the software:
https://docs.astral.sh/uv/

## Starting the assignment
First, if you don't have python 3.11 natively installed, run the following:
```
uv python install 3.11
```
Next, install and lock all the dependencies as listed in `pyproject.toml`:
```
uv lock
```
Then, run Jupyter Notebook
```
uv run --with jupyter jupyter notebook
```
Complete Task A in `task_a.ipynb` and Task B in `task_b.ipynb`.
