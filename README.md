leo - a german<->english language translation script
====================================================

leo is a python script that queries `dict.leo.org` for one or more given keywords
and prints their meanings and translations to stdout

Installation
------------

If you want to install leo system-wide, you should use setup.py:

	 python setup.py install

This will invoke python's setuptools and install leo to the system's
site-packages directory and create an executable script in `/usr/bin/leo`
To choose other install locations refer to setuptool's help by invoking

	 python setup.py install --help

If you do not wish to install leo system-wide you can simply call it by invoking

	 leo/leo.py

from the directory you downloaded leo to.

Usage
-----

Start leo by invoking

	 leo <keyword 1> [keyword 2] ...

when leo has been installed system-wide or by invoking

	 leo/leo.py <keyword 1> [keyword 2] ...

from the directory leo has been downloaded to.
All translations found will be printed to stdout

License
-------

[MIT](COPYING)