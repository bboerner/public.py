.. image:: https://img.shields.io/badge/language-python-blue.svg

.. image:: https://img.shields.io/pypi/pyversions/public.svg
   :target: https://pypi.python.org/pypi/public

|codacy| |landscape| |codeclimate| |scrutinizer|

.. |scrutinizer| image:: https://scrutinizer-ci.com/g/russianidiot/public.py/badges/quality-score.png?b=master
   :target: https://scrutinizer-ci.com/g/russianidiot/public.py/master
   :alt: scrutinizer-ci.com

.. |codacy| image:: https://img.shields.io/codacy/6692c8b8d1194b3db696b456b683ad94.svg
   :target: https://www.codacy.com/app/russianidiot-github/public-py/dashboard
   :alt: codacy.com

.. |codeclimate| image:: https://img.shields.io/codeclimate/github/russianidiot/public.py.svg
   :target: https://codeclimate.com/github/russianidiot/public.py
   :alt: codeclimate.com

.. |landscape| image:: https://landscape.io/github/russianidiot/public.py/master/landscape.svg?style=flat
   :target: https://landscape.io/github/russianidiot/public.py/master
   :alt: landscape.io

Install
```````

:code:`[sudo] pip install public`

Usage
`````

.. code:: python
	
	>>> from public import public
	
	>>> @public # decorator
	
	>>> public(*objects) # function
	
	

Example
```````

.. code:: python
	
	>>> @public
		def func(): pass
	
	>>> @public
		class CLS: pass
	
	>>> print(__all__)
	['CLS',func']
	
	# public(*objects) function
	>>> public("name")
	>>> public("name1","name2")
	
	>>> print(__all__)
	['name','name1','name2']
	

Sources:

*	`py_modules/public.py`_

.. _`py_modules/public.py`: https://github.com/russianidiot/public.py/blob/master/py_modules/public.py

Feedback |github_issues| |gitter| |github_follow|

.. |github_issues| image:: https://img.shields.io/github/issues/russianidiot/public.py.svg
	:target: https://github.com/russianidiot/public.py/issues

.. |github_follow| image:: https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow
	:target: https://github.com/russianidiot

.. |gitter| image:: https://badges.gitter.im/russianidiot/public.py.svg
	:target: https://gitter.im/russianidiot/public.py

----

`russianidiot.github.io/python/`_  - Python packages

.. _russianidiot.github.io/python/: http://russianidiot.github.io/python/

`russianidiot.github.io/cli/`_  - command line scripts

.. _russianidiot.github.io/cli/: http://russianidiot.github.io/cli/

`README.rst`_  - generated with `readmemako.py`_ (python+ `mako`_ templates) and `.README`_ dotfiles

.. _README.rst: https://github.com/russianidiot/public.py/blob/master/.README/pypi.python.org/README.rst
.. _readmemako.py: http://github.com/russianidiot/readmemako.py/
.. _mako: http://www.makotemplates.org/
.. _.README: https://github.com/russianidiot-dotfiles/.README