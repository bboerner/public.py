.. README generated with readmemako.py (github.com/russianidiot/readme-mako.py) and .README dotfiles (github.com/russianidiot-dotfiles/.README)

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

`Examples/`_

.. _Examples/: https://github.com/russianidiot/public.py/tree/master/Examples

Feedback |github_issues| |gitter| |github_follow|

.. |github_issues| image:: https://img.shields.io/github/issues/russianidiot/public.py.svg
	:target: https://github.com/russianidiot/public.py/issues

.. |github_follow| image:: https://img.shields.io/github/followers/russianidiot.svg?style=social&label=Follow
	:target: https://github.com/russianidiot

.. |gitter| image:: https://badges.gitter.im/russianidiot/public.py.svg
	:target: https://gitter.im/russianidiot/public.py
