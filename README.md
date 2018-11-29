# Seabred

Custom plotting extras meant to go with Seaborn, for numpy arrays instead of dataframes

Sea*born* -> Sea*bred* (Get it?)

## Install

`pip install seabred`

## Use

Recommended import: `import seabred as sb`

It currently has one function: `lineplot(...)`

### [Debug] Creating/pushing to test.pypi

Compile: `python3 setup.py sdist bdist_wheel`

Initial test push: `twine upload --repository seabred dist/*`