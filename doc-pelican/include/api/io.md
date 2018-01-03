<div class=" YAMLDoc" id="" markdown="1">

 

<div class="FunctionDoc YAMLDoc" id="readpickle" markdown="1">

## function __readpickle__\(path\)

Reads a DataMatrix from a pickle file.

__Example:__

~~~.python 
dm = io.readpickle('data.pkl')
~~~

__Arguments:__

- `path` -- The path to the pickle file.

__Returns:__

A DataMatrix.

</div>

<div class="FunctionDoc YAMLDoc" id="readtxt" markdown="1">

## function __readtxt__\(path, delimiter=u',', quotechar=u'"', default\_col\_type=<class 'datamatrix\.\_datamatrix\.\_mixedcolumn\.MixedColumn'>\)

Reads a DataMatrix from a csv file.

__Example:__

~~~ .python
dm = io.readtxt('data.csv')
~~~

__Arguments:__

- `path` -- The path to the pickle file.

__Keywords:__

- `delimiter` -- The delimiter characer.
	- Default: ','
- `quotechar` -- The quote character.
	- Default: '"'
- `default_col_type` -- The default column type.
	- Default: <class 'datamatrix._datamatrix._mixedcolumn.MixedColumn'>

__Returns:__

A DataMatrix.

</div>

<div class="FunctionDoc YAMLDoc" id="readxlsx" markdown="1">

## function __readxlsx__\(path, default\_col\_type=<class 'datamatrix\.\_datamatrix\.\_mixedcolumn\.MixedColumn'>\)

Reads a DataMatrix from an Excel 2010 xlsx file.

__Example:__

~~~.python 
dm = io.readxlsx('data.xlsx')
~~~

__Arguments:__

- `path` -- The path to the xlsx file.

__Keywords:__

- `default_col_type` -- The default column type.
	- Default: <class 'datamatrix._datamatrix._mixedcolumn.MixedColumn'>

__Returns:__

A DataMatrix.

</div>

<div class="FunctionDoc YAMLDoc" id="writepickle" markdown="1">

## function __writepickle__\(dm, path, protocol=-1\)

Writes a DataMatrix to a pickle file.

__Example:__

~~~ .python                             
io.writepickle(dm, 'data.pkl')
~~~

__Arguments:__

- `dm` -- The DataMatrix to write.
- `path` -- The path to the pickle file.

__Keywords:__

- `protocol` -- The pickle protocol.
	- Default: -1

</div>

<div class="FunctionDoc YAMLDoc" id="writetxt" markdown="1">

## function __writetxt__\(dm, path, delimiter=u',', quotechar=u'"'\)

Writes a DataMatrix to a csv file.

__Example:__

~~~ .python
io.writetxt(dm, 'data.csv')
~~~

__Arguments:__

- `dm` -- The DataMatrix to write.
- `path` -- The path to the pickle file.

__Keywords:__

- `delimiter` -- The delimiter characer.
	- Default: ','
- `quotechar` -- The quote character.
	- Default: '"'

</div>

<div class="FunctionDoc YAMLDoc" id="writexlsx" markdown="1">

## function __writexlsx__\(dm, path\)

Writes a DataMatrix to an Excel 2010 xlsx file. The first sheet will
contain a regular table with all non-series columns. SeriesColumns are
saved as individual sheets.

__Example:__

~~~ .python                             
io.writexlsx(dm, 'data.xlsx')
~~~

__Arguments:__

- `dm` -- The DataMatrix to write.
- `path` -- The path to the xlsx file.

</div>

</div>

