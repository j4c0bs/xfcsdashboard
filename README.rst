xfcs dashboard
==============

Add-on module for `xfcs <https://github.com/j4c0bs/xfcs>`_ to create interactive plots for FCS file metadata (3.0, 3.1).

Metadata plots are generated as a self contained html file.
Multiple display options are provided to hide or show parameters, calculated mean values, and customized time range.

Parameters displayed can be located on the right side of the plot.
To hide (or display) a parameter, click on its name.
To hide all except one parameter, double click on its name.
  .. image:: https://github.com/j4c0bs/xfcs/blob/master/docs/dashboard_preview.png


Installation
------------

Using pip:

::

    pip install xfcsdashboard

Without pip:

::

    python setup.py install


Command Line Usage
------------------

For stand alone usage:
::

    xfcsdashboard -i <metadata.csv>


Used in combination with metadata extraction in `xfcs <https://github.com/j4c0bs/xfcs>`_ (requires xfcs installed):
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
