xfcs dashboard
==============

Create interactive plots for FCS file metadata (3.0, 3.1).

Metadata plots are generated as a self contained html file.
Multiple display options are provided to hide or show parameters, calculated mean values, and customized time range.



Installation
------------

::

    python setup.py install

Command Line Usage
------------------

For stand alone usage:
::

    xfcsdashboard -i <metadata.csv>


Used in combination with metadata extraction in xfcs (requires xfcs installed):
::

    xfcsmeta [--options] --dashboard


Requirements
------------

- Python 3.5 or greater
- pandas
- plotly

License
-------

xfcsdashboard is released under the BSD 2-clause license. See
`LICENSE <https://raw.githubusercontent.com/j4c0bs/xfcsdashboard/master/LICENSE.txt>`_
for details.
