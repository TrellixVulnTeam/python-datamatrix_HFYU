title: Install

## Dependencies

`DataMatrix` runs on Python 2 and 3, and requires only the Python standard library. That is, you can use it without installing any additional Python packages.

The following packages are required for extra functionality:

- `fastnumbers` for improved performance
- `numpy` and `scipy` for using the `FloatColumn`, `IntColumn`, and `SeriesColumn` objects
- `prettytable` for creating a text representation of a DataMatrix (e.g. to print it out)
- `openpyxl` for reading and writing `.xlsx` files
- `json_tricks` for hashing, serialization to and from `json`, and memoization (caching).
- `pandas` for conversion to and from `pandas.DataFrame`.

## Installation

### PyPi (pip install)

~~~bash
pip install python-datamatrix
~~~

Optional dependencies:

~~~bash
pip install fastnumbers numpy scipy prettytable openpyxl pandas json_tricks
~~~


### Anaconda

~~~bash
conda install -c conda-forge datamatrix
~~~

Optional dependencies:


~~~bash
conda install -c conda-forge scipy pandas json_tricks
~~~


### Ubuntu

~~~bash
sudo add-apt-repository ppa:smathot/cogscinl
sudo apt-get update
sudo apt install python3-datamatrix
~~~


## Source code

- <https://github.com/smathot/python-datamatrix>
